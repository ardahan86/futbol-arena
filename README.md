# FUTBOL ARENA — Excel Entegre Lig Sitesi

Bu paket, gönderilen güncel Excel dosyasındaki 216 futbolcuyu **isim, ülke, doğal mevki, hücum, defans ve genel güç değerlerini değiştirmeden** `players.js` dosyasına yerleştirir.

## Kullanım
1. Dosyaları aynı klasöre çıkarın.
2. `index.html` dosyasını açın (önerilen: statik web sunucusunda yayınlayın).
3. Oyuncu listesi hazır gelir. Güncel Excel'i üstteki Excel yükle alanından yeniden yükleyebilirsiniz.
4. Lig kurun, takım kadrolarını seçin, fikstürü oluşturun ve maçları tek tek simüle edin.

## Sınırlar
- Bu **yerel tarayıcı prototipidir**; çevrim içi çok kullanıcılı oda senkronizasyonu henüz yoktur. Veriler localStorage'da tutulur.
- Maç motoru temel örnek sürümdür. Önceden belirlenen kapsamlı maç motorunun golcü, asist, kilit pas, kartlar, 60/75/85. dakika değişiklikleri ve tam istatistik sistemi henüz uygulanmamıştır.
- Mevki filtresi temel taslaktır; karma mevkiler için ayrıntılı kurallar sonraki sürümde test edilmelidir.
- İkili averaj ve rövanşlı fikstür uygulaması ilk sürümdür, lig kullanımından önce test edilmelidir.
- Excel okuma kütüphanesi CDN üzerinden geldiği için Excel'i yeniden yüklemek internet gerektirir; gömülü 216 futbolcu internet olmadan da listelenir.
