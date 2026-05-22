<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — Chrome کے لیے AI آواز ڈکٹیشن" />
</p>

<h3 align="center">LinguaVox — Chrome کے لیے AI آواز ڈکٹیشن · 21+ زبانوں میں ٹرانسکرپشن اور ترجمہ</h3>

<p align="center">
  ہاٹ کی دبائیں · بولیں · چھوڑیں · متن خودبخود کسی بھی ویب فیلڈ میں داخل ہو جاتا ہے<br>
  OpenAI Whisper · 21+ زبانیں · 6 AI موڈز · میٹنگز میں ریئل ٹائم سب ٹائٹلز · API کی ضرورت نہیں
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/لائسنس-MIT-blue.svg" alt="لائسنس" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/ویب سائٹ-linguavox-brightgreen" alt="ویب سائٹ" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-مفت%20انسٹال-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/ڈیش بورڈ-کھولیں-orange" alt="ڈیش بورڈ" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/ورژن-3.0.0-green" alt="ورژن" /></a>
</p>

---

## LinguaVox کیا ہے؟

LinguaVox ایک Chrome ایکسٹینشن ہے جو AI کی مدد سے آواز کو متن میں تبدیل کرتی ہے اور ترجمہ کرتی ہے۔ Ctrl+Space دبائیں، بولیں، چھوڑیں — ٹرانسکرائبڈ متن فوری طور پر فعال فیلڈ میں ظاہر ہوتا ہے: چیٹ، ای میل، CRM فارم، Jira میں تبصرہ، Notion میں بلاک۔ ایکسٹینشن 95%+ درستگی کے لیے OpenAI Whisper اور اختیاری متن کی بہتری کے لیے GPT-4o-mini استعمال کرتی ہے۔

زیادہ تر ڈکٹیشن ٹولز کے برعکس، LinguaVox کو اپنی OpenAI API key کی ضرورت نہیں۔ مفت صارفین شیئرڈ پول سے روزانہ 20 درخواستیں حاصل کرتے ہیں — بغیر کسی ترتیب کے۔ پیشرفتہ صارفین اور ٹیمیں لامحدود استعمال کے لیے اپنی key جوڑ سکتے ہیں۔

**v3.0 — میٹنگ موڈ:** Google Meet، Zoom، Teams اور کسی بھی براؤزر پر مبنی کال کے لیے ریئل ٹائم ترجمہ شدہ سب ٹائٹلز۔ ٹیب آڈیو Chrome API کے ذریعے کیپچر ہوتا ہے → Deepgram کو بھیجا جاتا ہے → سب ٹائٹلز فلوٹنگ اوورلے کے طور پر ظاہر ہوتے ہیں۔

## یہ کیسے کام کرتا ہے

**LinguaVox سے پہلے:** الگ ایپ کھولیں → ریکارڈ کریں → کاپی کریں → براؤزر پر جائیں → پیسٹ کریں  
**LinguaVox کے ساتھ:**

```
1. کسی بھی ویب فیلڈ میں کلک کریں (Slack, Gmail, Notion, Jira…)
2. Ctrl+Space دبائیں اور رکھیں  →  بولیں
3. چھوڑیں  →  ~3 سیکنڈ میں متن ظاہر ہوتا ہے  ✓
```

کاپی پیسٹ نہیں۔ ایپ سوئچنگ نہیں۔ کسی بھی سائٹ پر۔

## کہاں کام کرتا ہے

| پلیٹ فارم | حالت | نوٹس |
|-----------|------|------|
| Slack (براؤزر) | ✅ | براؤزر لیول ہاٹ کی Slack کی key capture کو bypass کرتی ہے |
| Gmail | ✅ | کمپوز اور ریپلائی فیلڈز |
| Notion | ✅ | تمام contenteditable بلاکس |
| Jira | ✅ | Issue فیلڈز، تبصرے، تفصیل |
| Asana | ✅ | ٹاسک اور تبصرہ فیلڈز |
| Salesforce | ✅ | CRM ان پٹ فیلڈز |
| کوئی بھی `<input>` / `<textarea>` | ✅ | یونیورسل |
| کوئی بھی `contenteditable` | ✅ | React, Draft.js, Quill کے ساتھ compatible |
| Google Docs | ⚠️ | محدود — کسٹم canvas editor |

## اہم خصوصیات

- **API key کی ضرورت نہیں** — شیئرڈ پول سے روزانہ 20 مفت درخواستیں
- **اپنی key لائیں** — OpenAI لاگت پر لامحدود استعمال
- **تنظیمی اکاؤنٹس** — شیئرڈ key pool، ممبر مینجمنٹ، استعمال کا تجزیہ
- **21+ زبانیں** — ایک قدم میں ٹرانسکرپشن + ترجمہ
- **6 AI بہتری موڈز** — گرامر درستگی، کاروباری انداز، تعلیمی، غیررسمی، تخلیقی، ذہین پالش
- **میٹنگ موڈ** — Deepgram کے ذریعے کسی بھی ٹیب آڈیو کے لیے ریئل ٹائم سب ٹائٹلز
- **رازداری** — آواز کا ڈیٹا کبھی محفوظ نہیں ہوتا
- **3 سیکنڈ سے کم** — بولنے سے متن داخل ہونے تک
- **95%+ درستگی** — OpenAI Whisper

