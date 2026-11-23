# UD.AFFANDY — Aplikasi Kasir Android

Versi awal aplikasi web yang dapat dipasang sebagai aplikasi (PWA) di HP Android.

## Fitur
- Dashboard omzet dan transaksi hari ini
- Tambah, edit, hapus produk
- Barcode/SKU, kategori, harga modal, harga jual, stok minimum
- Kasir, keranjang, pembayaran, kembalian, pengurangan stok otomatis
- Struk transaksi yang dapat dicetak
- Riwayat transaksi, rekap omzet dan estimasi laba
- Ekspor laporan CSV
- Backup dan pemulihan data JSON
- Pemindai barcode melalui kamera pada browser Android yang mendukung BarcodeDetector

## Cara mencoba di HP
1. Ekstrak ZIP ini.
2. Untuk pemasangan PWA, unggah isi folder ke GitHub Pages atau hosting HTTPS.
3. Buka alamat HTTPS tersebut menggunakan Chrome Android.
4. Pilih menu Chrome (⋮) > **Tambahkan ke layar utama** / **Install app**.
5. Berikan izin kamera saat menggunakan scanner.

## Catatan penting
- Pemindai kamera memerlukan HTTPS dan izin kamera. Jika browser tidak mendukung BarcodeDetector, masukkan kode barcode secara manual.
- Data versi ini tersimpan lokal di browser/perangkat. Backup secara berkala melalui menu Lainnya.
- Data tidak otomatis tersinkron antar HP dan belum memiliki akun pengguna/server cloud.
- Ini adalah aplikasi PWA, bukan APK native. Untuk menghasilkan APK native perlu proses build Android tambahan (misalnya Android Studio/Capacitor atau layanan build Android).
