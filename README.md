## Merhaba, ben Deniz Yıldız 👋

**Yazılım Mühendisi (Yeni Mezun, MCBÜ 2026)** — Yapay zekâ destekli web ve mobil uygulama geliştirme

Claude Code ile ürünleri fikirden yayına kadar götürüyorum: ihtiyacı netleştiriyorum, işi adımlara bölüyorum, yapay zekâ ajanına doğru bağlamı veriyorum, üretilen kodu okuyup test ederek doğruluyorum ve çalışan bir ürüne dönüştürüyorum.

📫 Denizzyldz27@gmail.com

---

### 🚀 Öne çıkan projeler

#### 📱 Sayılı Günler — Düğün planlama mobil uygulaması (Android + iOS)
🌐 [sayiligunler.com](https://sayiligunler.com) · 🔒 Kod özel depoda; mülakatta ekran paylaşımıyla gösterilebilir

- 6 aşamalı, 435 hazır kalemli planlayıcı; randevu hatırlatmaları, misafir takibi, sürükle-bırak masa düzeni, bütçe
- Çevrimdışı öncelikli mimari (SQLite / Drift, sürümlü şema göçleri)
- Firebase Firestore ile iki kullanıcı arasında senkronizasyon, çakışma çözümü, çevrimdışı kuyruk
- Uygulama içi satın alma, AdMob + KVKK/GDPR rıza akışı, kupon sistemi
- Firebase Auth ile korunan yönetim paneli (kupon üretme, duyuru yayımlama)
- **292 otomatik test + 77 güvenlik kuralı testi**, Codemagic CI

`Flutter` `Dart` `SQLite` `Firebase` `AdMob` `In-App Purchase` `Codemagic`

#### 💳 NFC IBAN ve Dijital Kartvizit Sistemi — Web uygulaması + yönetim paneli
🌐 [Canlı demo](https://nfc-iban-sistemi.birdokun.workers.dev) · 🔒 Kod özel depoda; mülakatta ekran paylaşımıyla gösterilebilir

- NFC kart veya QR ile işletmenin IBAN sayfasını / kişinin dijital kartvizitini açan mobil uyumlu web uygulaması
- Yönetim paneli: CRUD, IBAN doğrulama, QR üretimi, Web NFC ile karta yazma, PDF/CSV çıktısı
- Supabase (PostgreSQL) + Row Level Security, kimlik doğrulama, CSP/HSTS güvenlik başlıkları
- Canlıda SQL injection, XSS ve yetki testleri; Playwright ile uçtan uca testler
- GitHub → Cloudflare Workers otomatik yayın

`JavaScript` `Supabase` `PostgreSQL` `Cloudflare Workers` `Playwright`

#### 🥽 [ArchVR](https://github.com/denizzyldz00/archvr) — Mimari modelleri VR'da gezilebilir yapan sistem
🌐 [Canlı site](https://denizzyldz00.github.io/archvr/)

- Electron + React + Three.js masaüstü hazırlayıcı; Meta Quest 3 için WebXR gezinti sitesi
- TypeScript monorepo (npm workspaces, Vite), GitHub Actions ile otomatik dağıtım

`TypeScript` `React` `Electron` `Three.js` `WebXR` `GitHub Actions`

#### Diğer
- [CyberSecNetAnalyzer](https://github.com/denizzyldz00/CyberSecNetAnalyzer) — Python ile ağ trafiği analizi ve saldırı tespiti; OpenAI API ile bulguları sade Türkçe'ye çeviren LLM katmanı
- [ETicaretWeb](https://github.com/denizzyldz00/ETicaretWeb) / [ETicaretOLAP](https://github.com/denizzyldz00/ETicaretOLAP) — MSSQL veritabanı, yıldız şema veri ambarı, SSAS OLAP küpü
- [Turvio](https://github.com/denizzyldz00/turvio) — VR gözlükte çevrimdışı çalışan 360° sanal tur oynatıcısı (A-Frame, IndexedDB, PWA)

---

### 🤖 Yapay zekâ ile nasıl çalışıyorum?

| Adım | Ne yapıyorum |
|---|---|
| **Bağlam** | Kuralları, mimari kararları ve bilinen tuzakları `CLAUDE.md` ve proje notlarında tutuyorum; ajan her oturumda kaldığı yerden devam ediyor |
| **Planlama** | İşi küçük adımlara bölüyorum; her adım ayrı ve açıklayıcı bir commit |
| **Doğrulama** | Üretilen kodu okuyorum; otomatik testler, statik analiz ve yayın öncesi kontrol betikleriyle sabitliyorum |
| **Güvenlik** | Yayındaki uygulamaya SQLi / XSS / yetki testleri yapıp açıkları kapattırıyorum |
| **Sorumluluk** | Ürün kararları, mimari, kod inceleme, test, dokümantasyon ve yayına alma bende |

### 🛠️ Teknolojiler

- **Diller:** JavaScript · TypeScript · Dart · Python · Java · SQL · HTML/CSS
- **Frontend / Mobil:** Flutter · React · Electron · Three.js · PWA
- **Backend / Veri:** Firebase · Supabase · PostgreSQL · MSSQL · SQLite · REST API
- **Yayın / Araçlar:** Git · GitHub Actions · Codemagic · Cloudflare Workers · Firebase Hosting · Playwright
- **Yapay zekâ:** Claude Code · ChatGPT · OpenAI API
