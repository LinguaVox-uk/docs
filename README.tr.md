<p align="center">
  <a href="README.md">English</a> · <a href="README.uk.md">Українська</a> · <a href="README.ru.md">Русский</a> · <a href="README.zh-CN.md">中文</a> · <a href="README.es.md">Español</a> · <a href="README.de.md">Deutsch</a> · <a href="README.ja.md">日本語</a> · <a href="README.fr.md">Français</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a> · <a href="README.pt.md">Português</a> · <a href="README.it.md">Italiano</a> · <a href="README.pl.md">Polski</a> · <a href="README.nl.md">Nederlands</a> · <a href="README.tr.md">Türkçe</a> · <a href="README.sv.md">Svenska</a> · <a href="README.ro.md">Română</a> · <a href="README.el.md">Ελληνικά</a> · <a href="README.tl.md">Filipino</a> · <a href="README.ur.md">اردو</a> · <a href="README.pa.md">ਪੰਜਾਬੀ</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/LinguaVox-uk/docs/main/images/banner.png" width="800" alt="LinguaVox — Chrome için Yapay Zeka Destekli Ses Dikte" />
</p>

<h3 align="center">LinguaVox — Chrome için Yapay Zeka Destekli Ses Dikte · 21+ Dil Desteği</h3>

<p align="center">
  Kısayola bas · konuş · bırak · metin otomatik olarak herhangi bir web alanına eklenir<br>
  OpenAI Whisper · 21+ dil · 6 AI iyileştirme modu · Toplantılarda anlık altyazı · API anahtarı gerekmez
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/lisans-MIT-blue.svg" alt="Lisans" /></a>
  <a href="https://linguavox.uk"><img src="https://img.shields.io/badge/website-linguavox-brightgreen" alt="Website" /></a>
  <a href="https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Ücretsiz%20Yükle-blue?logo=googlechrome" alt="Chrome Web Store" /></a>
  <a href="https://linguavox.uk/login"><img src="https://img.shields.io/badge/kontrol%20paneli-aç-orange" alt="Kontrol Paneli" /></a>
  <a href="https://github.com/kos-4862/linguavox-public/releases/latest"><img src="https://img.shields.io/badge/sürüm-3.0.0-green" alt="Sürüm" /></a>
</p>

---

## LinguaVox Nedir?

LinguaVox, günlük çalışmanızdaki dil engelini ortadan kaldıran bir Chrome uzantısıdır. Ana dilinizde doğal bir şekilde konuşun — LinguaVox, OpenAI Whisper aracılığıyla sesi metne dönüştürür, 21'den fazla hedef dile çevirir ve düzenlenmiş metni doldurduğunuz web alanına doğrudan ekler. Kopyala-yapıştır yok, uygulama değiştirme yok, dil bilgisi endişesi yok.

Gmail, Slack, Notion, Jira, Asana, Salesforce'ta çalışır — metin alanı olan her web sitesinde. Ücretsiz plan, herhangi bir yapılandırma gerektirmeden günde 20 istek sunar. İleri düzey kullanıcılar ve ekipler, sınırsız kullanım için kendi OpenAI anahtarını getirebilir.

**v3.0 — Toplantı Modu:** Google Meet, Zoom, Teams ve tarayıcı tabanlı her görüşme için gerçek zamanlı çevrilmiş altyazılar. Sekme sesi Chrome API aracılığıyla yakalanır → Deepgram'a iletilir → altyazılar kayan bir katman olarak görünür.

## Nasıl Çalışır

**LinguaVox'tan önce:** Ayrı bir uygulama aç → kaydet → kopyala → tarayıcıya geç → yapıştır  
**LinguaVox ile:**

```
1. Herhangi bir web alanına tıklayın (Slack, Gmail, Notion, Jira…)
2. Ctrl+Boşluk'u basılı tutun  →  konuşun
3. Bırakın  →  metin ~3 saniyede görünür  ✓
```

Kopyala-yapıştır yok. Uygulama değiştirme yok. Her web sitesinde çalışır.

## Nerede Çalışır

| Platform | Durum | Notlar |
|----------|-------|--------|
| Slack (tarayıcı) | ✅ | Slack'in tuş yakalamayı atlamak için tarayıcı düzeyinde kısayol |
| Gmail | ✅ | Oluşturma ve yanıt alanları |
| Notion | ✅ | Tüm contenteditable blokları |
| Jira | ✅ | Sorun alanları, yorumlar, açıklamalar |
| Asana | ✅ | Görev ve yorum alanları |
| Salesforce | ✅ | CRM giriş alanları |
| Herhangi bir `<input>` / `<textarea>` | ✅ | Evrensel — her web sitesi |
| Herhangi bir `contenteditable` | ✅ | React, Draft.js, Quill uyumlu |
| Google Docs | ⚠️ | Sınırlı — özel canvas editörü |

## Temel Özellikler

