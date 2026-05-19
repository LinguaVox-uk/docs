# LinguaVox — Security & Data Protection

This document explains how LinguaVox handles your API keys, voice data, and personal information. If you have security concerns, read this page before installing.

---

## Your OpenAI API Key (BYOK)

### Where is it stored?

When you enter your OpenAI API key in the dashboard, it is:

1. Sent over HTTPS to the Cloudflare Worker (`api.linguavox.uk`)
2. Stored in **Cloudflare KV** — encrypted at rest by Cloudflare, associated with your user ID
3. **Never stored in the Chrome extension itself** — the extension only holds a JWT session token, not your API key

Your API key never touches your browser's `localStorage`, `sessionStorage`, or `chrome.storage`. It lives server-side only.

### Who can access it?

Only the Cloudflare Worker — running on Cloudflare's infrastructure — reads your key to make OpenAI API calls on your behalf. The key is not logged, not sent to any third party, and not visible to the extension code running in your browser.

### What if I want to remove it?

Go to [Dashboard → API Key](https://linguavox.uk/dashboard/apikey) → click "Remove key". The key is deleted from Cloudflare KV immediately.

---

## Shared Key Pool (Free Tier)

Free users share a pool of OpenAI API keys managed by LinguaVox. This means:

- You never need to provide your own key
- Your requests are routed through one of the shared keys — you cannot see which key is used
- The shared pool is rotated automatically on errors (429, 401) to ensure availability
- Usage is tracked per user per day (20 req/day limit) to prevent abuse

Your audio and transcriptions are **not associated with other users' data** even though a shared API key is used — each request is independent.

---

## Your Voice / Audio Data

### Is audio recorded or stored?

**No.** Audio processing works as follows:

1. You hold Ctrl+Space — your microphone captures audio in the browser via the Web Audio API
2. When you release, the audio blob is encoded to base64 in the Chrome extension (injected content script)
3. The base64 audio is sent via HTTPS to the Cloudflare Worker
4. The Worker forwards it to OpenAI's Whisper API (`https://api.openai.com/v1/audio/transcriptions`)
5. OpenAI returns the transcribed text
6. The transcription text is sent back to the extension and inserted into the active field
7. **The audio is discarded at every step** — the Worker does not write it to storage, logs, or any database

There is no audio file anywhere after this flow. Not on Cloudflare. Not on the LinguaVox server (there is no LinguaVox server — only a stateless Cloudflare Worker).

### Does OpenAI store my audio?

OpenAI's Whisper API processes your audio subject to [OpenAI's data usage policy](https://openai.com/policies/api-data-usage-policies). As of 2024, OpenAI does not use API inputs to train models by default.

### Does LinguaVox store transcription text?

The Worker does not store transcription text. The extension stores a local history in `chrome.storage.local` (on your device only, not synced to any server) for the popup history panel. This history is cleared when you uninstall the extension or clear extension data.

---

## Authentication & Session

### How does login work?

LinguaVox uses Google OAuth 2.0 via `chrome.identity.launchWebAuthFlow`:

1. You click "Sign in with Google" in the extension popup
2. Chrome opens a Google OAuth consent screen (Google's own domain — LinguaVox never sees your Google password)
3. Google returns an authorization code to the extension
4. The extension sends this code to the Cloudflare Worker
5. The Worker exchanges it with Google for your email and name
6. The Worker creates a JWT (JSON Web Token) signed with `HMAC-SHA256` using a secret stored in Cloudflare Worker Secrets (not in code)
7. The JWT is returned to the extension and stored in `chrome.storage.session`

LinguaVox receives only: your Google email and display name. Nothing else from your Google account.

### Where is the JWT stored?

In `chrome.storage.session` — cleared automatically when the browser closes. It is not in cookies, `localStorage`, or `sessionStorage`.

### How long does the session last?

JWT tokens are valid for 30 days. The extension re-authenticates automatically when needed.

---

## Cloudflare Worker Security

- All code runs on Cloudflare's global edge network — no traditional server to breach
- OpenAI API keys are stored as **Cloudflare Worker Secrets** — they are not visible in the Worker code, not in source control, and cannot be read by anyone except the Worker runtime
- JWT signing secret is also stored as a Worker Secret
- All endpoints require a valid JWT Bearer token (except `/api/auth/google`)
- Rate limiting (20 req/day for free tier) is enforced server-side in Cloudflare KV

---

## What Data Does LinguaVox Collect?

| Data | Stored where | Purpose | Retained |
|------|-------------|---------|---------|
| Google email + name | Cloudflare KV | Account identity | Until account deletion |
| Usage counter | Cloudflare KV | Rate limiting | Auto-expires after 25 hours |
| OpenAI API key (BYOK) | Cloudflare KV | API calls | Until you remove it |
| JWT session token | `chrome.storage.local` | Auth | 30 days |
| Transcription history | `chrome.storage.local` | Popup history panel | Until extension uninstall |
| Audio recordings | **Not stored anywhere** | — | Discarded immediately |
| Transcription text (server) | **Not stored anywhere** | — | Discarded immediately |

LinguaVox does **not** collect: browsing history, page content, keystrokes, or any data beyond what is listed above.

---

## Permissions Justification

LinguaVox requests the following Chrome permissions:

| Permission | Why |
|------------|-----|
| `activeTab` | To inject the text insertion code into the currently active tab |
| `scripting` | To execute `startAudioRecording` and `stopAudioRecording` in the page context |
| `storage` | To store settings (language, mode, enhancement) and JWT token |
| `tabs` | To identify which tab is active when recording stops |
| `identity` | To run Google OAuth flow via `chrome.identity.launchWebAuthFlow` |
| `notifications` | To show system notifications on errors |
| `host_permissions: http://*/*, https://*/*` | To inject content script on every page — required for universal text insertion |

The broad host permission (`http://*/*, https://*/*`) is necessary because LinguaVox works on any website. The content script only handles keyboard events and text insertion — it does not read page content.

---

## Reporting Security Issues

Found a vulnerability? Please email: **security@linguavox.uk**

Do not create a public GitHub issue for security vulnerabilities.