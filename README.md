# heaterCalc

3 fazlı rezistif ısıtıcılar için güç ve toprak kaçak akımı hesaplayıcı (tek dosya, GitHub Pages uyumlu).

- Bağlantı: Üçgen (Δ), Yıldız nötrsüz (Y), Yıldız nötrlü (Yn)
- Gerilim: Faz-Faz veya Faz-Nötr girişi
- Direnç: eleman direnci veya klemensler arası ölçülen değer (otomatik çözülür); dengeli/dengesiz
- Opsiyonel: tek rezistans değeri + tolerans girilince her faz arasındaki paralel rezistans adedi tahmin edilir (adet ≈ R_tek ÷ eşdeğer R), rezistans başına akım/güç gösterilir
- Opsiyonel: L1/L2/L3 (ve yıldız noktası) – PE izolasyon direnci → kaçak akım (I∆, RCD 30 mA kontrolü), kaçak güç; TN/TT veya IT şebeke

Kullanım: `index.html` dosyasını tarayıcıda açın veya GitHub Pages (Settings → Pages → Branch: `main` / root) ile yayınlayın.
