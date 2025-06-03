# Baby-Step To-Do List: Inisialisasi Backend dan Koneksi Database

Ini adalah langkah implementasi pertama yang sangat spesifik untuk proyek DogFood App. Tujuannya adalah menyiapkan fondasi backend agar pengembangan API selanjutnya dapat dilakukan.

## Sub-Tugas 1: Inisialisasi Proyek Node.js dan Express
*   **Deskripsi Tugas**: Buat direktori baru untuk backend, inisialisasi proyek Node.js, dan instal Express. Tujuannya adalah memiliki server web dasar yang dapat merespons permintaan HTTP.
*   **File yang Akan Dibuat/Dimodifikasi**:
    *   `backend/` (direktori baru)
    *   `backend/package.json` (dibuat oleh `npm init`)
    *   `backend/server.js` (file utama server Express)
*   **Kriteria Penerimaan/Cara Tes**:
    1.  Buat file `backend/server.js` dengan kode Express dasar yang mendengarkan di port 3000 dan merespons "Hello World" pada rute `/`.
    2.  Jalankan server dengan `node backend/server.js`.
    3.  Buka browser atau gunakan `curl` untuk mengakses `http://localhost:3000/`. Output yang diharapkan adalah "Hello World".

## Sub-Tugas 2: Konfigurasi Koneksi PostgreSQL
*   **Deskripsi Tugas**: Instal driver PostgreSQL untuk Node.js (misalnya `pg`), dan buat modul konfigurasi database untuk mengelola koneksi. Tujuannya adalah memastikan aplikasi backend dapat terhubung ke database PostgreSQL.
*   **File yang Akan Dibuat/Dimodifikasi**:
    *   `backend/package.json` (akan ditambahkan dependensi `pg`)
    *   `backend/config/db.js` (file konfigurasi koneksi database)
*   **Kriteria Penerimaan/Cara Tes**:
    1.  Pastikan PostgreSQL server sudah berjalan di lingkungan pengembangan lokal.
    2.  Buat file `backend/config/db.js` yang menggunakan `pg` untuk membuat pool koneksi ke database.
    3.  Modifikasi `backend/server.js` untuk mengimpor `db.js` dan mencoba melakukan query sederhana (misalnya, `SELECT 1+1 AS solution;`) saat server dimulai.
    4.  Log hasil query ke konsol.
    5.  Jalankan server dengan `node backend/server.js`. Output di konsol harus menunjukkan koneksi berhasil dan hasil query (misalnya, `solution: 2`). Jika ada error koneksi, itu harus terlihat di konsol.
