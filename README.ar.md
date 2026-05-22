<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — الإملاء الصوتي بالذكاء الاصطناعي لمتصفح Chrome" />
</p>

<h3 align="center">LinguaVox — الإملاء الصوتي بالذكاء الاصطناعي · 21+ لغة · إضافة Chrome</h3>

<p align="center">
  اضغط المفتاح · تحدث · أفلت · يظهر النص تلقائياً في أي حقل · ترجمة فورية في الاجتماعات<br>
  OpenAI Whisper · 21+ لغة · 6 أوضاع تحسين ذكاء اصطناعي · وضع الاجتماعات · لا يتطلب مفتاح API
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/الترخيص-MIT-blue.svg" alt="الترخيص" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/الموقع-linguavox-brightgreen" alt="الموقع" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-تثبيت%20مجاني-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/لوحة%20التحكم-فتح-orange" alt="لوحة التحكم" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/الإصدار-3.0.0-green" alt="الإصدار" /></a>
</p>

---

## ما هي LinguaVox؟

LinguaVox إضافة Chrome للإملاء الصوتي والترجمة بالذكاء الاصطناعي. اضغط Ctrl+Space، تحدث، أفلت — يظهر النص المُنسَّخ فوراً في الحقل النشط: دردشة، بريد إلكتروني، نموذج CRM، تعليق في Jira، كتلة في Notion. تستخدم الإضافة OpenAI Whisper لدقة 95%+ وGPT-4o-mini لتحسين النص اختيارياً: تصحيح النحو، تغيير الأسلوب، الترجمة.

على عكس معظم أدوات الإملاء، لا تتطلب LinguaVox مفتاح API خاصاً بك. يحصل المستخدمون المجانيون على 20 طلباً يومياً من مجموعة مشتركة — دون أي إعداد. يمكن للمستخدمين المتقدمين والفرق ربط مفتاحهم الخاص للاستخدام غير المحدود.

**v3.0 — وضع الاجتماعات:** ترجمة فورية للنصوص لاجتماعات Google Meet وZoom وTeams وأي مكالمة في المتصفح. يُلتقط صوت علامة التبويب عبر Chrome API → يُرسَل إلى Deepgram → تظهر النصوص كطبقة عائمة.

## كيف يعمل

**قبل LinguaVox:** فتح تطبيق منفصل → التسجيل → النسخ → التبديل للمتصفح → اللصق  
**مع LinguaVox:**

```
1. انقر في أي حقل ويب (Slack, Gmail, Notion, Jira…)
2. امسك  Ctrl+Space  →  تحدث
3. أفلت  →  يظهر النص في ~3 ثوانٍ  ✓
```

لا نسخ-لصق. لا تبديل تطبيقات. يعمل على أي موقع.

## أين يعمل

| المنصة | الحالة | ملاحظات |
|--------|--------|---------|
| Slack (متصفح) | ✅ | تجاوز التقاط المفاتيح على مستوى المتصفح |
| Gmail | ✅ | حقول الإنشاء والرد |
| Notion | ✅ | جميع كتل contenteditable |
| Jira | ✅ | حقول المشكلات والتعليقات |
| Asana | ✅ | حقول المهام والتعليقات |
| Salesforce | ✅ | حقول إدخال CRM |
| أي `<input>` / `<textarea>` | ✅ | شامل — أي موقع |
| أي `contenteditable` | ✅ | متوافق مع React وDraft.js وQuill |
| Google Docs | ⚠️ | محدود — محرر canvas مخصص |

## المزايا الرئيسية

- **لا يتطلب مفتاح API** — 20 طلب/يوم مجاناً من مجموعة مشتركة
- **أحضر مفتاحك** — استخدام غير محدود بتكلفة OpenAI
- **حسابات المنظمة** — مجموعة مفاتيح مشتركة، إدارة الأعضاء، تحليلات الاستخدام
- **21+ لغة** — نسخ + ترجمة في خطوة واحدة
- **6 أوضاع تحسين** — تصحيح نحوي، أسلوب مهني، أكاديمي، عامي، إبداعي، صقل ذكي
- **وضع الاجتماعات** — نصوص فورية لأي صوت عبر Deepgram
- **خصوصية كاملة** — لا يُخزَّن الصوت أبداً
- **أقل من 3 ثوانٍ** — من الكلام إلى إدراج النص
- **دقة 95%+** — OpenAI Whisper

