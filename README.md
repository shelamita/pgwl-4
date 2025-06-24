<<<<<<< HEAD
# **SAVANA RAYA**

<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

## **Tentang Proyek Ini**
SAVANA RAYA adalah proyek berbasis **Laravel** yang dikembangkan untuk kebutuhan pariwisata di Pulau Lombok.  
Framework Laravel dipilih karena kemudahannya dalam membangun aplikasi web dengan cepat dan efisien.

## **Fitur Utama**  
✅ Menggunakan Laravel sebagai backend.  
✅ Sistem manajemen data menggunakan database.  
✅ Routing yang fleksibel dan mudah dikonfigurasi.  
✅ Template Blade untuk tampilan dinamis.  

## **Dokumentasi Laravel**  
Untuk informasi lebih lanjut tentang Laravel, kunjungi [Laravel Docs](https://laravel.com/docs).  

## **Cara Menggunakan**  
### 1. Clone repository ini  
```sh
git clone https://github.com/shelamita/pgwebl.git
cd pgwebl
```

### 2. Install dependensi  
```sh
composer install
npm install
```

### 3. Konfigurasi file `.env`  
- Salin file `.env.example` menjadi `.env`  
  ```sh
  cp .env.example .env
  ```
- Atur konfigurasi database di file `.env`  
- Generate application key  
  ```sh
  php artisan key:generate
  ```

### 4. Jalankan migrasi database  
```sh
php artisan migrate
```

### 5. Jalankan aplikasi  
```sh
php artisan serve
```
Aplikasi akan berjalan di `http://127.0.0.1:8000`
