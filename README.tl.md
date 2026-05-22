<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — AI Voice Dictation para sa Chrome" />
</p>

<h3 align="center">LinguaVox — AI Voice Dictation para sa Chrome · Transkripsiyon at Pagsasalin sa 21+ Wika</h3>

<p align="center">
  Pindutin ang hotkey · magsalita · pakawalan · awtomatikong lalabas ang teksto sa anumang web field<br>
  OpenAI Whisper · 21+ wika · 6 na AI mode · Live na subtitle sa mga pulong · Hindi kailangan ng API key
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/lisensya-MIT-blue.svg" alt="Lisensya" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/website-linguavox-brightgreen" alt="Website" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-I--install%20Libre-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/dashboard-buksan-orange" alt="Dashboard" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/bersyon-3.0.0-green" alt="Bersyon" /></a>
</p>

---

## Ano ang LinguaVox?

Ang LinguaVox ay isang Chrome extension para sa AI voice dictation at pagsasalin. Pindutin ang Ctrl+Space, magsalita, pakawalan — ang na-transcribe na teksto ay agad na lalabas sa aktibong text field: chat, email, CRM form, komento sa Jira, bloke sa Notion. Gumagamit ang extension ng OpenAI Whisper para sa 95%+ na katumpakan at GPT-4o-mini para sa opsyonal na pagpapabuti ng teksto: pagwawasto ng gramatika, pagbabago ng istilo, pagsasalin.

Hindi tulad ng karamihan sa mga tool sa diktasyon, hindi nangangailangan ang LinguaVox ng sariling OpenAI API key. Ang mga libreng gumagamit ay nakakakuha ng 20 kahilingan sa isang araw mula sa shared pool — nang walang anumang configuration. Ang mga advanced na gumagamit at mga koponan ay maaaring i-connect ang kanilang sariling key para sa walang limitasyong paggamit.

**v3.0 — Meeting Mode:** real-time na isinalin na mga subtitle para sa Google Meet, Zoom, Teams at anumang browser-based na tawag. Ang tab audio ay nakuha sa pamamagitan ng Chrome API → ipinadala sa Deepgram → ang mga subtitle ay lumabas bilang floating overlay.

## Paano Ito Gumagana

**Bago ang LinguaVox:** buksan ang hiwalay na app → mag-record → kopyahin → lumipat sa browser → i-paste  
**Gamit ang LinguaVox:**

```
1. I-click ang anumang web field (Slack, Gmail, Notion, Jira…)
2. Hawakan ang  Ctrl+Space  →  magsalita
3. Pakawalan  →  lalabas ang teksto sa ~3 segundo  ✓
```

Walang kopya-paste. Walang paglipat ng app. Sa anumang website.

## Saan Ito Gumagana

| Platform | Status | Mga Tala |
|----------|--------|---------|
| Slack (browser) | ✅ | Browser-level na hotkey na lumalampas sa Slack key capture |
| Gmail | ✅ | Mga compose at reply field |
| Notion | ✅ | Lahat ng contenteditable na bloke |
| Jira | ✅ | Mga issue field, komento, paglalarawan |
| Asana | ✅ | Mga task at komento field |
| Salesforce | ✅ | Mga CRM input field |
| Anumang `<input>` / `<textarea>` | ✅ | Universal — anumang website |
| Anumang `contenteditable` | ✅ | Compatible sa React, Draft.js, Quill |
| Google Docs | ⚠️ | Limitado — custom canvas editor |

## Mga Pangunahing Feature

- **Hindi kailangan ng API key** — 20 kahilingan/araw libre mula sa shared pool
- **Dalhin ang iyong sariling key** — walang limitasyong paggamit sa OpenAI cost
- **Mga account ng organisasyon** — shared key pool, pamamahala ng miyembro, analytics ng paggamit
- **21+ wika** — transkripsiyon + pagsasalin sa isang hakbang
- **6 na AI improvement mode** — pagwawasto ng gramatika, business style, academic, casual, creative, smart polishing
- **Meeting Mode** — real-time na mga subtitle para sa anumang tab audio via Deepgram
- **Privacy-first** — ang boses na audio ay hindi kailanman naka-imbak
- **Wala pang 3 segundo** — mula sa pagsasalita hanggang sa na-insert na teksto
- **95%+ katumpakan** — OpenAI Whisper

