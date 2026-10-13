# FUTBOL ARENA — Lig Sitesi

Statik web uygulaması: `index.html`, `styles.css`, `players.js`, `app.js`.

## Yayınlama
1. GitHub deposunun ana dizinindeki aynı isimli dosyaları bu pakettekilerle değiştirin.
2. `players.js` dosyası futbolcu veri tabanını taşır. Excel'deki futbolcu puanlarını değiştirmeyin.
3. Değişiklikleri `main` dalına yükleyin. GitHub Pages otomatik yeniden yayınlar.
4. Siteyi açıp tarayıcıda zorla yenileyin: Windows `Ctrl + Shift + R`.

## Maç raporu
Maç simülasyonu tamamlandığında maç detay penceresi açılır. Olay akışı; goller, golcü ve asist, sarı/kırmızı kartlar ve oyuncu değişiklikleri içerir. Takım istatistikleri; topa sahip olma, şut, isabetli şut, xG, korner, faul, kartlar ve pas isabetidir. Olaylar simülasyon tarafından üretilir; oyuncu hücum, defans ve genel güç puanları değiştirilmez.

## Bilinen sınırlar
- Veriler bu sürümde tarayıcı `localStorage` alanında saklanır; farklı cihazlar arasında ortak lig senkronizasyonu için Firebase bağlantısı gerekir.
- Maç istatistikleri oyun simülasyonu çıktısıdır; gerçek maç verisi değildir.
- Yeni sürüm eski sürümle aynı yerel depolama anahtarını kullanır. Önceden oynanan maçlarda ayrıntılı `details` alanı bulunmuyorsa yalnızca yeni simüle edilen maçlarda ayrıntı raporu çıkar.
