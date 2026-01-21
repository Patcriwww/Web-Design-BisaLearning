## BisaLearning -- Web-Based E-Learning System

Project BisaLearning merupakan implementasi sistem pembelajaran daring
(e-learning) berbasis web yang dirancang untuk memfasilitasi proses
belajar mengajar secara digital. Sistem ini menyediakan manajemen akun
(admin, guru, dan siswa), pengelolaan materi pembelajaran, serta
autentikasi pengguna dalam satu platform terintegrasi.\
Project ini dibuat sebagai bagian dari tugas mata kuliah yang berkaitan
dengan **Web Programming / Sistem Informasi / Rekayasa Perangkat
Lunak**.

------------------------------------------------------------------------

## Latar Belakang

**Sistem pembelajaran konvensional memiliki beberapa keterbatasan,
antara lain:** - Akses materi yang terbatas oleh ruang dan waktu. -
Distribusi materi yang tidak terpusat. - Sulitnya monitoring aktivitas
belajar siswa.

**Dengan menggunakan sistem e-learning berbasis web:** - Materi dapat
diakses kapan saja dan di mana saja. - Data pengguna tersimpan terpusat
dalam database. - Proses belajar menjadi lebih fleksibel dan
terstruktur.

------------------------------------------------------------------------

## Fitur Utama

**1. Sistem Autentikasi** - Login untuk Admin, Guru, dan Siswa. -
Manajemen hak akses berbasis role.

**2. Manajemen Materi** - Guru dapat mengunggah, mengedit, dan menghapus
materi. - Siswa dapat mengakses dan mengunduh materi pembelajaran.

**3. Manajemen Pengguna** - Admin dapat menambah, mengedit, dan
menghapus akun. - Pengelolaan data siswa dan guru.

**4. Sistem Basis Data Terintegrasi** - Penyimpanan data user, materi,
dan aktivitas menggunakan MySQL.

------------------------------------------------------------------------

## Arsitektur Sistem

User\
--\> Login & Authentication\
--\> Role Check (Admin / Guru / Siswa)\
--\> Akses Fitur\
--\> Database MySQL\
--\> Tampilan Web (HTML, CSS, PHP)

------------------------------------------------------------------------

## Teknologi yang Digunakan

-   PHP\
-   MySQL\
-   HTML5\
-   CSS3 / SCSS\
-   JavaScript\
-   Arsitektur MVC Sederhana

------------------------------------------------------------------------

## Struktur Folder

Web-Design-BisaLearning/ │\
├── login.php\
├── controller/\
│ ├── auth.php\
│ ├── upload_materi.php\
│ ├── edit_materi.php\
│ └── hapus.php\
├── config/\
│ ├── bisalearn.sql\
│ └── mysql_db.php\
├── public/\
│ └── style.scss\
├── templates / views\
├── README.md

------------------------------------------------------------------------

## Cara Menjalankan

**1. Clone Repository**\
`git clone https://github.com/username/Web-Design-BisaLearning.git`\
`cd Web-Design-BisaLearning`

**2. Import Database**\
Import file `bisalearn.sql` ke MySQL melalui phpMyAdmin atau CLI.

**3. Konfigurasi Koneksi Database**\
Atur file `config/mysql_db.php` sesuai host, user, dan password MySQL.

**4. Jalankan Aplikasi**\
Buka melalui browser:\
`http://localhost/Web-Design-BisaLearning`

------------------------------------------------------------------------

## Contoh Alur Kerja

1.  User membuka halaman login.\
2.  Sistem memverifikasi akun ke database.\
3.  User masuk sesuai role (Admin / Guru / Siswa).\
4.  Guru mengunggah materi.\
5.  Materi tersimpan di database dan dapat diakses siswa.\
6.  Admin mengelola akun dan data sistem.

------------------------------------------------------------------------

## Tujuan Pembelajaran

Project ini bertujuan untuk memahami: - Konsep dasar Web Application\
- Implementasi CRUD\
- Autentikasi dan Autorisasi\
- Integrasi PHP dengan MySQL\
- Penerapan MVC pada aplikasi web\
- Pengembangan sistem e-learning

------------------------------------------------------------------------

## Author

**Fachri Reyhan**\
Mahasiswa -- Teknologi Informasi / Informatika\
Tahun: 2026

------------------------------------------------------------------------

## Lisensi

Project ini dibuat untuk keperluan akademik dan pembelajaran.\
Bebas digunakan sebagai referensi dengan mencantumkan sumber.
