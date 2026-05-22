<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — Голосовий диктант для Chrome з ШІ" />
</p>

<h3 align="center">LinguaVox — Говори своєю мовою. Пиши на 21+ мовах.</h3>

<p align="center">
  Затисни гарячу клавішу · говори · відпусти · текст з'являється в будь-якому полі за 3 секунди<br>
  OpenAI Whisper · 21+ мов виводу · 6 режимів ШІ · Без API-ключа · Slack, Gmail, Notion, Jira
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="Ліцензія" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/сайт-linguavox-brightgreen" alt="Сайт" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Встановити-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/дашборд-відкрити-orange" alt="Дашборд" /></a>
  <img src="https://img.shields.io/badge/версія-2.8-green" alt="Версія" />
</p>

---

## Що таке LinguaVox?

LinguaVox — це розширення Chrome для голосового диктанту та перекладу з ШІ. Затисни Ctrl+Space, говори, відпусти — і транскрибований текст миттєво з'являється в активному текстовому полі: чат, пошта, форма CRM, коментар у Jira, блок у Notion. Розширення використовує OpenAI Whisper для точності 95%+ і GPT-4o-mini для необов'язкового покращення тексту: виправлення граматики, зміна стилю, переклад.

На відміну від більшості інструментів диктанту, LinguaVox не потребує власного ключа OpenAI API. Безкоштовні користувачі отримують 20 запитів на день із спільного пулу ключів — без жодного налаштування. Досвідчені користувачі та команди можуть підключити власний ключ для необмеженого використання.

## Як це працює

**До LinguaVox:** відкрити окремий застосунок → записати → скопіювати → переключитись → вставити  
**З LinguaVox:**

```
1. Клікни будь-яке поле (Slack, Gmail, Notion, Jira…)
2. Затисни  Ctrl+Space  →  говори
3. Відпусти  →  текст з'являється за ~3 секунди  ✓
```

Без копіювання. Без переключення. На будь-якому сайті.

## Де працює

| Платформа | Статус | Примітки |
|-----------|--------|----------|
| Slack (браузер) | ✅ | Обробка на рівні браузера, обходить перехоплення клавіш Slack |
| Gmail | ✅ | Поля написання і відповіді |
| Notion | ✅ | Всі `contenteditable` блоки |
| Jira | ✅ | Поля задач, коментарі, описи |
| Asana | ✅ | Поля задач і коментарів |
| Salesforce | ✅ | Поля введення CRM |
| Будь-який `<input>` / `<textarea>` | ✅ | Universally — будь-який сайт |
| Будь-який `contenteditable` | ✅ | React, Draft.js, Quill сумісний |
| Google Docs | ⚠️ | Обмежено — нестандартний редактор |

## Ключові можливості

- **Без API-ключа** — 20 запитів/день безкоштовно зі спільного пулу, нульове налаштування
- **Власний ключ (BYOK)** — необмежене використання за вартістю OpenAI (~$0.50/міс типово)
- **Організаційні акаунти** — спільний пул ключів, управління учасниками, аналітика використання
- **21+ мова** — транскрипція та переклад за один крок
- **6 режимів покращення ШІ** — виправлення граматики, діловий стиль, академічний, розмовний, творчий, розумне шліфування
- **Конфіденційність** — аудіо ніколи не зберігається, обробляється в реальному часі
- **Менше 3 секунд** — від мовлення до вставленого тексту
- **95%+ точність** — OpenAI Whisper large-v2

## Режими покращення ШІ

| Режим | Що робить |
|-------|-----------|
| Розумне шліфування | Виправити граматику, покращити ясність, зберегти зміст |
| Діловий стиль | Переписати для ділового спілкування |
| Виправлення граматики | Тільки граматика та орфографія |
| Творчий стиль | Яскравий, захоплюючий текст |
| Розмовний стиль | Дружній, невимушений тон |
| Академічний стиль | Офіційна академічна мова |

## Ціни

| Тариф | Запити | Налаштування |
|-------|--------|--------------|
| Безкоштовно | 20/день | Тільки вхід через Google |
| Власний ключ | Необмежено | Твій ключ OpenAI API |
| Організація | Необмежено | Спільний ключ команди + аналітика |

## Часті питання

### Чи працює LinguaVox у Slack?
Так. Slack перехоплює події клавіатури на рівні сторінки. LinguaVox реєструє гарячу клавішу на рівні браузера через `chrome.commands.onCommand`, обходячи перехоплення Slack. Працює в усіх полях повідомлень Slack.

### Чи потрібен ключ OpenAI API?
Ні. Безкоштовні користувачі отримують 20 запитів/день зі спільного пулу. Додай власний ключ у дашборді для необмеженого використання.

### Чи зберігається мій голос?
Ні. Аудіо обробляється Whisper в реальному часі та одразу видаляється. Жодних голосових даних ніде не зберігається.

### Які мови підтримуються?
21+ мова: англійська, українська, російська, іспанська, французька, німецька, японська, корейська, китайська, арабська, португальська, італійська, польська, нідерландська, турецька, шведська, румунська, грецька та інші.

## Документація

| Ресурс | Опис |
|--------|------|
| [Сценарії використання](docs/use-cases.md) | Підтримка клієнтів, розробники, нерідні носії мови |
| [Інтеграції](docs/integrations.md) | Деталі для Slack, Notion, Jira та ін. |
| [FAQ](docs/faq.md) | 20+ відповідей |
| [Журнал змін](docs/changelog.md) | v1.0 → v2.9 |

## Встановлення

1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — натисни "Додати до Chrome"
2. Натисни іконку LinguaVox → "Увійти через Google"
3. Натисни Ctrl+Space будь-де і починай говорити

## Посилання

| | |
|--|--|
| 🌐 Сайт | https://linguavox.uk |
| 📊 Дашборд | https://linguavox.uk/login |
| 🎤 Голосовий переклад | https://linguavox.uk/voice-translation |
| ✨ Покращення голосу ШІ | https://linguavox.uk/ai-voice-enhancement |
| 🌍 Для не носіїв мови | https://linguavox.uk/for-non-native-speakers |
| 👤 Про автора | https://linguavox.uk/about |
| 🔒 Політика конфіденційності | https://linguavox.uk/privacy/ |
| 💬 Підтримка | https://linguavox.uk/support/ |

## Спільнота та підтримка

| | |
|--|--|
| 📺 YouTube | [Демо-відео та туторіали](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [Спільнота LinguaVox](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [Приєднатись linguavox.slack.com](https://linguavox.slack.com) |

## Демо-відео

| Сценарій | Дивитись |
|----------|---------|
| Gmail — складати листи голосом | [▶ Дивитись](https://youtube.com/watch?v=B9rQOzYE7Ys) |
| WhatsApp Web — голосові повідомлення | [▶ Дивитись](https://youtube.com/watch?v=NRyYxSrTZAM) |
| Telegram Web — голосовий диктант | [▶ Дивитись](https://youtube.com/watch?v=tLxNKNfB0lk) |
| LinkedIn — писати пости голосом | [▶ Дивитись](https://youtube.com/watch?v=3WX9EmYNYjk) |
| Meeting Mode — субтитри в реальному часі | [▶ Дивитись](https://youtube.com/watch?v=agcMJVPKlxE) |

## Ліцензія

MIT — дивись [LICENSE](LICENSE)