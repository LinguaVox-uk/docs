<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — Dettatura Vocale IA per Chrome" />
</p>

<h3 align="center">LinguaVox — Dettatura Vocale con IA per Chrome · Trascrizione e Traduzione in 21+ Lingue</h3>

<p align="center">
  Premi il tasto di scelta rapida · parla · rilascia · il testo si inserisce automaticamente in qualsiasi campo web<br>
  OpenAI Whisper · 21+ lingue · 6 modalità IA · Sottotitoli in tempo reale nelle riunioni · Nessuna chiave API richiesta
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="Licenza" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/sito-linguavox-brightgreen" alt="Sito web" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Installa%20Gratis-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/dashboard-apri-orange" alt="Dashboard" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/versione-3.0.0-green" alt="Versione" /></a>
</p>

---

## Cos'è LinguaVox?

LinguaVox è un'estensione Chrome per la dettatura vocale e la traduzione con intelligenza artificiale. Premi Ctrl+Space, parla, rilascia — il testo trascritto appare immediatamente nel campo attivo: chat, email, form CRM, commento su Jira, blocco su Notion. L'estensione utilizza OpenAI Whisper per una precisione del 95%+ e GPT-4o-mini per il miglioramento opzionale del testo: correzione grammaticale, cambio di stile, traduzione.

A differenza della maggior parte degli strumenti di dettatura, LinguaVox non richiede una chiave API OpenAI personale. Gli utenti gratuiti ricevono 20 richieste al giorno dal pool condiviso — senza configurazione. Gli utenti avanzati e i team possono collegare la propria chiave per un utilizzo illimitato.

**v3.0 — Modalità Riunione:** sottotitoli tradotti in tempo reale per Google Meet, Zoom, Teams e qualsiasi altra videochiamata nel browser. L'audio della scheda viene catturato via API Chrome → inviato a Deepgram → i sottotitoli appaiono come overlay flottante.

## Come Funziona

**Prima di LinguaVox:** aprire un'app separata → registrare → copiare → passare al browser → incollare  
**Con LinguaVox:**

```
1. Clicca qualsiasi campo web (Slack, Gmail, Notion, Jira…)
2. Tieni premuto  Ctrl+Space  →  parla
3. Rilascia  →  il testo appare in ~3 secondi  ✓
```

Nessun copia-incolla. Nessun cambio di app. Su qualsiasi sito.

## Dove Funziona

| Piattaforma | Stato | Note |
|-------------|-------|------|
| Slack (browser) | ✅ | Bypass dell'intercettazione tasti di Slack a livello browser |
| Gmail | ✅ | Composizione e risposta email |
| Notion | ✅ | Tutti i blocchi contenteditable |
| Jira | ✅ | Campi issue, commenti, descrizioni |
| Asana | ✅ | Campi attività e commenti |
| Salesforce | ✅ | Campi CRM |
| Qualsiasi `<input>` / `<textarea>` | ✅ | Universale |
| Qualsiasi `contenteditable` | ✅ | Compatibile con React, Draft.js, Quill |
| Google Docs | ⚠️ | Limitato — editor canvas personalizzato |

## Funzionalità Principali

- **Nessuna chiave API richiesta** — 20 richieste/giorno gratis via pool condiviso
- **Porta la Tua Chiave** — utilizzo illimitato al costo OpenAI
- **Account Organizzazione** — pool di chiavi condiviso, gestione membri, analytics utilizzo
- **21+ lingue** — trascrizione + traduzione in un solo passaggio
- **6 modalità di miglioramento IA** — correzione grammaticale, stile professionale, accademico, casual, creativo, rifinitura intelligente
- **Modalità Riunione** — sottotitoli in tempo reale per qualsiasi audio scheda via Deepgram
- **Privacy totale** — l'audio vocale non viene mai memorizzato
- **Meno di 3 secondi** — end-to-end dal parlato al testo inserito
- **Precisione 95%+** — OpenAI Whisper large-v2

## Modalità di Miglioramento IA

