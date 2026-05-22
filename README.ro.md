<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — Dictare Vocală cu AI pentru Chrome" />
</p>

<h3 align="center">LinguaVox — Dictare Vocală cu AI pentru Chrome · Transcriere și Traducere în 21+ Limbi</h3>

<p align="center">
  Apasă scurtătura · vorbește · eliberează · textul apare automat în orice câmp web<br>
  OpenAI Whisper · 21+ limbi · 6 moduri AI · Subtitrări în timp real la ședințe · Fără cheie API
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/licență-MIT-blue.svg" alt="Licență" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/site-linguavox-brightgreen" alt="Site" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Instalare%20Gratuită-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/panou%20de%20control-deschide-orange" alt="Panou de control" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/versiune-3.0.0-green" alt="Versiune" /></a>
</p>

---

## Ce este LinguaVox?

LinguaVox este o extensie Chrome pentru dictare vocală și traducere cu inteligență artificială. Apasă Ctrl+Spațiu, vorbește, eliberează — textul transcris apare imediat în câmpul activ: chat, e-mail, formular CRM, comentariu în Jira, bloc în Notion. Extensia utilizează OpenAI Whisper pentru o precizie de 95%+ și GPT-4o-mini pentru îmbunătățirea opțională a textului: corectare gramaticală, schimbare de stil, traducere.

Spre deosebire de majoritatea instrumentelor de dictare, LinguaVox nu necesită o cheie API OpenAI proprie. Utilizatorii gratuiți primesc 20 de cereri pe zi din grupul partajat — fără nicio configurare. Utilizatorii avansați și echipele pot conecta propria cheie pentru utilizare nelimitată.

**v3.0 — Modul Ședință:** subtitrări traduse în timp real pentru Google Meet, Zoom, Teams și orice apel din browser. Sunetul filei este capturat prin API-ul Chrome → trimis la Deepgram → subtitrările apar ca un overlay flotant.

## Cum funcționează

**Înainte de LinguaVox:** deschide o aplicație separată → înregistrează → copiază → comută la browser → lipește  
**Cu LinguaVox:**

```
1. Fă clic în orice câmp web (Slack, Gmail, Notion, Jira…)
2. Ține apăsat  Ctrl+Spațiu  →  vorbește
3. Eliberează  →  textul apare în ~3 secunde  ✓
```

Fără copiere-lipire. Fără schimbarea aplicației. Pe orice site.

## Unde funcționează

| Platformă | Status | Note |
|-----------|--------|------|
| Slack (browser) | ✅ | Scurtătură la nivel de browser ocolește captura de taste Slack |
| Gmail | ✅ | Câmpuri de compunere și răspuns |
| Notion | ✅ | Toate blocurile contenteditable |
| Jira | ✅ | Câmpuri de probleme, comentarii, descrieri |
| Asana | ✅ | Câmpuri de sarcini și comentarii |
| Salesforce | ✅ | Câmpuri de intrare CRM |
| Orice `<input>` / `<textarea>` | ✅ | Universal |
| Orice `contenteditable` | ✅ | Compatibil cu React, Draft.js, Quill |
| Google Docs | ⚠️ | Limitat — editor canvas personalizat |

## Funcții principale

- **Fără cheie API necesară** — 20 cereri/zi gratuite prin grup partajat
- **Adaugă propria cheie** — utilizare nelimitată la costul OpenAI
- **Conturi de organizație** — grup de chei partajate, gestionare membri, analiză utilizare
- **21+ limbi** — transcriere + traducere într-un singur pas
- **6 moduri de îmbunătățire AI** — corectare gramaticală, stil profesional, academic, informal, creativ, șlefuire inteligentă
- **Modul Ședință** — subtitrări în timp real pentru orice audio de filă via Deepgram
- **Confidențialitate totală** — sunetul vocal nu este niciodată stocat
- **Sub 3 secunde** — de la vorbire la inserarea textului
- **Precizie 95%+** — OpenAI Whisper

