# Program Kasir sederhana

Program Kasir Python ini adalah aplikasi berbasis teks yang memungkinkan admin untuk mengelola produk, serta memungkinkan pelanggan untuk melakukan pembelian dengan diskon dan pembayaran yang terproses dengan baik. Program ini sederhana, dan ditulis menggunakan Python 3.

## Fitur Utama

- **Input Produk oleh Admin**: Admin dapat menambahkan produk ke dalam daftar produk yang tersedia dengan memasukkan kode produk, nama produk, harga, dan jumlah stok produk. Program memastikan bahwa kode produk memiliki format yang benar (misalnya `P001`, `P123`) dan unik.
- **Pembelian oleh Pelanggan**: Pelanggan dapat memilih produk yang tersedia untuk dibeli dengan memasukkan kode produk dan jumlah yang ingin dibeli. Program akan menghitung total harga dan memungkinkan penerapan diskon jika pelanggan memiliki kode diskon.
- **Validasi Input**: Program memvalidasi input dari pengguna untuk memastikan semua informasi yang dimasukkan sesuai dengan format yang diinginkan dan tidak ada kesalahan input (misalnya harga negatif, stok negatif, kode produk tidak valid).
- **Pengelolaan Stok**: Setelah pembelian dilakukan, stok produk akan berkurang sesuai dengan jumlah yang dibeli oleh pelanggan.
- **Penghitungan Diskon**: Admin dapat mengatur diskon untuk total transaksi, yang akan diterapkan secara otomatis saat pelanggan melakukan pembayaran.
  
## Cara Menggunakan

### 1. Persiapan
Pastikan Anda sudah memiliki Python 3 terinstal di sistem Anda. Anda dapat mengunduhnya di [sini](https://www.python.org/downloads/).

### 2. Menjalankan Program
Untuk menjalankan program, ikuti langkah-langkah berikut:
1. Simpan file ini dengan ekstensi `.py` (misalnya `kasir.py`).
2. Buka terminal atau command prompt, dan jalankan perintah berikut:
   ```bash
   python kasir.py
