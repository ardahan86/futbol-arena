FUTBOL ARENA — 300 OYUNCU / GÜNCEL SİTE PAKETİ

Dosyalar:
- index.html: Site arayüzü
- styles.css: Tasarım
- app.js: Lig yönetimi ve maç simülasyon motoru
- players.json: Yüklediğin 300 oyuncunun kaynak veritabanı (değiştirilmeden korunur)
- players.js: Site motoruyla uyumluluk katmanı; oyuncu isimleri, kulüpleri, mevkileri ve puanları players.json dosyasından alınır

Kurulum:
1. ZIP dosyasını çıkar.
2. Bu dosyaların tamamını GitHub futbol-arena deposunun ana klasörüne yükle; mevcut dosyaların üzerine yaz.
3. Commit changes ile kaydet ve GitHub Pages dağıtımının tamamlanmasını bekle.
4. Siteyi yenile. index.html dosyasındaki önbellek sürümü güncellenmiştir.

Önemli:
- Kaynak listede 300 futbolcu vardır.
- attack, defense ve overall puanları kaynak players.json ile birebir korunmuştur; puanlar yeniden hesaplanmamıştır.
- Eski maç/lig motoru ve tasarım korunmuştur.
- players.js, eski motorun beklediği alanlarla uyumluluk sağlamak için country alanını kulüp adıyla doldurur; kaynak players.json içeriği değiştirilmez.
- Tarayıcıda kayıtlı eski lig kadroları oyuncu kimlikleri değişmişse yeniden kurulmalıdır.
