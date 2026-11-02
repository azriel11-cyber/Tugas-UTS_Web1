# VokaBook — Toko Buku Online

## Cara menjalankan
1. Ekstrak ZIP.
2. Buka folder `vokabook`.
3. Klik dua kali `index.html` untuk membuka di browser.
4. Login dengan akun dari `js/data.js`:
   - `rina@gmail.com` / `rina123`
   - `agus@gmail.com` / `agus123`
   - `siti@gmail.com` / `siti123`

## Struktur folder
- `index.html` dan `login.html`: login, lupa password, daftar (modal).
- `dashboard.html`: greeting berdasarkan jam lokal dan menu.
- `stok.html`: katalog buku bergambar dari `dataKatalogBuku`, tambah data lewat DOM.
- `checkout.html`: formulir pemesan, tambah/hapus baris buku, pembayaran.
- `tracking.html`: pencarian DO dan detail status/perjalanan.
- `laporan.html`: ringkasan pesanan dan perubahan status untuk pesanan baru.
- `transaksi.html`: riwayat transaksi.
- `css/style.css`: desain responsif sederhana.
- `js/data.js`: file data.js yang diberikan, dipakai tanpa perubahan.
- `js/app.js`: logika JavaScript.
- `img/`: gambar sampul buku.

Nomor DO demo: `20230012` dan `20230013`. Data tambahan disimpan pada localStorage, tanpa server/database.
