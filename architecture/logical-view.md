# Logical View

## Deskripsi

Logical View menjelaskan struktur logika dari Sistem Toko Online beserta hubungan antar komponen utama.

## Aktor

### Pelanggan

Dapat melakukan:
- Registrasi
- Login
- Melihat produk
- Mencari produk
- Menambah ke keranjang
- Checkout
- Melakukan pembayaran
- Melihat status pesanan

### Admin

Dapat melakukan:
- Login
- Mengelola produk
- Mengelola kategori
- Mengelola pesanan
- Mengelola pengguna
- Mengelola pembayaran
- Melihat laporan

## Modul Sistem

### Modul Pengguna

Mengelola data akun pelanggan dan admin.

### Modul Produk

Mengelola data produk yang dijual.

### Modul Kategori

Mengelola kategori produk.

### Modul Keranjang

Mengelola daftar belanja pelanggan.

### Modul Pesanan

Mengelola transaksi pemesanan.

### Modul Pembayaran

Mengelola proses pembayaran pelanggan.

### Modul Laporan

Menampilkan laporan penjualan.

## Hubungan Antar Modul

Pengguna
↓
Produk
↓
Keranjang
↓
Pesanan
↓
Pembayaran
↓
Laporan
