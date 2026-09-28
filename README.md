# Aplikasi Absensi Karyawan DTY

## Deskripsi

Aplikasi Absensi Karyawan DTY merupakan sistem informasi berbasis web yang digunakan untuk membantu proses pencatatan dan pengelolaan kehadiran karyawan pada lingkungan manufaktur tekstil, khususnya pada bagian produksi Drawn Textured Yarn (DTY).

Aplikasi ini membantu admin dalam mengelola data karyawan, mencatat absensi masuk dan pulang, melihat riwayat absensi, serta membuat laporan absensi.

## Fitur

* Login Admin
* Dashboard
* Data Karyawan
* Tambah Data Karyawan
* Edit Data Karyawan
* Hapus Data Karyawan
* Pencatatan Jam Masuk
* Pencatatan Jam Pulang
* Status Hadir dan Terlambat
* Riwayat Absensi
* Filter Riwayat Absensi
* Export Laporan Absensi ke CSV
* Statistik Kehadiran

## Teknologi

* PHP
* MySQL
* HTML
* CSS
* JavaScript
* XAMPP
* phpMyAdmin

## Struktur Folder

```text
dty-absensi/
│
├── config/
│   └── database.php
│
├── index.php
├── login.php
├── logout.php
├── dashboard.php
├── karyawan.php
├── tambah_karyawan.php
├── edit_karyawan.php
├── hapus_karyawan.php
├── absensi.php
├── riwayat.php
├── export_absensi.php
├── database.sql
└── README.md
```

## Cara Menjalankan Aplikasi

### 1. Install XAMPP

Pastikan XAMPP sudah terpasang pada komputer.

### 2. Aktifkan Apache dan MySQL

Buka XAMPP Control Panel, kemudian jalankan:

* Apache
* MySQL

### 3. Simpan Project

Letakkan folder project pada:

```text
C:\xampp\htdocs\dty-absensi
```

### 4. Buat Database

Buka phpMyAdmin melalui:

```text
http://localhost/phpmyadmin
```

Buat database dengan nama:

```text
dty_absensi
```

Kemudian pilih database tersebut dan lakukan import file:

```text
database.sql
```

### 5. Periksa Konfigurasi Database

Buka file:

```text
config/database.php
```

Konfigurasi default:

```text
Host     : localhost
Username : root
Password : kosong
Database : dty_absensi
```

### 6. Jalankan Aplikasi

Buka browser dan akses:

```text
http://localhost/dty-absensi/
```

## Alur Penggunaan

1. Admin melakukan login.
2. Admin masuk ke halaman Dashboard.
3. Admin dapat mengelola data karyawan.
4. Admin mencatat jam masuk karyawan.
5. Sistem menentukan status kehadiran berdasarkan waktu masuk.
6. Admin mencatat jam pulang karyawan.
7. Admin dapat melihat riwayat absensi.
8. Admin dapat melakukan filter dan export laporan absensi.

## Informasi Login

Akun administrator digunakan untuk mengakses sistem.

Username dan password tersedia pada data akun administrator di database hasil import.

## Catatan

Aplikasi ini dikembangkan sebagai project mata kuliah Project Manufaktur Tekstil dengan tema sistem absensi karyawan pada lingkungan manufaktur DTY.

Aplikasi berjalan pada server lokal menggunakan XAMPP.
