# DogFood App

## Deskripsi
DogFood App adalah aplikasi mobile untuk membantu pemilik anjing memilih makanan terbaik melalui rekomendasi yang dipersonalisasi berdasarkan profil anjing. MVP berfokus pada pembuatan profil anjing, rekomendasi makanan, dan opsi pembelian sampel. Aplikasi ini dibangun dengan React Native untuk frontend dan Node.js + PostgreSQL untuk backend.

## Fitur MVP
- Buat profil anjing (ras, usia, berat badan, alergi, dll.).
- Rekomendasi makanan dengan filter dan penjelasan.
- Pesan sampel makanan melalui checkout sederhana.
- Antarmuka ramah pengguna untuk iOS dan Android.

## Prasyarat
- Node.js v16 atau lebih tinggi.
- PostgreSQL v13 atau lebih tinggi.
- React Native CLI dan lingkungan pengembangan (Xcode untuk iOS, Android Studio untuk Android).
- Akun Firebase untuk autentikasi.
- Akun Stripe untuk pembayaran.

## Instalasi
1. **Clone repositori**:
   ```bash
   git clone https://github.com/username/dogfood-app.git
   cd dogfood-app
   ```
2. **Instal dependensi frontend**:
   ```bash
   cd client
   npm install
   ```
3. **Instal dependensi backend**:
   ```bash
   cd ../server
   npm install
   ```
4. **Konfigurasi lingkungan**:
   - Buat file `.env` di folder `server` dengan:
     ```
     DATABASE_URL=postgresql://user:password@localhost:5432/dogfood
     FIREBASE_CONFIG={your_firebase_config}
     STRIPE_SECRET_KEY={your_stripe_key}
     ```
   - Konfigurasi Firebase dan Stripe di dashboard masing-masing.
5. **Jalankan database**:
   - Siapkan PostgreSQL dan buat database `dogfood`.
   - Jalankan migrasi:
     ```bash
     npm run migrate
     ```
6. **Jalankan aplikasi**:
   - Backend: `cd server && npm start`
   - Frontend: `cd client && npm run ios` (atau `npm run android`)

## Struktur Proyek
- `/client`: Kode React Native untuk aplikasi mobile.
- `/server`: Kode Node.js + Express untuk backend API.
- `/docs`: Dokumen seperti PDD, tumpukan teknologi, dan rencana implementasi.

## Kontribusi
1. Fork repositori.
2. Buat branch fitur (`git checkout -b feature/nama-fitur`).
3. Commit perubahan (`git commit -m 'Menambahkan fitur X'`).
4. Push ke branch (`git push origin feature/nama-fitur`).
5. Buat Pull Request.

## Lisensi
© 2025 DogFood App. Semua hak dilindungi.

## Kontak
Untuk pertanyaan atau umpan balik, hubungi support@dogfoodapp.com atau buka issue di repositori ini.
