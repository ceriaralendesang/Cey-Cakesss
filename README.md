# Lavélle Cakes — Website UMKM Toko Cake dan Kue

Project website statis untuk tugas akhir menggunakan HTML5, CSS3, JavaScript, Bootstrap 5, dan localStorage.

## Halaman
1. `index.html` — Beranda, produk unggulan, daftar harga, tombol pesan.
2. `tentang.html` — Profil dan nilai usaha.
3. `menu.html` — Katalog produk dengan filter kategori.
4. `galeri.html` — Galeri foto.
5. `kontak.html` — Informasi kontak dan formulir demo.

## Cara menjalankan
- Ekstrak ZIP.
- Buka folder `lavelle-cakes`.
- Jalankan `index.html` melalui browser. Disarankan memakai ekstensi Live Server di Visual Studio Code.
- Bootstrap, Bootstrap Icons, Google Fonts, dan foto Unsplash memerlukan koneksi internet.

## Fitur
- Responsive layout Bootstrap 5.
- Keranjang belanja disimpan pada `localStorage`.
- Tambah, kurangi, dan hapus produk dari keranjang.
- Perhitungan total otomatis.
- Filter kategori menu.
- Formulir kontak dengan validasi browser.

## Hal yang harus disesuaikan
- Nama brand dan identitas UMKM jika berbeda.
- Harga produk: semua harga pada project ini adalah contoh/dummy.
- Alamat, nomor WhatsApp, jam operasional, dan akun media sosial.
- Foto produk: gambar saat ini menggunakan URL Unsplash sebagai placeholder.
- Testimoni: teks testimoni hanya contoh tampilan, bukan ulasan pelanggan nyata.

## Batasan
Project ini tidak memiliki backend, database, pembayaran online, atau pengiriman pesanan otomatis. Tombol checkout menampilkan ringkasan pesanan di browser. Formulir kontak hanya memberikan konfirmasi lokal.

## Upload ke GitHub
1. Buat repository baru di GitHub.
2. Upload semua file dan folder project.
3. Buka **Settings → Pages**.
4. Pada Build and deployment, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/root`, lalu Save.
6. Tunggu proses deployment selesai. GitHub akan menampilkan URL website.

## Struktur folder
```text
lavelle-cakes/
├── index.html
├── tentang.html
├── menu.html
├── galeri.html
├── kontak.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── images/
```
