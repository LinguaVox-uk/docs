<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — AI Spraakdictaat voor Chrome" />
</p>

<h3 align="center">LinguaVox — AI Spraakdictaat voor Chrome · Transcriptie en Vertaling in 21+ Talen</h3>

<p align="center">
  Druk op de sneltoets · spreek · laat los · tekst verschijnt automatisch in elk webveld<br>
  OpenAI Whisper · 21+ talen · 6 AI-verbeteringsmodi · Live ondertiteling in vergaderingen · Geen API-sleutel vereist
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/licentie-MIT-blue.svg" alt="Licentie" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/website-linguavox-brightgreen" alt="Website" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Gratis%20installeren-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/dashboard-openen-orange" alt="Dashboard" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/versie-3.0.0-green" alt="Versie" /></a>
</p>

---

## Wat is LinguaVox?

LinguaVox is een Chrome-extensie voor AI-spraakdictaat en vertaling. Druk op Ctrl+Space, spreek, laat los — de getranscribeerde tekst verschijnt direct in het actieve tekstveld: chat, e-mail, CRM-formulier, opmerking in Jira, blok in Notion. De extensie gebruikt OpenAI Whisper voor 95%+ nauwkeurigheid en GPT-4o-mini voor optionele tekstverbetering: grammaticacorrectie, stijlwijziging, vertaling.

In tegenstelling tot de meeste dicteertools vereist LinguaVox geen eigen OpenAI API-sleutel. Gratis gebruikers ontvangen 20 verzoeken per dag uit de gedeelde pool — zonder enige configuratie. Gevorderde gebruikers en teams kunnen hun eigen sleutel koppelen voor onbeperkt gebruik.

**v3.0 — Vergadermodus:** realtime vertaalde ondertiteling voor Google Meet, Zoom, Teams en elke andere browsergebaseerde vergadering. Tabelaudio wordt vastgelegd via de Chrome API → verzonden naar Deepgram → ondertiteling verschijnt als zwevende overlay.

## Hoe het werkt

**Voor LinguaVox:** aparte app openen → opnemen → kopiëren → wisselen naar browser → plakken  
**Met LinguaVox:**

```
1. Klik in elk webveld (Slack, Gmail, Notion, Jira…)
2. Houd  Ctrl+Spatie  ingedrukt  →  spreek
3. Laat los  →  tekst verschijnt in ~3 seconden  ✓
```

Geen kopiëren-plakken. Geen schakelen tussen apps. Op elke website.

## Waar het werkt

| Platform | Status | Opmerkingen |
|----------|--------|-------------|
| Slack (browser) | ✅ | Sneltoets op browserniveau omzeilt Slack's toetsvastlegging |
| Gmail | ✅ | Schrijf- en antwoordvelden |
| Notion | ✅ | Alle contenteditable-blokken |
| Jira | ✅ | Issue-velden, opmerkingen, beschrijvingen |
| Asana | ✅ | Taak- en opmerkingenvelden |
| Salesforce | ✅ | CRM-invoervelden |
| Elke `<input>` / `<textarea>` | ✅ | Universeel — elke website |
| Elke `contenteditable` | ✅ | Compatibel met React, Draft.js, Quill |
| Google Docs | ⚠️ | Beperkt — aangepaste canvas-editor |

## Belangrijkste functies

- **Geen API-sleutel vereist** — 20 verzoeken/dag gratis via gedeelde pool
- **Eigen sleutel meebrengen** — onbeperkt gebruik tegen OpenAI-kosten
- **Organisatieaccounts** — gedeelde sleutelpool, ledenbeheer, gebruiksanalytics
- **21+ talen** — transcriptie + vertaling in één stap
- **6 AI-verbeteringsmodi** — grammaticacorrectie, zakelijke stijl, academisch, casual, creatief, slim polijsten
- **Vergadermodus** — realtime ondertiteling voor elk tabblad-audio via Deepgram
- **Privacy-first** — spraakgeluid wordt nooit opgeslagen
- **Minder dan 3 seconden** — van spraak tot ingevoegde tekst
- **95%+ nauwkeurigheid** — OpenAI Whisper