## Mga AI Improvement Mode

| Mode | Ginagawa |
|------|---------|
| Smart Polishing | Mag-ayos ng gramatika, mapabuti ang kalinawan, mapanatili ang kahulugan |
| Business Style | Propesyonal at pormal na tono |
| Gramatika Lamang | Iwasto lamang ang gramatika at spelling |
| Creative Style | Masigla at nakaka-engganyo na pagsulat |
| Casual Style | Magiliw na conversational na tono |
| Academic Style | Pormal na akademikong wika |

## Pagpepresyo

| Plano | Kahilingan/araw | Mga Kinakailangan |
|-------|----------------|-------------------|
| Libre | 20 | Google account (OAuth login) |
| Sariling Key | Walang limitasyon | Google account + sariling OpenAI API key |
| Organisasyon | Walang limitasyon | Google account + shared team API key |

## Mga Madalas na Tanong

**Gumagana ba ang LinguaVox sa Slack?**  
Oo. Nakakahuli ang Slack ng mga keyboard event sa antas ng pahina. Inirehistro ng LinguaVox ang hotkey sa antas ng browser sa pamamagitan ng `chrome.commands.onCommand`, nilalampasan ang pagkuha ng Slack.

**Kailangan ko ba ng OpenAI API key?**  
Hindi. Ang mga libreng gumagamit ay nakakakuha ng 20 kahilingan/araw mula sa shared pool. Magdagdag ng sariling key sa dashboard para sa walang limitasyong paggamit.

**Nire-record o sino-store ba ang aking boses?**  
Hindi. Ang audio ay pinoproseso nang real-time ng Whisper at agad na tinanggal. Zero boses na data ang nakatago.

**Anong mga wika ang sinusuportahan?**  
21+ wika: Filipino, Ingles, Ukrainiano, Ruso, Espanyol, Pranses, Aleman, Hapon, Koreano, Tsino, Arabiko, Portuges, Italyano, Polish, Dutch, Turko, Swedo, Rumano, Griyego, Urdu, Punjabi at iba pa.

## Komunidad at Suporta

| | |
|--|--|
| 📺 YouTube | [Mga demo video at tutorial](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [LinguaVox Community Channel](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [Sumali sa linguavox.slack.com](https://linguavox.slack.com) |

## Mga Demo Video

| Kaso ng Paggamit | Panoorin |
|-----------------|---------|
| Gmail — mag-compose ng email sa pamamagitan ng boses | [▶ Panoorin](https://youtube.com/watch?v=B9rQOzYE7Ys) |
| WhatsApp Web — mga boses na mensahe | [▶ Panoorin](https://youtube.com/watch?v=NRyYxSrTZAM) |
| Telegram Web — voice dictation | [▶ Panoorin](https://youtube.com/watch?v=tLxNKNfB0lk) |
| LinkedIn — sumulat ng mga post sa pamamagitan ng boses | [▶ Panoorin](https://youtube.com/watch?v=3WX9EmYNYjk) |
| Meeting Mode — real-time na mga subtitle | [▶ Panoorin](https://youtube.com/watch?v=agcMJVPKlxE) |

## Pag-install

**Opsyon A — Chrome Web Store (inirerekomenda):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — i-click ang "Idagdag sa Chrome"
2. I-click ang LinguaVox icon → "Mag-sign in gamit ang Google"
3. Pindutin ang Ctrl+Space kahit saan at simulan ang pagsasalita

**Opsyon B — Manual na pag-install (ZIP):**
1. I-download ang `linguavox-3.0.0.zip` mula sa [Releases →](https://github.com/kos-4862/linguavox-public/releases/latest)
2. I-unzip sa isang folder
3. Chrome → `chrome://extensions` → i-enable ang "Developer mode" → "Load unpacked" → piliin ang folder

## Mga Link

| | |
|--|--|
| 🌐 Website | https://linguavox.uk |
| 📊 Dashboard | https://linguavox.uk/login |
| 🔒 Patakaran sa Privacy | https://linguavox.uk/privacy/ |
| 🤖 AI Docs (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 Suporta | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## Lisensya

MIT — tingnan ang [LICENSE](LICENSE)