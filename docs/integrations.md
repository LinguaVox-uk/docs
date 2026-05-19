# LinguaVox — Platform Integrations

LinguaVox works on any website that uses standard HTML input fields or `contenteditable` editors. This page covers tested platforms and any platform-specific notes.

---

## Fully Supported Platforms

### Slack (`app.slack.com`)

Slack intercepts keyboard events at the page level, which breaks standard hotkey detection in most extensions. LinguaVox handles this via `chrome.commands.onCommand` — the hotkey is registered at the browser level, bypassing Slack's event capture.

**How to use:**
1. Open Slack in Chrome at `app.slack.com`
2. Click any message input field
3. Press Ctrl+Space → speak → release
4. Text inserts directly into the message field

Works in: DMs, channels, thread replies, Slack Canvas.

---

### Gmail (`mail.google.com`)

Works in compose windows and reply fields. Text inserts at the current cursor position.

**How to use:**
1. Open a compose or reply window
2. Click inside the text area
3. Press Ctrl+Space → speak → release

---

### Notion (`notion.so`)

Notion uses a `contenteditable` editor (similar to Slack). LinguaVox uses `document.execCommand('insertText')` for reliable insertion in Notion's rich-text blocks.

**How to use:**
1. Click inside any Notion text block, comment, or database field
2. Press Ctrl+Space → speak → release

Works in: pages, databases, comments, inline mentions.

---

### Jira (`*.atlassian.net`)

Works in issue descriptions, comments, and all text fields.

**How to use:**
1. Click inside a text field or description editor
2. Press Ctrl+Space → speak → release

---

### Asana (`app.asana.com`)

Works in task names, descriptions, comments.

---

### Salesforce

Works in standard CRM input fields, notes, and activity logs.

---

### Google Search

Works in the search input field. Useful for dictating long search queries.

---

### Any Standard Web Form

Any `<input type="text">`, `<textarea>`, or `<input>` field on any website works automatically. LinguaVox tracks focus events and targets whichever field is active when you release the hotkey.

**React / Next.js apps:** LinguaVox uses a React-compatible native input setter that triggers React's synthetic events — text insertion works correctly in controlled components.

---

## Limited / Partial Support

### Google Docs (`docs.google.com`)

Google Docs uses a custom canvas-based editor that is not a standard HTML element. Basic text insertion works in some scenarios, but full reliability requires a page refresh in complex documents. Full Google Docs support is on the roadmap.

### Google Slides

Similar limitations to Google Docs. Works in text boxes but with reduced reliability.

### Microsoft Office Online

Not currently tested. Standard input fields in Word Online work; the main editor canvas has the same limitation as Google Docs.

---

## Text Insertion Methods

LinguaVox uses the following insertion methods in priority order:

1. **React-compatible native input setter** — for `<input>` and `<textarea>` with React state. Triggers `InputEvent(inputType: 'insertText')` to work with controlled components.
2. **`document.execCommand('insertText')`** — for `contenteditable` editors (Slack, Notion, Gmail compose).
3. **Direct DOM manipulation** — fallback for non-React standard inputs.
4. **Clipboard paste** — last resort fallback if DOM insertion fails.

---

## Requesting Platform Support

If LinguaVox doesn't work on a platform you need, open an issue at https://github.com/LinguaVox-uk/docs/issues with:
- The platform name and URL
- Which field doesn't work
- Browser version and OS