| Modalità | Cosa fa |
|----------|---------|
| Rifinitura Intelligente | Corregge grammatica, migliora chiarezza, preserva il tuo stile |
| Stile Professionale | Tono comunicativo professionale e formale |
| Solo Grammatica | Corregge grammatica e ortografia, nessun cambio di stile |
| Stile Creativo | Linguaggio vivace e coinvolgente |
| Stile Casual | Tono amichevole e conversazionale |
| Stile Accademico | Linguaggio accademico formale |

## Prezzi

| Piano | Richieste/giorno | Requisiti |
|-------|-----------------|-----------|
| Gratuito | 20 | Account Google (login OAuth) |
| Porta la Tua Chiave | Illimitato | Account Google + chiave API OpenAI personale |
| Organizzazione | Illimitato | Account Google + chiave API team condivisa |

## Domande Frequenti

**LinguaVox funziona su Slack?**  
Sì. Slack intercetta gli eventi tastiera a livello di pagina. LinguaVox registra il tasto di scelta rapida a livello browser tramite `chrome.commands.onCommand`, bypassando l'intercettazione di Slack. Funziona in tutti i campi messaggi di Slack.

**Ho bisogno di una chiave API OpenAI?**  
No. Gli utenti gratuiti ricevono 20 richieste/giorno dal pool condiviso. Aggiungi la tua chiave nella dashboard per un utilizzo illimitato.

**La mia voce viene registrata o memorizzata?**  
No. L'audio viene elaborato in tempo reale da Whisper e scartato immediatamente. Zero dati vocali conservati.

**Quali lingue sono supportate?**  
21+ lingue: italiano, inglese, ucraino, russo, spagnolo, francese, tedesco, giapponese, coreano, cinese, arabo, portoghese, polacco, olandese, turco, svedese, rumeno, greco, filippino, urdu, punjabi e altre.

**Quanto è precisa la trascrizione?**  
95%+ di precisione a livello di parola per l'italiano e le principali lingue europee tramite OpenAI Whisper.

## Comunità e Supporto

| | |
|--|--|
| 📺 YouTube | [Video demo e tutorial](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [Canale Community LinguaVox](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [Unisciti a linguavox.slack.com](https://linguavox.slack.com) |

## Video Dimostrativi

| Caso d'uso | Guarda |
|------------|--------|
| Gmail — scrivi email con la voce | [▶ Guarda](https://youtube.com/watch?v=FAuBIfE6VYU) |
| WhatsApp Web — messaggi vocali | [▶ Guarda](https://youtube.com/watch?v=5UHmNtDlvyY) |
| Telegram Web — dettatura vocale | [▶ Guarda](https://youtube.com/watch?v=n9u-BR0z4RU) |
| LinkedIn — scrivi post con la voce | [▶ Guarda](https://youtube.com/watch?v=xdbDBEPWKW8) |
| Modalità Riunione — sottotitoli in tempo reale | [▶ Guarda](https://youtube.com/watch?v=agcMJVPKlxE) |

## Installazione

**Opzione A — Chrome Web Store (consigliata):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — clicca "Aggiungi a Chrome"
2. Clicca l'icona LinguaVox → "Accedi con Google"
3. Premi Ctrl+Space ovunque e inizia a parlare

**Opzione B — Installazione manuale (ZIP):**
1. Scarica `linguavox-3.0.0.zip` da [Releases →](https://github.com/kos-4862/linguavox-public/releases/latest)
2. Decomprimi in una cartella
3. Chrome → `chrome://extensions` → abilita "Modalità sviluppatore" → "Carica decompressa" → seleziona la cartella

## Link

| | |
|--|--|
| 🌐 Sito web | https://linguavox.uk |
| 📊 Dashboard | https://linguavox.uk/login |
| 🔒 Informativa Privacy | https://linguavox.uk/privacy/ |
| 🤖 Documentazione AI (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 Supporto | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## Licenza

MIT — vedi [LICENSE](LICENSE)