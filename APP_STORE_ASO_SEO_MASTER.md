# 🍏 APP STORE OPTIMIZATION (ASO) & SEO MASTER SPECIFICATION
## Application: Briqo 3.5 — Anti-Shame ADHD Companion

---

## 🇹🇷 TURKISH STORE LOCALIZATION (TR ASO)

### 1. App Title (Max 30 Chars)
`Briqo: ADHD & Odak Asistanı` *(Exact 26 chars - Highest Search Keyword Density)*

### 2. Subtitle (Max 30 Chars)
`Dopamin Radarı & Fidget Ajanda` *(Exact 29 chars)*

### 3. Keywords (Max 100 Chars - No spaces after commas for max efficiency)
```text
adhd,odaklanma,dikkat dağınıklığı,dopamin,planlayıcı,alışkanlık,asistan,fidget,ajanda,takip,hafıza,ruhhali
```
*(Exact 99 characters packed without wasting a single character!)*

### 4. Category & Rating
* **Primary Category:** Health & Fitness (Sağlık ve Fitness)
* **Secondary Category:** Productivity (Verimlilik)
* **Age Rating:** 4+ (All ages safe)

### 5. Promotional Text (Max 170 Chars)
`Sevimli ahtapot Brix ile tanışın! Dopamin Radarı, Tek Görev Kalkanı, ASMR balon fidget ve suçluluk hissettirmeyen nöro-dostu odak araçları burada.`

### 6. Full Description (Formatted for High App Store Search Ranking)
```text
ADHD zihninizi cezalandırmayan, onunla iş birliği yapan şefkatli bir yol arkadaşı arıyorsanız Briqo 3.5 ile tanışın!

Uygulamanın sevimli ve empati odaklı maskotu ahtapot Brix, günlük rutinlerinizi yönetmenize, odaklanmanıza ve zihinsel dalgalanmalarınızı dengelemenize yardımcı olur. Geleneksel planlayıcıların aksine Briqo, ADHD bireylerin nörolojik yapısına ve dopamin ihtiyaçlarına özel olarak tasarlanmıştır.

🌟 ÖNE ÇIKAN İNOVATİF ÖZELLİKLER:

🧠 DOPAMİN DURUM RADARI (NÖRO-REÇETE MOTORU)
Zihninizin o anki durumunu tek tıkla tespit edin: Doomscrolling (kilitlenme), Aşırı Yüklenme (panik), Dağınık Zihin veya Hiperfokus. Briqo size anında zıt bir nörolojik reçete ve 10 saniyelik sıfırlama aksiyonu sunar.

🛡️ TEK GÖREV KALKANI (ANTİ-ANALİZ FELCİ)
Listelerdeki karmaşıklığı yok edin. Ekranda sadece 1 aktif mikro görev görünür. Diğer tüm görevler gizlenir, analiz felcine son verir.

🏡 BRIX COZY ODA BUILDER
Görev yaptıkça Brix'in odasını dekore edin! Halı, monstera bitkisi, uykucu kedi ve kahve köşesi satın alarak kendi huzurlu alanınızı oluşturun.

👯 SANAL BODY-DOUBLING & ODAK ZAMANLAYICI
Brix kulaklıklarını takar ve sizinle birlikte çalışır. Lo-fi müzik, Yağmur ASMR ve Kafe ortam sesleri eşliğinde Pomodoro zamanlayıcısı.

🫧 ASMR FIDGET BALON OYUNU
Zihinsel huzursuzluğunuzu ve motor stresinizi azaltmak için tasarlanmış, ASMR sesli pop fidget oyun alanı. Balon patlatırken sanal ödüller (DP) kazanın!

🫂 SIFIR SUÇLULUK (NO-SHAME STREAK) SİSTEMİ
Giriş yapmayı unuttuğunuzda sizi sıfırlayan veya suçlu hissettiren sert kuralları unutun. Brix sizi yargılamayan, sevgi ve motivasyon dolu empati mesajlarıyla karşılar.

Briqo, nöro-çeşitliliği kutlayan ve zihninizi zorlamak yerine onunla uyum içinde çalışan bir yaşam asistanıdır.
```

---

## 🇺🇸 ENGLISH STORE LOCALIZATION (US/GLOBAL ASO)

### 1. App Title (Max 30 Chars)
`Briqo: ADHD Focus Companion` *(Exact 27 chars)*

### 2. Subtitle (Max 30 Chars)
`Dopamine Radar & ASMR Fidget` *(Exact 28 chars)*

### 3. Keywords (Max 100 Chars)
```text
adhd,focus,dopamine,planner,fidget,body doubling,habit,waiting mode,executive dysfunction,asmr,timer
```

### 4. Promotional Text (Max 170 Chars)
`Meet Brix, your cute ADHD buddy! Enjoy the Dopamine State Radar, Single-Task Shield, ASMR fidget games, and zero-guilt habit coaching tailored for neurodivergent minds.`

---

## 🚀 AUTOMATED DEPLOYMENT TRIGGER

The Github Actions automated release workflow is configured in `.github/workflows/deploy-appstore.yml`. 

To trigger the automated release pipeline, push a version tag:
```bash
git tag -a v3.5.0 -m "Release Briqo 3.5 to App Store"
git push origin v3.5.0
```
This triggers Fastlane to build the Xcode workspace and automatically submit Briqo to App Store Connect!
