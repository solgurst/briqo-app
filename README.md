# 🐙 Briqo — Akıllı ADHD Arkadaşı (v2.0)

Briqo, nöro-çeşitli (ADHD) bireyler için geliştirilmiş, kullanıcının zihin profiline göre adapte olan, eğlenceli ve empati odaklı bir **ADHD Companion** uygulamasıdır.

Uygulamanın maskotu olan sevimli ahtapot **Brix**, kullanıcılara yol arkadaşlığı yapar, onları motive eder ve odaklanmalarına yardımcı olur.

---

## 🌟 Öne Çıkan Özellikler

*   **💾 localStorage Veri Kalıcılığı:** Tüm verileriniz tarayıcınızda güvenle saklanır, ilerlemeniz kaybolmaz.
*   **🫂 Utanç Yok (No-Shame) Streak Sistemi:** Uygulamayı kullanmayı unuttuğunuzda sizi cezalandırmayan, şefkatli ve motive edici geri dönüş mesajları.
*   **🍹 Dopamin Menüsü:** Gün içinde zihninizi tazeleyecek mikro aktiviteler ve ödüllü puan sistemi.
*   **💔 RSD Destek Modu:** Duygusal hassasiyet anları için özel nefes egzersizleri ve Brix telkinleri.
*   **⏳ Bekleme Modu Kurtarıcısı:** Randevu öncesi kilitlenmeleri önleyen geri sayım ve odaklanma yardımcısı.
*   **🎯 Hiperfokus Alarmı:** Su içmeyi hatırlatan, 45 dakikalık odaklanma zamanlayıcısı.
*   **🫧 Fidget Balon Patlatma Oyunu:** ASMR sesli pop fidget alanı ile anlık rahatlama.
*   **💎 Dopamin Dükkanı:** Puanlarınızla Brix için havalı aksesuarlar satın alma ve kuşanma odası.

---

## 🚀 Canlı Yayına Alma (Vercel/Netlify ile Ücretsiz Web Dağıtımı)

Briqo, tamamen istemci tarafında (client-side) çalışan sunucusuz bir uygulamadır. Bu nedenle **herhangi bir sunucu maliyeti yoktur** ve tamamen ücretsiz olarak dağıtılabilir.

### Vercel ile Dağıtım Adımları:
1.  [Vercel](https://vercel.com) hesabınıza giriş yapın.
2.  **Add New > Project** seçeneğini tıklayın.
3.  GitHub hesabınızı bağlayarak bu depoyu (`briqo-app`) seçin.
4.  **Project Settings** kısmında:
    *   **Root Directory** seçeneğini `www` olarak ayarlayın. (Burası kritik! Sadece web çıktılarını dağıtmasını sağlar).
    *   **Build & Development Settings** alanına dokunmanıza gerek yoktur.
5.  **Deploy** butonuna tıklayın. Birkaç saniye içinde uygulamanız canlıya alınacaktır!

---

## 📱 Telefona Kurma (PWA - Progressive Web App)

Briqo, Progressive Web App (PWA) desteğine sahiptir. Bu sayede uygulama mağazalarına yüklemeden önce doğrudan tarayıcı üzerinden telefona yüklenebilir:

*   **Android (Chrome):** Canlı yayın adresini Chrome'da açın, sağ üstteki üç noktaya dokunun ve **"Ana Ekrana Ekle"** seçeneğini seçin.
*   **iOS (Safari):** Canlı yayın adresini Safari'de açın, alttaki **Paylaş** butonuna dokunun ve listeden **"Ana Ekrana Ekle"**yi seçin.

Uygulama telefonunuza kendi ikonu (Brix) ile yüklenecek ve internetiniz olmasa bile tamamen **çevrimdışı (offline)** çalışacaktır.

---

## 🛠️ Native Mobil Derleme (CapacitorJS)

Proje, native Android ve iOS altyapısıyla hazır gelmektedir. Kendi bilgisayarınızda derlemek veya bulut derleme servislerini kullanmak için:

### Gereksinimler:
*   Node.js (LTS sürümü)
*   Android için: Android Studio & JDK
*   iOS için: macOS & Xcode

### Adımlar:
1.  Bağımlılıkları yükleyin:
    ```bash
    npm install
    ```
2.  Web kodlarında değişiklik yaptıysanız native platformlara senkronize edin:
    ```bash
    npx cap sync
    ```
3.  Native projeleri açın ve derleyin:
    *   **Android için:** `npx cap open android` (Android Studio'da açılır, doğrudan imzalı APK/Bundle üretebilirsiniz).
    *   **iOS için:** `npx cap open ios` (Xcode'da açılır).

---

## 🔒 Güvenlik ve Lisans
Bu proje kişisel kullanım ve geliştirme amacıyla tasarlanmıştır. İçerisinde yer alan tüm grafiksel ögeler ve kodlar yerel olarak üretilmiştir.
