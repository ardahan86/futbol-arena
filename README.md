# FUTBOL ARENA – Güncel site paketi

Bu paket mevcut Lig Merkezi arayüzünü, stillerini ve maç simülasyon motorunu korur; oyuncu verisini 300 oyunculuk güncel players.js dosyasına bağlar.

## GitHub'a yükleme
1. Depodaki mevcut dosyaların yedeğini al.
2. ZIP içindeki `FUTBOL_ARENA_arma_guncelleme/` klasörünün içindeki dört dosyayı (`index.html`, `styles.css`, `app.js`, `players.js`) deponun kök dizinine yükle. Klasörün kendisini değil, içindeki dosyaları yükle.
3. Commit changes yap ve GitHub Pages dağıtımının tamamlanmasını bekle.
4. Siteyi `Ctrl+Shift+R` ile yenile.

## Korunan davranış
- Maç simülasyon kodu değiştirilmedi.
- Kayıtlı lig verisi (`league`) localStorage'dan yüklenmeye devam eder.
- Eski yerel oyuncu önbelleği yeni 300 oyunculuk listeyi ezmesin diye artık yüklenmez.
- Eski kadro seçimleri eski oyuncu kimliklerine bağlıysa yeni havuzdan kadroları yeniden seçmek gerekebilir.
