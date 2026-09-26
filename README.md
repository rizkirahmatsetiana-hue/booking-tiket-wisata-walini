# Booking Tiket Wisata Walini

Starter project untuk aplikasi booking tiket wisata Walini berbasis Laravel.

## Fitur awal
- Beranda wisata Walini
- Daftar destinasi
- Form booking tiket
- Struktur database booking
- Halaman admin sebagai rancangan awal

## Cara menggunakan
1. Buat project Laravel baru:
   ```bash
   composer create-project laravel/laravel booking-tiket-walini
   ```
2. Salin file dari folder ini ke project Laravel.
3. Atur database pada file `.env`.
4. Jalankan:
   ```bash
   php artisan migrate
   php artisan serve
   ```

Catatan: folder `vendor` dan dependensi Laravel tidak disertakan agar ukuran file tetap kecil. Jalankan Composer pada langkah pertama.
