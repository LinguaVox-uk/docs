<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — Dyktowanie Głosowe AI dla Chrome" />
</p>

<h3 align="center">LinguaVox — Dyktowanie Głosowe z AI dla Chrome · Transkrypcja i Tłumaczenie w 21+ Językach</h3>

<p align="center">
  Naciśnij skrót · mów · puść · tekst pojawia się automatycznie w dowolnym polu web<br>
  OpenAI Whisper · 21+ języków · 6 trybów AI · Napisy na żywo w spotkaniach · Bez klucza API
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="Licencja" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/strona-linguavox-brightgreen" alt="Strona" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Zainstaluj%20Bezpłatnie-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/dashboard-otwórz-orange" alt="Dashboard" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/wersja-3.0.0-green" alt="Wersja" /></a>
</p>

---

## Czym jest LinguaVox?

LinguaVox to rozszerzenie Chrome do dyktowania głosowego i tłumaczenia z wykorzystaniem sztucznej inteligencji. Naciśnij Ctrl+Space, mów, puść — transkrybowany tekst natychmiast pojawia się w aktywnym polu tekstowym: czat, e-mail, formularz CRM, komentarz w Jira, blok w Notion. Rozszerzenie używa OpenAI Whisper dla dokładności 95%+ i GPT-4o-mini do opcjonalnego poprawiania tekstu: korekta gramatyki, zmiana stylu, tłumaczenie.

W przeciwieństwie do większości narzędzi do dyktowania, LinguaVox nie wymaga własnego klucza API OpenAI. Darmowi użytkownicy otrzymują 20 żądań dziennie ze wspólnej puli — bez żadnej konfiguracji. Zaawansowani użytkownicy i zespoły mogą podłączyć własny klucz dla nieograniczonego użycia.

**v3.0 — Tryb Spotkania:** napisy tłumaczone w czasie rzeczywistym dla Google Meet, Zoom, Teams i każdej innej wideokonferencji w przeglądarce. Audio karty jest przechwytywane przez API Chrome → przesyłane do Deepgram → napisy pojawiają się jako pływający overlay.

## Jak To Działa

**Przed LinguaVox:** otworzyć osobną aplikację → nagrać → skopiować → przełączyć → wkleić  
**Z LinguaVox:**

```
1. Kliknij dowolne pole web (Slack, Gmail, Notion, Jira…)
2. Przytrzymaj  Ctrl+Space  →  mów
3. Puść  →  tekst pojawia się w ~3 sekundy  ✓
```

Bez kopiowania. Bez przełączania aplikacji. Na każdej stronie.

## Gdzie Działa

| Platforma | Status | Uwagi |
|-----------|--------|-------|
| Slack (przeglądarka) | ✅ | Obsługa na poziomie przeglądarki, omija przechwytywanie klawiszy Slack |
| Gmail | ✅ | Pola pisania i odpowiedzi |
| Notion | ✅ | Wszystkie bloki contenteditable |
| Jira | ✅ | Pola zgłoszeń, komentarze, opisy |
| Asana | ✅ | Pola zadań i komentarzy |
| Salesforce | ✅ | Pola CRM |
| Dowolny `<input>` / `<textarea>` | ✅ | Uniwersalne — każda strona |
| Dowolny `contenteditable` | ✅ | Kompatybilny z React, Draft.js, Quill |
| Google Docs | ⚠️ | Ograniczone — niestandardowy edytor canvas |

## Główne Funkcje

- **Bez klucza API** — 20 żądań/dzień za darmo ze wspólnej puli
- **Własny klucz (BYOK)** — nieograniczone użycie po koszcie OpenAI
- **Konta organizacji** — wspólna pula kluczy, zarządzanie członkami, analityka
- **21+ języków** — transkrypcja + tłumaczenie w jednym kroku
- **6 trybów AI** — korekta gramatyki, styl biznesowy, akademicki, casual, kreatywny, inteligentne szlifowanie
- **Tryb Spotkania** — napisy w czasie rzeczywistym dla dowolnego audio karty via Deepgram
- **Prywatność** — audio głosowe nigdy nie jest przechowywane
- **Mniej niż 3 sekundy** — end-to-end od mowy do wstawionego tekstu
- **Dokładność 95%+** — OpenAI Whisper

