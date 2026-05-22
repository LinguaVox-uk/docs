<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — Голосовой диктант для Chrome с ИИ" />
</p>

<h3 align="center">LinguaVox — Говори на своём языке. Пиши на 21+ языках.</h3>

<p align="center">
  Зажми горячую клавишу · говори · отпусти · текст появляется в любом поле за 3 секунды<br>
  OpenAI Whisper · 21+ языков вывода · 6 режимов ИИ · Без API-ключа · Slack, Gmail, Notion, Jira
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="Лицензия" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/сайт-linguavox-brightgreen" alt="Сайт" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Установить-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/дашборд-открыть-orange" alt="Дашборд" /></a>
  <img src="https://img.shields.io/badge/версия-2.8-green" alt="Версия" />
</p>

---

## Что такое LinguaVox?

LinguaVox — расширение Chrome для голосового диктанта и перевода с ИИ. Зажми Ctrl+Space, говори, отпусти — и транскрибированный текст мгновенно появляется в активном текстовом поле: чат, письмо, форма CRM, комментарий в Jira, блок в Notion. Расширение использует OpenAI Whisper для точности 95%+ и GPT-4o-mini для опционального улучшения текста: исправление грамматики, смена стиля, перевод.

В отличие от большинства инструментов диктовки, LinguaVox не требует собственного ключа OpenAI API. Бесплатные пользователи получают 20 запросов в день из общего пула ключей — без какой-либо настройки. Опытные пользователи и команды могут подключить свой ключ для неограниченного использования.

## Как это работает

**До LinguaVox:** открыть отдельное приложение → записать → скопировать → переключиться → вставить  
**С LinguaVox:**

```
1. Кликни любое поле (Slack, Gmail, Notion, Jira…)
2. Зажми  Ctrl+Space  →  говори
3. Отпусти  →  текст появляется за ~3 секунды  ✓
```

Без копирования. Без переключения. На любом сайте.

## Где работает

| Платформа | Статус | Примечания |
|-----------|--------|------------|
| Slack (браузер) | ✅ | Обработка на уровне браузера, обходит перехват клавиш Slack |
| Gmail | ✅ | Поля написания и ответа |
| Notion | ✅ | Все `contenteditable` блоки |
| Jira | ✅ | Поля задач, комментарии, описания |
| Asana | ✅ | Поля задач и комментариев |
| Salesforce | ✅ | Поля ввода CRM |
| Любой `<input>` / `<textarea>` | ✅ | Универсально — любой сайт |
| Любой `contenteditable` | ✅ | React, Draft.js, Quill совместимо |
| Google Docs | ⚠️ | Ограничено — нестандартный редактор |

## Ключевые возможности

- **Без API-ключа** — 20 запросов/день бесплатно из общего пула, нулевая настройка
- **Собственный ключ (BYOK)** — неограниченное использование по стоимости OpenAI (~$0.50/мес)
- **Организационные аккаунты** — общий пул ключей, управление участниками, аналитика
- **21+ язык** — транскрипция и перевод за один шаг
- **6 режимов улучшения ИИ** — исправление грамматики, деловой стиль, академический, разговорный, творческий, умная полировка
- **Конфиденциальность** — аудио никогда не сохраняется, обрабатывается в реальном времени
- **Менее 3 секунд** — от речи до вставленного текста
- **95%+ точность** — OpenAI Whisper large-v2

## Режимы улучшения ИИ

| Режим | Что делает |
|-------|-----------|
| Умная полировка | Исправить грамматику, улучшить ясность, сохранить смысл |
| Деловой стиль | Переписать для делового общения |
| Исправление грамматики | Только грамматика и орфография |
| Творческий стиль | Яркий, захватывающий текст |
| Разговорный стиль | Дружелюбный, непринуждённый тон |
| Академический стиль | Официальный академический язык |

## Цены

| Тариф | Запросы | Настройка |
|-------|---------|-----------|
| Бесплатно | 20/день | Только вход через Google |
| Собственный ключ | Без ограничений | Твой ключ OpenAI API |
| Организация | Без ограничений | Общий ключ команды + аналитика |

## Часто задаваемые вопросы

### Работает ли LinguaVox в Slack?
Да. Slack перехватывает события клавиатуры на уровне страницы. LinguaVox регистрирует горячую клавишу на уровне браузера через `chrome.commands.onCommand`, обходя перехват Slack. Работает во всех полях сообщений Slack.

### Нужен ли ключ OpenAI API?
Нет. Бесплатные пользователи получают 20 запросов/день из общего пула. Добавь свой ключ в дашборде для неограниченного использования.

### Сохраняется ли мой голос?
Нет. Аудио обрабатывается Whisper в реальном времени и сразу удаляется. Никаких голосовых данных нигде не сохраняется.

### Какие языки поддерживаются?
21+ язык: английский, украинский, русский, испанский, французский, немецкий, японский, корейский, китайский, арабский, португальский, итальянский, польский, нидерландский, турецкий, шведский, румынский, греческий и другие.

## Документация

| Ресурс | Описание |
|--------|----------|
| [Сценарии использования](docs/use-cases.md) | Поддержка клиентов, разработчики, неносители языка |
| [Интеграции](docs/integrations.md) | Детали для Slack, Notion, Jira и др. |
| [FAQ](docs/faq.md) | 20+ ответов |
| [История изменений](docs/changelog.md) | v1.0 → v2.9 |

## Установка

1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — нажми "Добавить в Chrome"
2. Нажми иконку LinguaVox → "Войти через Google"
3. Нажми Ctrl+Space где угодно и начинай говорить

## Ссылки

| | |
|--|--|
| 🌐 Сайт | https://linguavox.uk |
| 📊 Дашборд | https://linguavox.uk/login |
| 🎤 Голосовой перевод | https://linguavox.uk/voice-translation |
| ✨ ИИ-улучшение голоса | https://linguavox.uk/ai-voice-enhancement |
| 🌍 Для не носителей языка | https://linguavox.uk/for-non-native-speakers |
| 👤 Об авторе | https://linguavox.uk/about |
| 🔒 Политика конфиденциальности | https://linguavox.uk/privacy/ |
| 💬 Поддержка | https://linguavox.uk/support/ |

## Сообщество и поддержка

| | |
|--|--|
| 📺 YouTube | [Демо-видео и туториалы](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [Сообщество LinguaVox](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [Присоединиться linguavox.slack.com](https://linguavox.slack.com) |

## Демо-видео

| Сценарий | Смотреть |
|----------|---------|
| Gmail — писать письма голосом | [▶ Смотреть](https://youtube.com/watch?v=FAuBIfE6VYU) |
| WhatsApp Web — голосовые сообщения | [▶ Смотреть](https://youtube.com/watch?v=5UHmNtDlvyY) |
| Telegram Web — голосовой диктант | [▶ Смотреть](https://youtube.com/watch?v=n9u-BR0z4RU) |
| LinkedIn — писать посты голосом | [▶ Смотреть](https://youtube.com/watch?v=xdbDBEPWKW8) |
| Meeting Mode — субтитры в реальном времени | [▶ Смотреть](https://youtube.com/watch?v=agcMJVPKlxE) |

## Лицензия

MIT — см. [LICENSE](LICENSE)