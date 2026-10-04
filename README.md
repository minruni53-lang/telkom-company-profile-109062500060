# Telkom University Company Profile - Praktikum

Project simulasi untuk praktikum pengembangan web menggunakan HTML, CSS, PHP Native, MySQL/MariaDB, dan Git/GitHub.

Project ini dibuat sebagai media pembelajaran integrasi website dinamis, database, dan version control.

> **Catatan:** Website ini merupakan simulasi untuk keperluan praktikum dan bukan merupakan situs resmi Telkom University.

## Fitur Project

- Halaman Beranda
- Halaman Profil
- Halaman Program Studi dengan data dari database
- Halaman daftar berita
- Halaman detail berita
- Formulir kontak
- Penyimpanan pesan kontak ke database
- Form admin sederhana untuk menambahkan berita
- Version control menggunakan Git dan GitHub

## Teknologi

- HTML
- CSS
- PHP Native
- MySQL/MariaDB
- Git
- GitHub
- Laragon

## Struktur Project

```text
telkom-company-profile-109062500060/
├── admin/
│   ├── add_news.php
│   └── save_news.php
├── assets/
│   └── css/
│       └── style.css
├── config/
│   └── database.php
├── database/
│   └── telkom_profile.sql
├── includes/
│   ├── header.php
│   └── footer.php
├── index.php
├── profile.php
├── programs.php
├── news.php
├── news_detail.php
├── contact.php
├── contact_process.php
├── README.md
└── .gitignore

## Cara Menjalankan Project

### 1. Menjalankan Laragon
- Buka aplikasi Laragon.
- Jalankan **Apache** dan **MySQL** dengan menekan tombol **Start All**.
- Pastikan kedua service berjalan dengan normal.

### 2. Menempatkan Project
Letakkan folder project di:

`C:\laragon\www\telkom-company-profile-109062500060`

### 3. Menyiapkan Database
- Buka phpMyAdmin melalui Laragon.
- Buat database dengan nama `telkom_profile`.
- Import file `database/telkom_profile.sql`.

### 4. Membuka Project
Buka browser dan akses:

`http://localhost/telkom-company-profile-109062500060/`

### 5. Pengujian
Pastikan:
- Halaman beranda dapat dibuka.
- Data Program Studi tampil dari database.
- Daftar dan detail berita dapat dibuka.
- Form kontak dapat digunakan.
- Pesan dari form kontak tersimpan ke database.

## Praktikum Git

Project ini dibuat sebagai penerapan materi Git dan GitHub, meliputi:

- Repository lokal dan remote GitHub
- Commit dan push
- Branch dan merge
- Simulasi merge conflict
- Clone project ke folder kedua sebagai simulasi Laptop B
- Push dan pull
- Recovery menggunakan revert
- Pembuatan release dengan tag `v1.0.0`

### Riwayat Praktikum Git

Riwayat commit dapat dilihat menggunakan perintah:

```bash
git log --oneline --graph --decorate --all