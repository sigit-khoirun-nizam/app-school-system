# Sistem Informasi Sekolah

Sistem Informasi Sekolah adalah aplikasi berbasis web dan mobile yang dirancang untuk mengelola berbagai aspek administrasi dan akademik sekolah. Aplikasi ini menggunakan Laravel sebagai backend, React untuk web frontend, dan Flutter untuk aplikasi mobile.

## Fitur Utama

- Manajemen pengguna dengan berbagai peran (admin, kepala sekolah, guru, siswa, dan wali murid)
- Pengelolaan data siswa dan orang tua
- Manajemen kelas dan mata pelajaran
- Sistem absensi dan penilaian
- Penjadwalan kelas
- Manajemen perpustakaan
- Pengelolaan keuangan sekolah
- Kegiatan ekstrakurikuler
- Pengumuman dan notifikasi
- Sistem pengaduan
- Manajemen dokumen sekolah

## Teknologi yang Digunakan

- Backend: Laravel 11.x
- Web Frontend: React 18.x
- Mobile App: Flutter 3.x
- Database: MySQL 8.x
- Authentication: Laravel Sanctum
- Authorization: Spatie Permission

## Persyaratan Sistem

- PHP >= 8.1
- Composer
- Node.js >= 14.x
- npm atau yarn
- Flutter SDK
- MySQL

## Instalasi

1. Clone repositori ini:
2. Instal dependensi PHP:
3. Salin file .env.example menjadi .env dan sesuaikan konfigurasi database:
4. Generate app key:
5. Jalankan migrasi dan seeder:
6. Instal dependensi JavaScript untuk frontend web:
7. Untuk aplikasi Flutter, buka direktori `mobile_app` dan jalankan:

## Menjalankan Aplikasi

1. Jalankan server Laravel:
2. Dalam terminal terpisah, jalankan frontend React:
3. Untuk menjalankan aplikasi Flutter, gunakan:

## Struktur Database

Sistem ini menggunakan struktur database yang kompleks dengan banyak tabel yang saling berelasi. Beberapa tabel utama meliputi:

- users
- students
- parents
- teachers
- classes
- subjects
- attendance
- grades
- dan lainnya

Untuk detail lengkap struktur database, silakan lihat file migrasi di direktori `database/migrations`.

## API Endpoints

Dokumentasi lengkap API dapat diakses melalui rute `/api/documentation` setelah menjalankan server Laravel.

## Kontribusi

Kami sangat menghargai kontribusi dari komunitas. Jika Anda ingin berkontribusi, silakan buat pull request atau buka issue untuk diskusi fitur baru atau perbaikan bug.

## Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

## Kontak

Jika Anda memiliki pertanyaan atau masukan, silakan hubungi tim pengembang
