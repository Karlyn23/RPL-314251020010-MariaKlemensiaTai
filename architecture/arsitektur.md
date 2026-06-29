# Arsitektur Sistem

## Deskripsi

Sistem Toko Online menggunakan arsitektur tiga lapisan (Three-Tier Architecture) yang terdiri dari Presentation Layer, Business Logic Layer, dan Database Layer.

## Presentation Layer

Lapisan ini merupakan antarmuka yang digunakan oleh pengguna untuk berinteraksi dengan sistem melalui web browser.

Fitur yang tersedia:
- Registrasi
- Login
- Melihat Produk
- Mencari Produk
- Keranjang Belanja
- Checkout
- Riwayat Pesanan

## Business Logic Layer

Lapisan ini menangani seluruh proses bisnis sistem.

Proses yang dilakukan:
- Autentikasi pengguna
- Manajemen produk
- Manajemen kategori
- Manajemen pesanan
- Manajemen pembayaran
- Validasi data
- Pembuatan laporan

## Database Layer

Database digunakan untuk menyimpan seluruh data sistem.

Data yang disimpan:
- Data pengguna
- Data produk
- Data kategori
- Data pesanan
- Data pembayaran

## Alur Sistem

Pengguna → Website → Business Logic → Database → Business Logic → Website → Pengguna

## Keuntungan Arsitektur

- Mudah dikembangkan
- Mudah dipelihara
- Keamanan data lebih baik
- Performa sistem stabil
- Mendukung pengembangan fitur baru

## Diagram Arsitektur

![Diagram Arsitektur](gambar-sistem-toko-online.jpeg)
