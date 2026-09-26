# Booking Tiket Wisata Walini

Starter project aplikasi **Booking Tiket Wisata Walini** berbasis Laravel.

## Fitur awal

- Beranda wisata Walini
- Daftar destinasi
- Detail destinasi
- Form booking tiket
- Kode booking otomatis
- Perhitungan total harga
- Halaman tiket/struk
- Database MySQL
- Struktur siap dikembangkan untuk dashboard admin

## Teknologi

- Laravel 12
- PHP 8.2+
- MySQL
- Blade
- Vite

## Instalasi

1. Clone/download repository.
2. Buka folder project di VS Code.
3. Install dependency:

```bash
composer install
```

4. Salin `.env.example` menjadi `.env`.
5. Buat database MySQL dengan nama `booking_walini`.
6. Jalankan:

```bash
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

7. Buka `http://127.0.0.1:8000`.

## Catatan GitHub

Folder `vendor` dan file `.env` sengaja tidak dimasukkan ke repository. Setelah project di-download, jalankan `composer install`.
