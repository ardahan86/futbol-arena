# FUTBOL ARENA güncellemesi

## Bu pakette yapılanlar
- Lig oluştur penceresi ve form gönderimi daha dayanıklı hale getirildi.
- Eski/bozuk yerel lig kaydı ekranın açılmasını engellemesin diye kontrol eklendi.
- Takım sayısına göre yeterli futbolcu olup olmadığı doğrulanıyor (18 oyuncu/takım).
- Maç motorunda hücum, defans ve genel güç birlikte ama farklı ağırlıklarla hesaplamaya katılıyor.
- Kaleci savunması gol ihtimalini etkiliyor; orta saha puanları topa sahip olma ve pas isabetine katkı veriyor.
- Golcü seçimi hücum/genel güç ağırlıklı yapılıyor.
- `players.js` içindeki oyuncu isimleri ve puanlar değiştirilmedi.

## Yayına alma
`index.html`, `app.js`, `styles.css` ve `players.js` dosyalarını GitHub deposuna yükleyin. `players.js` dosyası paketteki oyuncu kayıtlarını korur; sizde daha yeni bir oyuncu listesi varsa o dosyanın üzerine yazmayın, yalnızca `app.js` dosyasını güncelleyin.
