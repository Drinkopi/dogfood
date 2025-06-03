# Dokumen Desain Produk (PDD) - DogFood App

## Visi Produk
DogFood App adalah aplikasi mobile yang membantu pemilik anjing memilih makanan terbaik untuk hewan peliharaan mereka melalui rekomendasi yang dipersonalisasi, fitur sampel, komunitas pengguna, integrasi wearable, dan program loyalitas berbasis gamifikasi. Aplikasi ini bertujuan meningkatkan kesehatan anjing dan kepuasan pemilik dengan pengalaman yang intuitif dan menarik.

## Tujuan
- Memberikan rekomendasi makanan yang sesuai dengan kebutuhan unik setiap anjing.
- Mengurangi risiko salah beli melalui opsi sampel.
- Membangun komunitas pemilik anjing untuk berbagi pengalaman.
- Memanfaatkan data wearable untuk rekomendasi yang lebih akurat.
- Meningkatkan retensi pengguna melalui program loyalitas yang menyenangkan.

## Pengguna Sasaran
- Pemilik anjing dari berbagai usia yang peduli dengan kesehatan dan nutrisi hewan peliharaan mereka.
- Pengguna teknologi yang nyaman dengan aplikasi mobile dan wearable.
- Komunitas pecinta anjing yang ingin berbagi tips dan pengalaman.

## Fitur Utama
### 1. Rekomendasi Makanan yang Dipersonalisasi
- **Fungsi**: Pengguna membuat profil anjing dengan detail seperti ras, usia, berat badan, tingkat aktivitas, alergi, kondisi kesehatan, dan preferensi rasa.
- **Alur Pengguna**:
  1. Pengguna mengisi formulir profil anjing.
  2. Algoritma merekomendasikan makanan berdasarkan data profil, menghindari alergen, dan menyesuaikan porsi.
  3. Pengguna dapat memfilter rekomendasi (misalnya, "makanan bebas gluten").
  4. Setiap rekomendasi disertai penjelasan (contoh: "Kaya omega-3 untuk kulit sehat").
- **Tampilan**: Daftar rekomendasi dengan filter, detail nutrisi, dan tombol untuk memesan.

### 2. Fitur "Coba Dulu" atau Sampel
- **Fungsi**: Pengguna dapat membeli sampel kecil atau paket trial sebelum membeli ukuran penuh.
- **Alur Pengguna**:
  1. Pengguna memilih sampel dari rekomendasi.
  2. Opsi untuk memesan bundel sampel atau langganan bulanan.
  3. Checkout dan pelacakan pengiriman.
- **Tampilan**: Halaman produk dengan opsi ukuran sampel dan langganan.

### 3. Komunitas dan Forum Diskusi
- **Fungsi**: Forum untuk diskusi, ulasan produk, dan tanya jawab dengan ahli.
- **Alur Pengguna**:
  1. Pengguna bergabung dengan forum atau grup berdasarkan ras anjing.
  2. Membaca/menulis ulasan, memposting pertanyaan, atau berpartisipasi dalam diskusi.
  3. Notifikasi untuk jawaban dari ahli.
- **Tampilan**: Forum dengan topik terstruktur, ulasan produk, dan grup ras.

### 4. Integrasi dengan Wearable (Smart Collar)
- **Fungsi**: Sinkronisasi data aktivitas dan kesehatan dari smart collar.
- **Alur Pengguna**:
  1. Pengguna menghubungkan smart collar via Bluetooth.
  2. Data seperti aktivitas dan detak jantung dianalisis untuk rekomendasi makanan.
  3. Peringatan kesehatan jika ada anomali.
- **Tampilan**: Dashboard kesehatan dengan grafik aktivitas dan notifikasi.

### 5. Program Loyalitas Berbasis Gamifikasi
- **Fungsi**: Sistem poin, misi, badge, dan referral untuk meningkatkan keterlibatan.
- **Alur Pengguna**:
  1. Pengguna mendapatkan poin dari pembelian atau misi (contoh: "Unggah foto anjing").
  2. Poin ditukar dengan diskon atau hadiah.
  3. Lihat progres level dan badge di profil.
- **Tampilan**: Halaman loyalitas dengan poin, misi, dan leaderboard.

## Alur Pengguna Utama
1. **Onboarding**: Pengguna mendaftar, membuat profil anjing, dan menghubungkan wearable (opsional).
2. **Eksplorasi**: Lihat rekomendasi makanan, jelajahi forum, atau cek misi loyalitas.
3. **Aksi**: Pesan sampel, tulis ulasan, atau tukar poin.
4. **Pemantauan**: Lihat data kesehatan anjing dan peringatan dari wearable.

## Desain Antarmuka
- **Prinsip**: Intuitif, ramah pengguna, dan visual menarik dengan tema anjing.
- **Warna**: Palet hangat (cokelat, krem) dengan aksen hijau atau biru.
- **Navigasi**: Bottom navigation bar untuk Home, Rekomendasi, Forum, Loyalitas, dan Profil.

## Prioritas Pengembangan
- **Fitur Inti**: Rekomendasi makanan yang dipersonalisasi.
- **Fitur Pendukung**: Sampel, forum, wearable, dan loyalitas (tahap bertahap).