## Tryby Ulepszania AI

| Tryb | Co robi |
|------|---------|
| Inteligentne Szlifowanie | Poprawia gramatykę, poprawia przejrzystość, zachowuje styl |
| Styl Biznesowy | Profesjonalny, formalny ton |
| Tylko Gramatyka | Korekta gramatyki i ortografii, bez zmiany stylu |
| Styl Kreatywny | Wyrazisty, angażujący język |
| Styl Casual | Przyjazny, konwersacyjny ton |
| Styl Akademicki | Formalny język akademicki |

## Cennik

| Plan | Żądania/dzień | Wymagania |
|------|---------------|-----------|
| Darmowy | 20 | Konto Google (login OAuth) |
| Własny klucz | Nieograniczone | Konto Google + własny klucz API OpenAI |
| Organizacja | Nieograniczone | Konto Google + wspólny klucz API zespołu |

## Często Zadawane Pytania

**Czy LinguaVox działa na Slacku?**  
Tak. Slack przechwytuje zdarzenia klawiatury na poziomie strony. LinguaVox rejestruje skrót na poziomie przeglądarki przez `chrome.commands.onCommand`, omijając przechwytywanie Slacka.

**Czy potrzebuję klucza API OpenAI?**  
Nie. Darmowi użytkownicy otrzymują 20 żądań/dzień ze wspólnej puli. Dodaj własny klucz w panelu dla nieograniczonego użycia.

**Czy mój głos jest nagrywany?**  
Nie. Audio jest przetwarzane w czasie rzeczywistym i natychmiast odrzucane. Zero danych głosowych nigdzie nie jest przechowywanych.

**Jakie języki są obsługiwane?**  
21+ języków: polski, angielski, ukraiński, rosyjski, hiszpański, francuski, niemiecki, japoński, koreański, chiński, arabski, portugalski, włoski, holenderski, turecki, szwedzki, rumuński, grecki, filipiński, urdu, pendżabski i inne.

## Społeczność i Wsparcie

| | |
|--|--|
| 📺 YouTube | [Filmy demo i tutoriale](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [Kanał Społeczności LinguaVox](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [Dołącz do linguavox.slack.com](https://linguavox.slack.com) |

## Filmy Demo

| Przypadek użycia | Oglądaj |
|-----------------|---------|
| Gmail — pisz e-maile głosem | [▶ Oglądaj](https://youtube.com/watch?v=FAuBIfE6VYU) |
| WhatsApp Web — wiadomości głosowe | [▶ Oglądaj](https://youtube.com/watch?v=5UHmNtDlvyY) |
| Telegram Web — dyktowanie głosowe | [▶ Oglądaj](https://youtube.com/watch?v=n9u-BR0z4RU) |
| LinkedIn — pisz posty głosem | [▶ Oglądaj](https://youtube.com/watch?v=xdbDBEPWKW8) |
| Tryb Spotkania — napisy w czasie rzeczywistym | [▶ Oglądaj](https://youtube.com/watch?v=agcMJVPKlxE) |

## Instalacja

**Opcja A — Chrome Web Store (zalecana):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — kliknij "Dodaj do Chrome"
2. Kliknij ikonę LinguaVox → "Zaloguj się przez Google"
3. Naciśnij Ctrl+Space gdziekolwiek i zacznij mówić

**Opcja B — Instalacja ręczna (ZIP):**
1. Pobierz `linguavox-3.0.0.zip` z [Releases →](https://github.com/kos-4862/linguavox-public/releases/latest)
2. Wypakuj do folderu
3. Chrome → `chrome://extensions` → włącz "Tryb dewelopera" → "Załaduj rozpakowane" → wybierz folder

## Linki

| | |
|--|--|
| 🌐 Strona | https://linguavox.uk |
| 📊 Panel | https://linguavox.uk/login |
| 🔒 Polityka prywatności | https://linguavox.uk/privacy/ |
| 🤖 Dokumentacja AI (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 Wsparcie | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## Licencja

MIT — patrz [LICENSE](LICENSE)