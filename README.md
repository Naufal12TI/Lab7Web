# Lab7Web - Pemrograman Web

Repository ini berisi hasil praktikum **Pemrograman Web** menggunakan **CodeIgniter 4**.

---

## Praktikum 1: Pengenalan PHP Framework (CodeIgniter 4)

**Yang dipelajari:**
- Instalasi CodeIgniter 4
- Konfigurasi `.env` dan baseURL
- Konsep MVC (Model-View-Controller)
- Routing
- Template Layout dengan `header.php` dan `footer.php`
- Penggunaan CLI Spark (`php spark routes`)

**Hasil yang dicapai:**
- Berhasil membuat layout sederhana
- Membuat Controller `Page`
- Routing untuk halaman About, Contact, FAQs, TOS
- Semua halaman menggunakan layout yang sama

**Screenshot Praktikum 1:**
- XAMPP Control Panel
- Welcome Page CodeIgniter
- File Routes.php
- Halaman About, Contact, FAQs, TOS

---

## Praktikum 2: Framework Lanjutan (CRUD Artikel)

**Yang dipelajari:**
- Konfigurasi Database
- Membuat Model
- Operasi CRUD lengkap
- Upload File Gambar
- Pencarian dan Pagination

**Fitur yang sudah diimplementasikan:**
- Database `lab_ci4` + tabel `artikel`
- Model `ArtikelModel`
- Controller `Artikel` (CRUD lengkap)
- Upload gambar ke folder `public/gambar`
- Halaman Admin
- Fitur pencarian
- Pagination (5 data per halaman)

**Screenshot Praktikum 2:**
- Database dan struktur tabel `artikel`
- Halaman Admin Daftar Artikel
- Form Tambah Artikel
- Berhasil menambahkan artikel (dengan gambar)
- Form Edit Artikel
- Hasil pencarian
- Pagination

---

## Cara Menjalankan Project

1. Clone repository ini
2. Jalankan XAMPP (Apache + MySQL)
3. Buat database `lab_ci4`
4. Sesuaikan file `.env` (database name = `lab_ci4`)
5. Akses di browser:
   - Halaman depan: `http://localhost/lab11_php_ci/public/`
   - Halaman Admin: `http://localhost/lab11_php_ci/public/admin/artikel`

## Author
- Nama: Naufal Khoirul Ibrahim
- NIM: 312410108
- Kelas: TI24C2
- Universitas Pelita Bangsa

---

**Dokumentasi ini dibuat secara bertahap sesuai urutan praktikum.**
