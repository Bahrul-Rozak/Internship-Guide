# Standar Penulisan Kode - Magang Fullstack Developer

Selamat datang di proyek magang Fullstack Developer!  
Berikut adalah standar penulisan kode yang diharapkan untuk menjaga kualitas dan konsistensi proyek.

---

## Struktur Project

Gunakan struktur folder default Laravel tanpa mengubahnya:  
- `app/` untuk kode backend  
- `resources/` untuk view (Blade templates)  
- `public/` untuk asset publik seperti CSS, JS, gambar  
- `database/` untuk migration dan seeding  
- `routes/` untuk routing aplikasi

---

## Penulisan Kode PHP (Laravel)

- Ikuti standar **PSR-12** untuk penulisan kode PHP  
- Gunakan **CamelCase** untuk penamaan Class dan Controller  
- Gunakan **camelCase** untuk penamaan variabel dan fungsi  
- Gunakan Eloquent ORM untuk query database  
- Lakukan validasi input di Controller atau menggunakan Form Request  
- Untuk routing, **lebih baik gunakan route resource** (`Route::resource`) untuk CRUD standar  
- Jika butuh route custom, boleh ditambahkan dengan penamaan yang jelas dan konsisten  
- Hindari duplikasi kode, manfaatkan fungsi atau helper jika perlu  
- Berikan komentar singkat pada fungsi yang kompleks atau penting  

---

## Blade Template & HTML

- Gunakan indentasi 2 spasi  
- Gunakan Blade directive seperti `@if`, `@foreach` untuk kontrol alur  
- Jangan gunakan inline CSS/JS di Blade, pisahkan ke file terpisah di `public/` atau `resources/`  
- Gunakan semantic HTML (`<header>`, `<nav>`, `<main>`, `<footer>`, dll)  

---

## CSS & JavaScript

- Gunakan penamaan class dan id yang deskriptif dan konsisten  
- Gunakan ES6+ untuk penulisan JavaScript  
- Pisahkan kode JavaScript ke file terpisah, hindari menulis langsung di Blade  
- Minimalkan penggunaan variabel global di JS  
- Berikan komentar pada bagian kode yang kompleks  

---

## Penggunaan Git

- Commit dengan pesan yang jelas dan singkat, misalnya:  
  - `feat: tambah fitur login`  
  - `fix: perbaiki bug validasi`  
- Gunakan branch terpisah untuk setiap fitur atau perbaikan  
- Jangan langsung commit ke branch `main` atau `master`  
- Lakukan pull request dan review sebelum merge ke branch utama  

---

Terima kasih sudah mengikuti standar ini, supaya kita bisa kerja sama dengan nyaman dan hasil kode terjaga kualitasnya! 🚀

---

**Happy Coding!**