- **API anahtarı gerekmez** — paylaşılan havuzdan günde 20 ücretsiz istek
- **Kendi Anahtarınızı Getirin** — OpenAI maliyetiyle sınırsız kullanım
- **Kuruluş hesapları** — paylaşılan anahtar havuzu, üye yönetimi, kullanım analitiği
- **21+ dil** — tek adımda transkripsiyon + çeviri
- **6 AI iyileştirme modu** — dilbilgisi düzeltme, iş stili, akademik, gündelik, yaratıcı, akıllı parlatma
- **Toplantı Modu** — Deepgram aracılığıyla herhangi bir sekme sesi için gerçek zamanlı altyazılar
- **Gizlilik öncelikli** — ses verisi asla saklanmaz
- **3 saniyenin altında** — konuşmadan metin eklemeye kadar uçtan uca
- **%95+ doğruluk** — OpenAI Whisper

## AI İyileştirme Modları

| Mod | Ne Yapar |
|-----|---------|
| Akıllı Parlatma | Dilbilgisini düzeltir, netliği artırır, anlamı korur |
| İş Stili | Profesyonel, resmi ton |
| Sadece Dilbilgisi | Yalnızca dilbilgisi ve yazımı düzeltir |
| Yaratıcı Stil | Canlı, ilgi çekici yazı |
| Gündelik Stil | Samimi, konuşma tonu |
| Akademik Stil | Resmi akademik dil |

## Fiyatlandırma

| Plan | İstek/gün | Gereksinimler |
|------|-----------|---------------|
| Ücretsiz | 20 | Google hesabı (OAuth girişi) |
| Kendi Anahtarınızı Getirin | Sınırsız | Google hesabı + kendi OpenAI API anahtarınız |
| Kuruluş | Sınırsız | Google hesabı + paylaşılan ekip API anahtarı |

## Sıkça Sorulan Sorular

**LinguaVox Slack'te çalışıyor mu?**  
Evet. Slack, klavye olaylarını sayfa düzeyinde yakalar. LinguaVox, `chrome.commands.onCommand` aracılığıyla kısayolu tarayıcı düzeyinde kaydederek Slack'in yakalamayı atlar.

**OpenAI API anahtarına ihtiyacım var mı?**  
Hayır. Ücretsiz kullanıcılar paylaşılan havuzdan günde 20 istek alır. Sınırsız kullanım için kontrol panelinde kendi anahtarınızı ekleyin.

**Sesim kaydediliyor mu?**  
Hayır. Ses, Whisper tarafından gerçek zamanlı olarak işlenir ve hemen silinir. Hiçbir yerde ses verisi saklanmaz.

**Hangi diller destekleniyor?**  
21'den fazla dil: Türkçe, İngilizce, Ukraynaca, Rusça, İspanyolca, Fransızca, Almanca, Japonca, Korece, Çince, Arapça, Portekizce, İtalyanca, Lehçe, Hollandaca, İsveççe, Romence, Yunanca, Filipince, Urduca, Pencapça ve daha fazlası.

## Topluluk ve Destek

| | |
|--|--|
| 📺 YouTube | [Demo videoları ve eğitimler](https://www.youtube.com/channel/UCHRcSLs96N5M_mC4I4XXTMg) |
| 💬 WhatsApp | [LinguaVox Topluluk Kanalı](https://whatsapp.com/channel/0029VbCx0blElaglJ5zvFl3d) |
| 🤝 Slack | [linguavox.slack.com'a katıl](https://linguavox.slack.com) |

## Demo Videoları

| Kullanım Alanı | İzle |
|----------------|------|
| Gmail — sesle e-posta yaz | [▶ İzle](https://youtube.com/watch?v=FAuBIfE6VYU) |
| WhatsApp Web — sesli mesajlar | [▶ İzle](https://youtube.com/watch?v=5UHmNtDlvyY) |
| Telegram Web — sesli dikte | [▶ İzle](https://youtube.com/watch?v=n9u-BR0z4RU) |
| LinkedIn — sesle gönderi yaz | [▶ İzle](https://youtube.com/watch?v=xdbDBEPWKW8) |
| Toplantı Modu — anlık altyazılar | [▶ İzle](https://youtube.com/watch?v=agcMJVPKlxE) |

## Kurulum

**Seçenek A — Chrome Web Store (önerilen):**
1. [Chrome Web Store →](https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea) — "Chrome'a Ekle"ye tıklayın
2. LinguaVox simgesine tıklayın → "Google ile Giriş Yap"
3. Ctrl+Boşluk'a basın ve konuşmaya başlayın

**Seçenek B — Manuel kurulum (ZIP):**
1. [Sürümler →](https://github.com/kos-4862/linguavox-public/releases/latest) adresinden `linguavox-3.0.0.zip` indirin
2. Bir klasöre çıkarın
3. Chrome → `chrome://extensions` → "Geliştirici modu"nu etkinleştirin → "Paketlenmemiş yükle" → klasörü seçin

## Bağlantılar

| | |
|--|--|
| 🌐 Website | https://linguavox.uk |
| 📊 Kontrol Paneli | https://linguavox.uk/login |
| 🔒 Gizlilik Politikası | https://linguavox.uk/privacy/ |
| 🤖 AI Belgeleri (llms.txt) | https://linguavox.uk/llms.txt |
| 💬 Destek | https://linguavox.uk/support/ |
| 📦 Chrome Web Store | https://chromewebstore.google.com/detail/linguavox/dpdejiobdhljljfnkmipjblbpcfhbdea |

## Lisans

MIT — [LICENSE](LICENSE) dosyasına bakın