<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — AI Voice Dictation Chrome Extension" />
</p>

<h3 align="center">LinguaVox — Speak your language. Write in any of 21+.</h3>

<p align="center">
  Hold a hotkey · speak · release · text appears in any web field · Real-time meeting subtitles in any language<br>
  OpenAI Whisper · Deepgram · 21+ languages · 6 AI enhancement modes · Meeting Mode · No API key required
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/website-linguavox-brightgreen" alt="Website" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Install%20Free-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/dashboard-open-orange" alt="Dashboard" /></a>
  <a href="https://linguavox.uk/llms.txt"><img src="https://img.shields.io/badge/llms.txt-AI%20docs-purple" alt="llms.txt" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/version-3.0.0-green" alt="Version" /></a>
</p>

---

## What is LinguaVox?

LinguaVox is a Chrome extension that removes the language tax from your daily work. Speak naturally in your native language — LinguaVox transcribes via OpenAI Whisper, translates to any of 21+ target languages, and inserts polished text directly into whatever web field you're typing in. No copy-paste, no app switching, no grammar anxiety.

Works in Gmail, Slack, Notion, Jira, Asana, Salesforce — any website with a text field. Free tier includes 20 requests/day with zero setup. Power users and teams can bring their own OpenAI key for unlimited usage.

**v3.0 — Meeting Mode:** real-time translated subtitles for Google Meet, Zoom, Teams, and any other browser-based call. Tab audio captured via Chrome API → streamed to Deepgram → subtitles appear as a floating overlay. Requires explicit consent on first use.

## How It Works

**Before LinguaVox:** open a separate app → record → copy → switch to browser → paste  
**After LinguaVox:**

```
1. Click any web field (Slack, Gmail, Notion, Jira…)
2. Hold  Ctrl+Space  →  speak
3. Release  →  text appears within ~3 seconds  ✓
```

No copy-paste. No switching apps. Works on any website.

## Browser & OS Requirements

| Browser | Status | Notes |
|---------|--------|-------|
| Chrome 88+ | ✅ | Fully supported |
| Edge (Chromium) | ✅ | Should work — same Chromium APIs, not officially tested |
| Brave | ✅ | Should work — not officially tested |
| Opera | ✅ | Should work — not officially tested |
| Firefox | ❌ | Not supported — different extension API |

**OS:** Windows, macOS, Linux — anywhere Chrome/Edge/Brave runs.  
**Google Account required** — free tier login uses Google OAuth. No Google account = no free tier (BYOK still works without Google sign-in is not yet supported).

## Where It Works

| Platform | Status | Notes |
|----------|--------|-------|
| Slack (browser) | ✅ | Browser-level hotkey bypass for Slack's key capture |
| Gmail | ✅ | Compose and reply fields |
| Notion | ✅ | All `contenteditable` blocks |
| Jira | ✅ | Issue fields, comments, descriptions |
| Asana | ✅ | Task and comment fields |
| Salesforce | ✅ | CRM input fields |
| Any `<input>` / `<textarea>` | ✅ | Universal — any website |
| Any `contenteditable` | ✅ | React, Draft.js, Quill compatible |
| Google Docs | ⚠️ | Limited — custom canvas editor |


All OpenAI API calls go through the Worker. API keys never leave the server.

## Key Features

- **No API key required** — 20 req/day free via shared pool, zero setup
- **Bring Your Own Key** — unlimited usage at OpenAI cost (~$0.50/month typical)
- **Organization accounts** — shared key pool, member management, usage analytics
- **21+ languages** — transcription + translation in one step
- **6 AI enhancement modes** — grammar fix, business style, academic, casual, creative, smart polish
- **Meeting Mode** — real-time subtitles for any tab audio (Google Meet, Zoom, Teams…) via Deepgram
- **Privacy-first** — voice audio never stored; meeting audio uses 90s ephemeral tokens, mip_opt_out=true
- **Under 3 seconds** — end-to-end from speech to inserted text
- **95%+ accuracy** — OpenAI Whisper large-v2 equivalent

## AI Enhancement Modes

