# Telkom University Company Profile - Praktikum

Project simulasi untuk praktikum pengembangan web menggunakan HTML, CSS,
PHP native, MySQL/MariaDB, dan Git/GitHub.

Project ini dibuat sebagai media pembelajaran integrasi website dinamis,
database, dan version control.

> Catatan: website ini merupakan simulasi untuk keperluan praktikum dan
> bukan merupakan situs resmi Telkom University.

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