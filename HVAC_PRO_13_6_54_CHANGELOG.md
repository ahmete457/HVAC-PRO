# HVAC PRO V13.6.54

## Kullanıcı arayüzü ve konum seçimi
- Ana menü artık başlangıç ekranıdır; hesaplama kartları menünün altında otomatik görünmez.
- Soğutma, ısıtma, taze hava, kanal tasarımı, hidronik, psikrometri ve cihaz/sistemler ayrı çalışma sayfalarına açılır.
- Çalışma sayfalarına ana menüye dönüş düğmeleri eklendi.
- Taze hava ve kanal tasarımı ana menüde ayrı seçeneklerdir.
- Ülke → il/şehir seçimi Türkiye'de çevrimdışı 81 il listesiyle çalışır. Diğer ülkelerde şehir araması kullanıcı tarafından başlatılan Photon sorgusuyla yapılır ve ülke koduna göre filtrelenir.
- Küresel iklim gateway, ERA5 sorguları ve uygulamaya gömülü şehir iklim veri dosyaları kaldırıldı. Şehir seçimi artık iklim koşullarını otomatik doldurmaz.
- Şehir adı ve ülke kodunun konum arama servisine gönderildiği, proje hesap verilerinin gönderilmediği kullanıcıya açıklanır.
- Eski projelerde kayıtlı ülke/şehir değerlerinin geri yüklenmesi korunur.

## Sürüm
- Android versionName: `13.6.54`
- Android versionCode: `84`

## QA sınırları
- JavaScript hesaplama ve kaynak kontrolleri: PASS.
- Android XML ve proje yapısal kontrolleri: PASS.
- Photon servisinin canlı ağ davranışı ve farklı ülke sonuçları bu ortamda uçtan uca test edilmedi.
- Gradle/Android SDK bulunmadığından APK derlenmedi; gerçek cihazda sayfa navigasyonu, şehir araması ve PDF çıktısı ayrıca denenmelidir.