## AI بہتری موڈز

| موڈ | کیا کرتا ہے |
|-----|-----------|
| ذہین پالش | گرامر درست کرنا، وضاحت بہتر کرنا، مفہوم برقرار رکھنا |
| کاروباری انداز | پیشہ ورانہ، رسمی لہجہ |
| صرف گرامر | صرف گرامر اور اسپیلنگ درست کرنا |
| تخلیقی انداز | زندہ دل، دلچسپ تحریر |
| غیررسمی انداز | دوستانہ، گفتگو کا لہجہ |
| تعلیمی انداز | رسمی تعلیمی زبان |

## قیمت

| پلان | درخواستیں/دن | ضروریات |
|------|-------------|---------|
| مفت | 20 | Google اکاؤنٹ (OAuth لاگ ان) |
| اپنی key | لامحدود | Google اکاؤنٹ + اپنی OpenAI API key |
| تنظیم | لامحدود | Google اکاؤنٹ + شیئرڈ ٹیم API key |

## اکثر پوچھے جانے والے سوالات

**کیا LinguaVox Slack پر کام کرتی ہے؟**  
ہاں۔ Slack صفحہ کی سطح پر کی بورڈ ایونٹس کیپچر کرتا ہے۔ LinguaVox `chrome.commands.onCommand` کے ذریعے براؤزر کی سطح پر ہاٹ کی رجسٹر کرتی ہے، Slack کی کیپچرنگ کو bypass کرتے ہوئے۔

**کیا مجھے OpenAI API key کی ضرورت ہے؟**  
نہیں۔ مفت صارفین شیئرڈ پول سے روزانہ 20 درخواستیں حاصل کرتے ہیں۔ لامحدود استعمال کے لیے ڈیش بورڈ میں اپنی key شامل کریں۔

**کیا میری آواز ریکارڈ یا محفوظ ہوتی ہے؟**  
نہیں۔ آڈیو Whisper کے ذریعے ریئل ٹائم میں پروسیس ہوتی ہے اور فوری طور پر حذف ہو جاتی ہے۔ کوئی آواز کا ڈیٹا محفوظ نہیں ہوتا۔

**کون سی زبانیں سپورٹ ہیں؟**  
21+ زبانیں: اردو، انگریزی، یوکرینی، روسی، ہسپانوی، فرانسیسی، جرمن، جاپانی، کورین، چینی، عربی، پرتگالی، اطالوی، پولش، ڈچ، ترکی، سویڈش، رومانی، یونانی، فلیپینو، پنجابی اور مزید۔

## کمیونٹی اور سپورٹ

| | |
|--|--|
| 📺 YouTube | [ڈیمو ویڈیوز اور ٹیوٹوریلز](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [LinguaVox کمیونٹی چینل](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [linguavox.slack.com میں شامل ہوں](https://linguavox.slack.com) |

## ڈیمو ویڈیوز

| استعمال کا کیس | دیکھیں |
|----------------|-------|
| Gmail — آواز سے ای میل لکھیں | [▶ دیکھیں](https://youtube.com/watch?v=B9rQOzYE7Ys) |
| WhatsApp Web — آواز کے پیغامات | [▶ دیکھیں](https://youtube.com/watch?v=NRyYxSrTZAM) |
| Telegram Web — آواز ڈکٹیشن | [▶ دیکھیں](https://youtube.com/watch?v=tLxNKNfB0lk) |
| LinkedIn — آواز سے پوسٹ لکھیں | [▶ دیکھیں](https://youtube.com/watch?v=3WX9EmYNYjk) |
| میٹنگ موڈ — ریئل ٹائم سب ٹائٹلز | [▶ دیکھیں](https://youtube.com/watch?v=agcMJVPKlxE) |

## انسٹالیشن

**آپشن A — Chrome Web Store (تجویز کردہ):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — "Chrome میں شامل کریں" پر کلک کریں
2. LinguaVox آئیکون پر کلک کریں → "Google سے سائن ان کریں"
3. کہیں بھی Ctrl+Space دبائیں اور بولنا شروع کریں

**آپشن B — دستی انسٹالیشن (ZIP):**
1. [Releases →](https://github.com/kos-4862/linguavox-public/releases/latest) سے `linguavox-3.0.0.zip` ڈاؤن لوڈ کریں
2. ایک فولڈر میں انزپ کریں
3. Chrome → `chrome://extensions` → "Developer mode" فعال کریں → "Load unpacked" → فولڈر منتخب کریں

## لنکس

| | |
|--|--|
| 🌐 ویب سائٹ | https://linguavox.uk |
| 📊 ڈیش بورڈ | https://linguavox.uk/login |
| 🔒 رازداری کی پالیسی | https://linguavox.uk/privacy/ |
| 🤖 AI دستاویزات (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 سپورٹ | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## لائسنس

MIT — [LICENSE](LICENSE) دیکھیں