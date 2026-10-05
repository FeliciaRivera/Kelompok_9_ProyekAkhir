# Warung Pojok Mba Sofy - Website Profil & Katalog UMKM

Proyek akhir perancangan website profil dan katalog UMKM, dikerjakan sebagai tugas kelompok mata kuliah Pemrograman Antarmuka Pengguna.

## Informasi Tugas

- Mata Kuliah: Pemrograman Antarmuka Pengguna
- Kelompok: 9 (SI A)
- Studi Kasus: Opsi A - Profil & Katalog UMKM
- Link PPT dan Laporan: https://drive.google.com/drive/folders/1u7DrrEh4pd2Fb-DhYHQd8wr3Fknqyzms?usp=sharing
- Link Repo Github : https://github.com/FeliciaRivera/Kelompok_9_ProyekAkhir

## Anggota Kelompok

| Nama | NIM |
|---|---|
| Deio Castello Sujati | 825250002 |
| Felicia Rivera | 825250003 |
| Muhammad Ubait Dhaifullah | 825250012 |

## Tentang Project Ini

Website ini dibuat untuk Warung Pojok Mba Sofy, sebuah usaha kuliner rumahan yang menyajikan aneka masakan rumahan seperti nasi goreng, kwetiau, mie goreng, nasi katsu, roti bakar, dan aneka minuman. Website menampilkan profil usaha, katalog menu beserta daftar harga dalam bentuk tabel, kategori produk, jam operasional, peta lokasi, galeri produk, dan form pemesanan.

## Fitur Utama

- Struktur halaman semantik: `header`, `nav`, `main`, `article`, `aside`, `footer`.
- Tiga halaman HTML yang saling terhubung: Beranda, Menu, dan Tentang.
- Layout multi-kolom menggunakan CSS Grid `grid-template-columns: 2fr 1fr`, memisahkan konten utama artikel/profil dengan sidebar kategori produk, jam operasional, peta lokasi, dan kontak.
- Tabel Katalog Menu & Daftar Harga dengan struktur `thead`/`tbody`, penggunaan `colspan` untuk judul tabel dan `rowspan` untuk pengelompokan kategori menu.
- Tabel dibungkus dengan `.table-wrapper` agar dapat di-scroll horizontal pada layar kecil.
- Styling tabel meliputi `border-collapse`, `padding`, `text-align`, zebra-striping `nth-child(even)`, dan efek hover pada baris.
- Kategori produk ditampilkan dalam grid dua kolom lengkap dengan foto.
- Galeri produk menggunakan grid tiga kolom dengan efek hover.
- Menu navigasi dengan dropdown Makanan, Minuman, Roti Bakar yang berfungsi menggunakan HTML + CSS murni tanpa JavaScript.
- Hamburger menu responsif CSS-only untuk tampilan mobile.
- Peta lokasi menggunakan embed Google Maps melalui `iframe`.
- Video profil warung ditampilkan menggunakan tag `<video>`.
- Form pemesanan lengkap dengan kontrol: input teks, email, telepon, number, radio, dropdown `select`, area teks `textarea`, dan tombol submit.
- Desain responsif: layout dua kolom berubah menjadi satu kolom pada layar dengan lebar di bawah 860px.

## Prinsip Desain yang Diterapkan

1. **Konsistensi Visual** — Menggunakan variabel CSS untuk palet warna dan tipografi yang sama di seluruh halaman agar website terasa satu kesatuan.
2. **Hierarki Informasi** — Membedakan ukuran, warna, dan ketebalan pada judul, subjudul, dan isi sehingga pengunjung mudah memindai halaman. Judul utama menggunakan border solid, subjudul menggunakan border putus-putus.
3. **Jarak & Tata Letak** — Memberikan whitespace yang cukup antar elemen melalui padding, margin, dan gap grid supaya halaman tidak terasa sesak.
4. **Navigasi Jelas** — Menu diletakkan di posisi yang sama pada setiap halaman, dilengkapi indikator halaman aktif dan dropdown yang berfungsi tanpa JavaScript.
5. **Optimasi Gambar** — Menggunakan `object-fit: cover`, `max-width: 100%`, dan atribut `loading="lazy"` pada peta agar halaman cepat dimuat dan gambar tidak gepeng.
6. **Aksesibilitas Dasar** — Memastikan kontras warna cukup, menyertakan atribut `alt` pada gambar, `label` pada form, `aria-label` pada tombol hamburger, dan `:focus` state pada input.

## Teknologi yang Digunakan

- HTML5
- CSS3 (CSS Grid, Flexbox, Media Queries, CSS Variables, tanpa framework tambahan)

## Pembagian Tugas

| Anggota | Bagian yang Dikerjakan |
|---|---|
| Deio Castello Sujati | Fondasi CSS variabel warna, reset, header, navigasi, dropdown, layout, hero, artikel, sidebar, kategori produk, peta, footer, media queries dan halaman Beranda `index.html`. |
| Felicia Rivera | Halaman Menu `menu.html` yang mencakup tabel Katalog Menu & Daftar Harga dengan `colspan`/`rowspan`, galeri produk, form pemesanan lengkap, panel info pendukung, serta styling CSS untuk tabel, galeri, dan form. |
| Muhammad Ubait Dhaifullah | Halaman Tentang Kami `about.html` yang mencakup cerita usaha, visi, misi, tabel nilai perusahaan, sidebar info singkat, dan peta lokasi. Bertanggung jawab atas dokumentasi `README.md` dan Quality Control seluruh file. |