## Moduri de îmbunătățire AI

| Mod | Ce face |
|-----|---------|
| Șlefuire inteligentă | Corectează gramatica, îmbunătățește claritatea, păstrează sensul |
| Stil profesional | Ton de comunicare profesional și formal |
| Doar gramatică | Corectează doar gramatica și ortografia |
| Stil creativ | Scriere vie și captivantă |
| Stil informal | Ton conversațional și prietenos |
| Stil academic | Limbaj academic formal |

## Prețuri

| Plan | Cereri/zi | Cerințe |
|------|-----------|---------|
| Gratuit | 20 | Cont Google (autentificare OAuth) |
| Propria cheie | Nelimitat | Cont Google + propria cheie API OpenAI |
| Organizație | Nelimitat | Cont Google + cheie API de echipă partajată |

## Întrebări frecvente

**Funcționează LinguaVox pe Slack?**  
Da. Slack interceptează evenimentele de tastatură la nivel de pagină. LinguaVox înregistrează scurtătura la nivel de browser prin `chrome.commands.onCommand`, ocolind captura Slack.

**Am nevoie de o cheie API OpenAI?**  
Nu. Utilizatorii gratuiți primesc 20 cereri/zi din grupul partajat. Adaugă propria cheie în panoul de control pentru utilizare nelimitată.

**Vocea mea este înregistrată sau stocată?**  
Nu. Sunetul este procesat în timp real de Whisper și eliminat imediat. Zero date vocale păstrate.

**Ce limbi sunt suportate?**  
21+ limbi: română, engleză, ucraineană, rusă, spaniolă, franceză, germană, japoneză, coreeană, chineză, arabă, portugheză, italiană, poloneză, olandeză, turcă, suedeză, greacă, tagalog, urdu, punjabi și altele.

## Comunitate și suport

| | |
|--|--|
| 📺 YouTube | [Videoclipuri demonstrative și tutoriale](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [Canalul Comunității LinguaVox](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [Alătură-te la linguavox.slack.com](https://linguavox.slack.com) |

## Videoclipuri demonstrative

| Caz de utilizare | Vizionare |
|-----------------|----------|
| Gmail — redactează e-mailuri prin voce | [▶ Vizionare](https://youtube.com/watch?v=B9rQOzYE7Ys) |
| WhatsApp Web — mesaje vocale | [▶ Vizionare](https://youtube.com/watch?v=NRyYxSrTZAM) |
| Telegram Web — dictare vocală | [▶ Vizionare](https://youtube.com/watch?v=tLxNKNfB0lk) |
| LinkedIn — scrie postări prin voce | [▶ Vizionare](https://youtube.com/watch?v=3WX9EmYNYjk) |
| Modul Ședință — subtitrări în timp real | [▶ Vizionare](https://youtube.com/watch?v=agcMJVPKlxE) |

## Instalare

**Opțiunea A — Chrome Web Store (recomandat):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — apasă "Adaugă în Chrome"
2. Apasă iconița LinguaVox → "Conectare cu Google"
3. Apasă Ctrl+Spațiu oriunde și începe să vorbești

**Opțiunea B — Instalare manuală (ZIP):**
1. Descarcă `linguavox-3.0.0.zip` din [Releases →](https://github.com/kos-4862/linguavox-public/releases/latest)
2. Dezarhivează într-un folder
3. Chrome → `chrome://extensions` → activează "Modul dezvoltator" → "Încarcă extensie nedeclarată" → selectează folderul

## Linkuri

| | |
|--|--|
| 🌐 Site | https://linguavox.uk |
| 📊 Panou de control | https://linguavox.uk/login |
| 🔒 Politică de confidențialitate | https://linguavox.uk/privacy/ |
| 🤖 Documentație AI (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 Suport | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## Licență

MIT — consultați [LICENSE](LICENSE)