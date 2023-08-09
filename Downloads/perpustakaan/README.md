<h1 align="center">Sistem Perpustakaan</h1>

## Fitur 

- Autentikasi Admin, Petugas dan Peminjam
- CRUD Kategori
- CRUD Buku
- CRUD Penerbit
- CRUD Rak
- Melakukan peminjaman buku
- Menampilkan chart
- Mengimplementasikan livewire
- Menggunakan admin LTE
- Menggunakan fakerphp
- Dan lain-lain

## User

**Admin**

- email: admin@gmail.com
- Password: 123123123

**Petuags**

- email: petugas@gmail.com
- Password: 123123123

**Peminjam**

- email: peminjam@gmail.com
- Password: 123123123

## Install

**Download zip**

```bash
extract file zip
```

## Buka di kode editor


## Install composer

```bash
composer install
```

## Copy .Env

```bash
copy .env.example menjadi .env
```

## Buka Web Server


## Buat database di localhost 

```bash
nama database : sistempenpus
```

## Setting database di .env

```bash
DB_PORT=3306
DB_DATABASE=sistempenpus
DB_USERNAME=root
DB_PASSWORD=
```

## Generate key

```bash
php artisan key:generate
```

## Jalankan migrate dan seeder

```bash
php artisan migrate --seed
```

## Buat Storage Link

```bash
php artisan storage:link
```


## Jalankan Serve

```bash
php artisan serve
```