| Mode | What It Does |
|------|-------------|
| Smart Polish | Fix grammar, improve clarity, keep meaning |
| Business Style | Professional communication tone |
| Grammar Fix | Correct grammar and spelling only |
| Creative Style | Vivid, engaging writing |
| Casual Style | Friendly conversational tone |
| Academic Style | Formal academic language |

## Pricing

| Plan | Requests/day | Requirements |
|------|-------------|--------------|
| Free | 20 | Google Account (OAuth login) |
| Bring Your Own Key | Unlimited | Google Account + your OpenAI API key |
| Organization | Unlimited | Google Account + shared team API key |

## FAQ

### Does LinguaVox work on Slack?
Yes. Slack intercepts keyboard events at the page level. LinguaVox registers the hotkey at the browser level via `chrome.commands.onCommand`, bypassing Slack's capture. Works in all Slack message fields.

### Do I need an OpenAI API key?
No. Free users get 20 requests/day from the shared pool. Add your own key in the dashboard for unlimited usage.

### Is my voice recorded or stored?
No. Audio is processed in real-time by Whisper and discarded immediately. Zero voice data retained anywhere.

### What languages are supported?
21+ languages: English, Ukrainian, Russian, Spanish, French, German, Japanese, Korean, Chinese, Arabic, Portuguese, Italian, Polish, Dutch, Turkish, Swedish, Romanian, Greek, Tagalog, Urdu, Punjabi, and more.

## Documentation

| Resource | Description |
|----------|-------------|
| [Use Cases](docs/use-cases.md) | Customer support, devs, non-native speakers, RSI |
| [Integrations](docs/integrations.md) | Platform-specific notes for Slack, Notion, Jira, etc. |
| [Security & Data Protection](docs/security.md) | How API keys, audio, and personal data are handled |
| [FAQ](docs/faq.md) | 20+ answers |
| [Changelog](docs/changelog.md) | v1.0 → v3.0 |

## Installation

**Option A — Chrome Web Store (recommended):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — click "Add to Chrome"
2. Click the LinguaVox icon → "Sign in with Google"
3. Press Ctrl+Space anywhere and start speaking

**Option B — Manual install (ZIP):**
1. Download `linguavox-3.0.0.zip` from [Releases →](https://github.com/kos-4862/linguavox-public/releases/latest)
2. Unzip to a folder
3. Chrome → `chrome://extensions` → enable "Developer mode" → "Load unpacked" → select the folder

**For Bring Your Own Key:** [Dashboard → API Key](https://linguavox.uk/dashboard/apikey)

## Links

| | |
|--|--|
| 🌐 Website | https://linguavox.uk |
| 📊 Dashboard | https://linguavox.uk/login |
| 🎤 Voice Translation | https://linguavox.uk/voice-translation |
| ✨ AI Voice Enhancement | https://linguavox.uk/ai-voice-enhancement |
| 🌍 For Non-Native Speakers | https://linguavox.uk/for-non-native-speakers |
| 👤 About the Author | https://linguavox.uk/about |
| 🔒 Privacy Policy | https://linguavox.uk/privacy/ |
| 🤖 AI docs (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 Support | https://linguavox.uk/support/ |

## Community & Support

| | |
|--|--|
| 📺 YouTube | [Demo videos & tutorials](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [LinguaVox Community Channel](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [Join linguavox.slack.com](https://linguavox.slack.com) |

## Demo Videos

| Use Case | Watch |
|----------|-------|
| Full demo — dictate on any website | [▶ Watch](https://youtube.com/watch?v=B9rQOzYE7Ys) |
| WhatsApp Web — send voice messages | [▶ Watch](https://youtube.com/watch?v=NRyYxSrTZAM) |
| Telegram Web — voice dictation | [▶ Watch](https://youtube.com/watch?v=tLxNKNfB0lk) |
| LinkedIn — write posts by voice | [▶ Watch](https://youtube.com/watch?v=3WX9EmYNYjk) |
| Meeting Mode — real-time subtitles | [▶ Watch](https://youtube.com/watch?v=agcMJVPKlxE) |

## License

MIT — see [LICENSE](LICENSE)