## AI-verbeteringsmodi

| Modus | Wat het doet |
|-------|-------------|
| Slim Polijsten | Grammatica corrigeren, helderheid verbeteren, betekenis behouden |
| Zakelijke Stijl | Professionele, formele toon |
| Alleen Grammatica | Alleen grammatica en spelling corrigeren |
| Creatieve Stijl | Levendige, boeiende tekst |
| Casual Stijl | Vriendelijke, conversationele toon |
| Academische Stijl | Formeel academisch taalgebruik |

## Prijzen

| Plan | Verzoeken/dag | Vereisten |
|------|---------------|-----------|
| Gratis | 20 | Google-account (OAuth-login) |
| Eigen sleutel | Onbeperkt | Google-account + eigen OpenAI API-sleutel |
| Organisatie | Onbeperkt | Google-account + gedeelde team-API-sleutel |

## Veelgestelde vragen

**Werkt LinguaVox op Slack?**  
Ja. Slack onderschept toetsenbordgebeurtenissen op paginaniveau. LinguaVox registreert de sneltoets op browserniveau via `chrome.commands.onCommand`, waarmee Slack's vastlegging wordt omzeild.

**Heb ik een OpenAI API-sleutel nodig?**  
Nee. Gratis gebruikers ontvangen 20 verzoeken/dag uit de gedeelde pool. Voeg je eigen sleutel toe in het dashboard voor onbeperkt gebruik.

**Wordt mijn stem opgenomen of opgeslagen?**  
Nee. Audio wordt realtime verwerkt door Whisper en onmiddellijk verwijderd. Nul spraakgegevens bewaard.

**Welke talen worden ondersteund?**  
21+ talen: Nederlands, Engels, Oekraïens, Russisch, Spaans, Frans, Duits, Japans, Koreaans, Chinees, Arabisch, Portugees, Italiaans, Pools, Turks, Zweeds, Roemeens, Grieks, Filipijns, Urdu, Punjabi en meer.

## Community & Ondersteuning

| | |
|--|--|
| 📺 YouTube | [Demovideo's en tutorials](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [LinguaVox Community-kanaal](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [Lid worden van linguavox.slack.com](https://linguavox.slack.com) |

## Demovideo's

| Gebruik | Bekijken |
|---------|---------|
| Gmail — e-mails dicteren | [▶ Bekijken](https://youtube.com/watch?v=FAuBIfE6VYU) |
| WhatsApp Web — spraakberichten | [▶ Bekijken](https://youtube.com/watch?v=5UHmNtDlvyY) |
| Telegram Web — spraakdictaat | [▶ Bekijken](https://youtube.com/watch?v=n9u-BR0z4RU) |
| LinkedIn — berichten dicteren | [▶ Bekijken](https://youtube.com/watch?v=xdbDBEPWKW8) |
| Vergadermodus — live ondertiteling | [▶ Bekijken](https://youtube.com/watch?v=agcMJVPKlxE) |

## Installatie

**Optie A — Chrome Web Store (aanbevolen):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — klik op "Toevoegen aan Chrome"
2. Klik op het LinguaVox-pictogram → "Inloggen met Google"
3. Druk overal op Ctrl+Spatie en begin te spreken

**Optie B — Handmatige installatie (ZIP):**
1. Download `linguavox-3.0.0.zip` van [Releases →](https://github.com/kos-4862/linguavox-public/releases/latest)
2. Pak uit naar een map
3. Chrome → `chrome://extensions` → schakel "Ontwikkelaarsmodus" in → "Uitgepakte extensie laden" → selecteer de map

## Links

| | |
|--|--|
| 🌐 Website | https://linguavox.uk |
| 📊 Dashboard | https://linguavox.uk/login |
| 🔒 Privacybeleid | https://linguavox.uk/privacy/ |
| 🤖 AI-documentatie (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 Ondersteuning | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## Licentie

MIT — zie [LICENSE](LICENSE)