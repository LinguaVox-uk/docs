# LinguaVox Changelog

## v3.0 — Meeting Mode + Deepgram

- **Meeting Mode** — real-time translated subtitles for any browser-based call (Google Meet, Zoom, Teams, etc.)
- Tab audio captured via Chrome `tabCapture` API → streamed to Deepgram → floating subtitle overlay
- Explicit consent modal on first Meeting Mode use (Deepgram disclosure + Privacy Policy link)
- 90-second ephemeral Deepgram tokens with `mip_opt_out=true` (audio not retained)
- `offscreen.html` document for audio capture in Manifest V3 service worker context
- JWT session tokens moved to `chrome.storage.session` (cleared on browser close)
- Cloudflare Worker: startup secret validation on every fetch, `/api/health` endpoint
- Rate limit increased to 100 req/day on shared pool

## v2.8 — Dashboard + Bring Your Own Key + Org Management

- **Web Dashboard** at `linguavox.uk/dashboard/`
- **Bring Your Own Key** — connect personal OpenAI API key for unlimited usage
- **Organization accounts** — create a team, share API key pool, view member usage analytics
- **Org management** — invite/remove members, owner-level access control
- **Usage analytics** — today's request count + 7-day chart in dashboard overview
- New marketing landing page with pricing section and 3-step onboarding
- Privacy policy page
- Rate limit: 20 requests/day on shared API key pool (unlimited with BYOK)

## v2.7 — AI Enhancement Modes

- 6 AI enhancement modes: Smart Polish, Business Style, Grammar Fix, Creative Style, Casual Style, Academic Style
- Enhancement uses Chat Completions (GPT-4o-mini), not Assistants API
- Try/catch fallback: original transcription preserved if enhancement fails

## v2.6 — Translation Mode

- Speak in any language, get output in any target language
- Translation via GPT-4o-mini after Whisper transcription
- Target language selector in popup

## v2.5 — Multi-language Support

- 21+ languages for transcription
- Language auto-detection option
- Interface localization for 14+ locales

## v2.0 — Cloudflare Worker Backend

- All OpenAI calls moved to Cloudflare Worker — API keys never leave the server
- Google OAuth authentication
- JWT-based session management
- Rate limiting via Cloudflare KV

## v1.0 — Initial Release

- Voice transcription via OpenAI Whisper
- Ctrl+Space hotkey (hold to talk)
- Text insertion into any web input field
- React/Draft.js/Quill compatible text insertion
- Slack support via `chrome.commands.onCommand`