## أوضاع التحسين بالذكاء الاصطناعي

| الوضع | ما يفعله |
|-------|---------|
| الصقل الذكي | تصحيح النحو، تحسين الوضوح، الحفاظ على المعنى |
| الأسلوب المهني | نبرة مهنية رسمية |
| تصحيح نحوي فقط | تصحيح القواعد والإملاء دون تغيير الأسلوب |
| الأسلوب الإبداعي | كتابة حيوية وجذابة |
| الأسلوب العامي | نبرة محادثة ودية |
| الأسلوب الأكاديمي | لغة أكاديمية رسمية |

## خطط الأسعار

| الخطة | طلبات/يوم | المتطلبات |
|-------|-----------|-----------|
| مجاني | 20 | حساب Google (تسجيل دخول OAuth) |
| مفتاحك الخاص | غير محدود | حساب Google + مفتاح OpenAI API الخاص |
| المنظمة | غير محدود | حساب Google + مفتاح API مشترك للفريق |

## الأسئلة الشائعة

**هل تعمل LinguaVox على Slack؟**  
نعم. يلتقط Slack أحداث لوحة المفاتيح على مستوى الصفحة. تسجل LinguaVox الاختصار على مستوى المتصفح عبر `chrome.commands.onCommand`، متجاوزةً التقاط Slack.

**هل أحتاج مفتاح API OpenAI؟**  
لا. المستخدمون المجانيون يحصلون على 20 طلباً يومياً. أضف مفتاحك في لوحة التحكم للاستخدام غير المحدود.

**هل يُسجَّل صوتي أو يُخزَّن؟**  
لا. يُعالَج الصوت فورياً بواسطة Whisper ويُحذَف على الفور. لا تُحفَظ أي بيانات صوتية.

**ما اللغات المدعومة؟**  
21+ لغة: العربية، الإنجليزية، الأوكرانية، الروسية، الإسبانية، الفرنسية، الألمانية، اليابانية، الكورية، الصينية، البرتغالية، الإيطالية، البولندية، الهولندية، التركية، السويدية، الرومانية، اليونانية، الفلبينية، الأردية، البنجابية والمزيد.

## المجتمع والدعم

| | |
|--|--|
| 📺 YouTube | [فيديوهات توضيحية وبرامج تعليمية](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [قناة مجتمع LinguaVox](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [انضم إلى linguavox.slack.com](https://linguavox.slack.com) |

## فيديوهات توضيحية

| حالة الاستخدام | مشاهدة |
|----------------|--------|
| Gmail — كتابة رسائل بالصوت | [▶ مشاهدة](https://youtube.com/watch?v=B9rQOzYE7Ys) |
| WhatsApp Web — رسائل صوتية | [▶ مشاهدة](https://youtube.com/watch?v=NRyYxSrTZAM) |
| Telegram Web — إملاء صوتي | [▶ مشاهدة](https://youtube.com/watch?v=tLxNKNfB0lk) |
| LinkedIn — كتابة منشورات بالصوت | [▶ مشاهدة](https://youtube.com/watch?v=3WX9EmYNYjk) |
| وضع الاجتماعات — نصوص فورية | [▶ مشاهدة](https://youtube.com/watch?v=agcMJVPKlxE) |

## التثبيت

**الخيار أ — Chrome Web Store (موصى به):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — انقر "إضافة إلى Chrome"
2. انقر أيقونة LinguaVox → "تسجيل الدخول بـ Google"
3. اضغط Ctrl+Space في أي مكان وابدأ التحدث

**الخيار ب — تثبيت يدوي (ZIP):**
1. حمّل `linguavox-3.0.0.zip` من [الإصدارات →](https://github.com/kos-4862/linguavox-public/releases/latest)
2. فك الضغط في مجلد
3. Chrome → `chrome://extensions` → فعّل "وضع المطور" → "تحميل غير مضغوط" → اختر المجلد

## الروابط

| | |
|--|--|
| 🌐 الموقع | https://linguavox.uk |
| 📊 لوحة التحكم | https://linguavox.uk/login |
| 🔒 سياسة الخصوصية | https://linguavox.uk/privacy/ |
| 🤖 توثيق AI (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 الدعم | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## الترخيص

MIT — انظر [LICENSE](LICENSE)