# ENGLISH WORLD – Android (APK)

İlkokul 1–4. sınıf İngilizce öğrenme uygulamasının Android projesi (Capacitor 6).

## APK nasıl alınır (Android Studio gerekmez)

1. GitHub'da yeni bir depo aç (ör. `english-world`).
2. Bu klasörün **içindekileri** depoya yükle. `.github` klasörü de yüklenmeli.
3. Depoda **Actions** sekmesine gir → **Build English World APK** iş akışı çalışır
   (çalışmazsa **Run workflow** butonuna bas).
4. Yaklaşık 5–8 dakika sonra iş bitince sayfanın altındaki **Artifacts** bölümünden
   `EnglishWorld-APK` dosyasını indir, zip'i aç → `EnglishWorld.apk`.
5. Telefona/tablete kopyala, aç → "Bilinmeyen kaynaklara izin ver" → Yükle.

## Uygulamayı güncellemek

`www/index.html` dosyasını değiştirip depoya yükle; Actions yeni APK'yı otomatik üretir.

## Bilgiler

- Paket adı: `com.englishworld.kids`
- Tamamen çevrimdışı çalışır. İlerleme cihazda saklanır.
- Sesli okuma, telefonun kendi metin-okuma motorunu kullanır (Google Konuşma Hizmetleri).
  Ses gelmezse: Ayarlar → Erişilebilirlik → Metin okuma çıkışı → İngilizce ses verisini indir.
- Android geri tuşu: pencere → oyun → ana sayfa → çıkış sırasıyla çalışır.
- Ebeveyn panelindeki EXPORT DATA, Android paylaşım menüsünü açar (Drive, WhatsApp, Dosyalar…).
- Üretilen APK "debug" imzalıdır; kişisel kullanım ve test içindir. Google Play için imzalı AAB gerekir.
