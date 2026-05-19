# LinguaVox — Frequently Asked Questions

---

## Getting Started

### How do I install LinguaVox?

Visit the Chrome Web Store and click "Add to Chrome." After installation, click the LinguaVox icon in the Chrome toolbar and sign in with Google. No additional setup is required for the free tier.

### Do I need an OpenAI API key to use LinguaVox?

No. Free users get 20 requests per day via LinguaVox's shared OpenAI key pool — no OpenAI account needed. If you need unlimited usage, add your own OpenAI API key in the [dashboard](https://linguavox.uk/dashboard/apikey).

### How do I start recording?

Hold Ctrl+Space and speak. Release the keys when you're done. Text will appear in whatever input field was active when you released.

### What is the keyboard shortcut?

Default: **Ctrl+Space** (hold to speak, release to transcribe). You can also use Space alone to stop recording after starting with Ctrl+Space.

---

## Accuracy & Performance

### How accurate is LinguaVox?

LinguaVox uses OpenAI Whisper, which achieves 95%+ word-level accuracy for English and major European languages. Accuracy is lower for less-resourced languages. The AI Enhancement step can automatically correct minor transcription errors.

### How long does transcription take?

Under 3 seconds from releasing the hotkey to text appearing. This includes audio encoding, upload to Cloudflare edge, Whisper transcription, optional AI enhancement, and text insertion.

### Why did my text not appear?

Common causes:
1. No input field was focused — click inside a text field before holding the hotkey
2. The website blocked DOM text insertion — try clicking the field again
3. Your daily limit was reached — check your usage in the dashboard
4. The extension needs a page refresh — click the LinguaVox icon to check status

---

## Privacy & Security

### Is my voice recorded or stored?

No. Audio is processed in real-time by OpenAI Whisper and discarded immediately after transcription. LinguaVox does not store audio recordings, transcription history (beyond your local browser storage), or personal voice data.

### Who can see my transcriptions?

Your transcriptions are processed by OpenAI's API (subject to OpenAI's data policy). LinguaVox does not read or store transcription content on its servers beyond the duration of the API call.

### How is my account secured?

Authentication uses Google OAuth 2.0. LinguaVox receives only your Google email and name — no password is ever stored. Session tokens are stored in Chrome's local extension storage, not in cookies or localStorage.

---

## Platform Compatibility

### Does LinguaVox work on Slack?

Yes. Slack intercepts keyboard events at the page level, which breaks standard hotkey detection. LinguaVox handles Slack specifically via `chrome.commands.onCommand` — the hotkey is registered at the browser level. Works in all Slack message fields.

### Does LinguaVox work on Notion?

Yes. Notion's `contenteditable` editor is fully supported. Voice input works in text blocks, comments, database fields, and inline mentions.

### Does LinguaVox work on Google Docs?

Partially. Google Docs uses a custom canvas editor. Basic usage works but full reliability requires a page refresh in complex documents. Full Google Docs support is planned.

### Does LinguaVox work on any website?

For standard `<input>`, `<textarea>`, and `contenteditable` fields: yes, it works on any website. Platforms with non-standard editors (Google Docs canvas, some rich-text editors) may have limited compatibility.

---

## Languages & Translation

### What languages are supported for transcription?

21+ languages: English, Ukrainian, Russian, Spanish, French, German, Japanese, Korean, Chinese (Mandarin), Arabic, Portuguese, Italian, Polish, Dutch, Turkish, Swedish, Romanian, Greek, Tagalog, Urdu, Punjabi, and more.

### How does translation work?

Set Mode to "Translate" in the extension popup. Select your speech language and the target language. Speak → LinguaVox transcribes with Whisper, then sends the text to GPT-4o-mini for translation into the target language.

### Can I speak my native language and get output in a different language?

Yes — this is the primary use case. Set Mode to Translate, select your speech language and target language. Speak your native language naturally — LinguaVox transcribes with Whisper, translates via GPT-4o-mini, optionally polishes with AI enhancement, and inserts the final text into the active field. Example: speak Ukrainian → get polished English in Gmail within 3 seconds.

---

## Plans & Billing

### What does the free tier include?

20 transcription/translation requests per day. No credit card. No OpenAI account needed. Resets every 24 hours.

### What is Bring Your Own Key?

You add your own OpenAI API key in the dashboard. LinguaVox routes your requests through your key — unlimited requests, billed directly to your OpenAI account at standard Whisper + GPT-4o-mini rates.

### How much does Bring Your Own Key cost in practice?

OpenAI Whisper costs $0.006/minute of audio. GPT-4o-mini enhancement costs ~$0.0002/request. For typical usage (20 dictations/day at ~15 seconds each), the monthly cost via BYOK is under $0.50.

### What is the Organization plan?

Org accounts let you create a team with a shared OpenAI API key pool. All members use the org's key — no individual setup needed. Admins see usage analytics in the dashboard.

---

## AI Enhancement

### What are the AI enhancement modes?

| Mode | What it does |
|------|-------------|
| Smart Polish | Fix grammar, improve clarity, keep meaning |
| Business Style | Professional communication tone |
| Grammar Fix | Correct grammar and spelling only |
| Creative Style | Vivid, engaging writing |
| Casual Style | Friendly, conversational |
| Academic Style | Formal academic language |

### Is AI enhancement always on?

No. Enhancement is optional and can be toggled on/off in the popup. If enhancement is off, only Whisper transcription runs.

### What if enhancement makes the text worse?

Enhancement uses a try/catch fallback — if the enhancement API call fails or produces an error, the original Whisper transcription is inserted unchanged.

---

## Technical

### Does LinguaVox work in Incognito mode?

Only if you enable the extension in Incognito mode in Chrome settings (`chrome://extensions/` → LinguaVox → Allow in Incognito).

### Why does LinguaVox need host permissions for all URLs?

LinguaVox injects a content script to handle keyboard events and text insertion on every page you visit. This is required for it to work on any website without you having to enable it per-site.

### Where are my settings stored?

Settings (language, mode, enhancement preferences) are stored in `chrome.storage.sync` — synced across your Chrome profile. Session auth tokens are in `chrome.storage.local`.