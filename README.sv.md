<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — AI Röstdiktering för Chrome" />
</p>

<h3 align="center">LinguaVox — AI Röstdiktering för Chrome · Transkription och Översättning till 21+ Språk</h3>

<p align="center">
  Håll snabbtangenten · tala · släpp · texten infogas automatiskt i vilket webbfält som helst<br>
  OpenAI Whisper · 21+ språk · 6 AI-förbättringslägen · Direkttextning i möten · Ingen API-nyckel krävs
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/licens-MIT-blue.svg" alt="Licens" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/webbplats-linguavox-brightgreen" alt="Webbplats" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Installera%20Gratis-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/instrumentpanel-öppna-orange" alt="Instrumentpanel" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/version-3.0.0-green" alt="Version" /></a>
</p>

---

## Vad är LinguaVox?

LinguaVox är ett Chrome-tillägg för AI-röstdiktering och -översättning. Håll Ctrl+Blanksteg, tala, släpp — den transkriberade texten visas omedelbart i det aktiva textfältet: chatt, e-post, CRM-formulär, kommentar i Jira, block i Notion. Tillägget använder OpenAI Whisper för 95%+ noggrannhet och GPT-4o-mini för valfri textförbättring: grammatikkorrigering, stilbyte, översättning.

Till skillnad från de flesta dikteringsverktyg kräver LinguaVox ingen egen OpenAI API-nyckel. Gratisanvändare får 20 förfrågningar per dag från den delade poolen — utan någon konfiguration. Avancerade användare och team kan ansluta sin egen nyckel för obegränsad användning.

**v3.0 — Mötesläge:** realtidstextning för Google Meet, Zoom, Teams och alla webbläsarbaserade samtal. Flikaudio fångas via Chrome API → skickas till Deepgram → textning visas som ett flytande overlay.

## Hur det fungerar

**Innan LinguaVox:** öppna separat app → spela in → kopiera → byt till webbläsare → klistra in  
**Med LinguaVox:**

```
1. Klicka i ett webbfält (Slack, Gmail, Notion, Jira…)
2. Håll  Ctrl+Blanksteg  →  tala
3. Släpp  →  texten visas på ~3 sekunder  ✓
```

Ingen kopiering-inklistring. Inget appbyte. På vilken webbplats som helst.

## Var det fungerar

| Plattform | Status | Anteckningar |
|-----------|--------|-------------|
| Slack (webbläsare) | ✅ | Tangentbord på webbläsarnivå kringgår Slacks fångst |
| Gmail | ✅ | Skrivfält och svarsfält |
| Notion | ✅ | Alla contenteditable-block |
| Jira | ✅ | Ärendefält, kommentarer, beskrivningar |
| Asana | ✅ | Uppgifts- och kommentarsfält |
| Salesforce | ✅ | CRM-inmatningsfält |
| Valfri `<input>` / `<textarea>` | ✅ | Universell — vilken webbplats som helst |
| Valfri `contenteditable` | ✅ | Kompatibel med React, Draft.js, Quill |
| Google Docs | ⚠️ | Begränsat — anpassad canvas-editor |

## Huvudfunktioner

- **Ingen API-nyckel krävs** — 20 förfrågningar/dag gratis via delad pool
- **Ta med din egen nyckel** — obegränsad användning till OpenAI-kostnad
- **Organisationskonton** — delad nyckeldepå, medlemshantering, användningsanalys
- **21+ språk** — transkription + översättning i ett steg
- **6 AI-förbättringslägen** — grammatikkorrigering, affärsstil, akademisk, avslappnad, kreativ, intelligent polering
- **Mötesläge** — realtidstextning för valfritt flikaudio via Deepgram
- **Integritetsfokuserat** — röstljud lagras aldrig
- **Under 3 sekunder** — från tal till infogad text
- **95%+ noggrannhet** — OpenAI Whisper

## AI-förbättringslägen

| Läge | Vad det gör |
|------|------------|
| Intelligent polering | Rätta grammatik, förbättra tydlighet, bevara mening |
| Affärsstil | Professionell, formell ton |
| Bara grammatik | Rätta endast grammatik och stavning |
| Kreativ stil | Levande, engagerande text |
| Avslappnad stil | Vänlig, konversationell ton |
| Akademisk stil | Formellt akademiskt språk |

## Prissättning

| Plan | Förfrågningar/dag | Krav |
|------|-------------------|------|
| Gratis | 20 | Google-konto (OAuth-inloggning) |
| Ta med din nyckel | Obegränsat | Google-konto + din OpenAI API-nyckel |
| Organisation | Obegränsat | Google-konto + delad team-API-nyckel |

## Vanliga frågor

**Fungerar LinguaVox på Slack?**  
Ja. Slack fångar tangentbordshändelser på sidnivå. LinguaVox registrerar snabbtangenten på webbläsarnivå via `chrome.commands.onCommand`, vilket kringgår Slacks fångst.

**Behöver jag en OpenAI API-nyckel?**  
Nej. Gratisanvändare får 20 förfrågningar/dag från den delade poolen. Lägg till din egen nyckel i instrumentpanelen för obegränsad användning.

**Spelas min röst in eller lagras den?**  
Nej. Ljud bearbetas realtid av Whisper och kasseras omedelbart. Noll röstdata bevaras.

**Vilka språk stöds?**  
21+ språk: svenska, engelska, ukrainska, ryska, spanska, franska, tyska, japanska, koreanska, kinesiska, arabiska, portugisiska, italienska, polska, holländska, turkiska, rumänska, grekiska, tagalog, urdu, punjabi och fler.

## Community och Support

| | |
|--|--|
| 📺 YouTube | [Demovideor och handledningar](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [LinguaVox Community-kanal](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [Gå med i linguavox.slack.com](https://linguavox.slack.com) |

## Demovideor

| Användningsfall | Se |
|----------------|-----|
| Gmail — diktera e-post | [▶ Se](https://youtube.com/watch?v=FAuBIfE6VYU) |
| WhatsApp Web — röstmeddelanden | [▶ Se](https://youtube.com/watch?v=5UHmNtDlvyY) |
| Telegram Web — röstdiktering | [▶ Se](https://youtube.com/watch?v=n9u-BR0z4RU) |
| LinkedIn — diktera inlägg | [▶ Se](https://youtube.com/watch?v=xdbDBEPWKW8) |
| Mötesläge — realtidstextning | [▶ Se](https://youtube.com/watch?v=agcMJVPKlxE) |

## Installation

**Alternativ A — Chrome Web Store (rekommenderat):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — klicka "Lägg till i Chrome"
2. Klicka på LinguaVox-ikonen → "Logga in med Google"
3. Tryck Ctrl+Blanksteg var som helst och börja tala

**Alternativ B — Manuell installation (ZIP):**
1. Ladda ner `linguavox-3.0.0.zip` från [Releases →](https://github.com/kos-4862/linguavox-public/releases/latest)
2. Packa upp i en mapp
3. Chrome → `chrome://extensions` → aktivera "Utvecklarläge" → "Läs in okomprimerat tillägg" → välj mappen

## Länkar

| | |
|--|--|
| 🌐 Webbplats | https://linguavox.uk |
| 📊 Instrumentpanel | https://linguavox.uk/login |
| 🔒 Integritetspolicy | https://linguavox.uk/privacy/ |
| 🤖 AI-dokumentation (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 Support | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## Licens

MIT — se [LICENSE](LICENSE)