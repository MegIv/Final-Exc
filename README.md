Program Kasir Python
Program Kasir Python ini adalah aplikasi sederhana yang memungkinkan admin untuk mengelola produk yang tersedia untuk dijual, serta memungkinkan pelanggan untuk melakukan transaksi pembelian dengan berbagai fitur seperti diskon dan pembayaran. Program ini dirancang untuk membantu dalam simulasi penjualan barang menggunakan antarmuka berbasis teks.

Fitur Program:
Input Produk oleh Admin:

Admin dapat menambahkan produk ke dalam daftar produk yang tersedia dengan memasukkan kode produk, nama produk, harga, dan jumlah stok produk.
Program memastikan bahwa kode produk memiliki format yang benar (misalnya, P001, P123) dan harus unik.
Admin diminta untuk memasukkan nama produk, harga, dan stok dengan urutan yang benar dan memastikan bahwa input yang diberikan valid.
Pembelian oleh Pelanggan:

Pelanggan dapat memilih produk yang tersedia dengan memasukkan kode produk.
Program menghitung total harga pembelian dan memungkinkan penerapan diskon jika pelanggan memiliki kode diskon.
Pelanggan dapat melakukan pembayaran, dan jika pembayaran mencukupi, program akan mencetak struk pembelian beserta kembalian.
Validasi Input:

Program memvalidasi input dari pengguna untuk memastikan semua informasi yang dimasukkan sesuai dengan format yang diinginkan dan tidak ada kesalahan input (misalnya, harga negatif, stok negatif, kode produk tidak valid).
Pengelolaan Stok:

Setelah pembelian dilakukan, stok produk akan berkurang sesuai dengan jumlah yang dibeli oleh pelanggan.
Penghitungan Diskon:

Admin dapat mengatur diskon untuk total transaksi, yang akan diterapkan secara otomatis saat pelanggan melakukan pembayaran.
Cara Menggunakan Program:
1. Menjalankan Program
Program ini dibuat menggunakan Python 3. Pastikan Python sudah terinstall di komputer Anda.
Untuk menjalankan program, simpan file dengan ekstensi .py (misalnya kasir.py), kemudian buka terminal atau command prompt dan jalankan perintah berikut:
python kasir.py
2. Menu Utama
Setelah menjalankan program, Anda akan dihadapkan pada menu utama yang menawarkan 3 opsi:

Admin input produk: Menambahkan produk baru ke dalam daftar produk yang tersedia.
Pembelian oleh pelanggan: Proses transaksi pembelian produk oleh pelanggan.
Keluar: Menutup program.
3. Admin Input Produk
Pilih opsi 1 untuk menginput produk baru.
Program akan meminta Anda untuk memasukkan kode produk, nama produk, harga produk, dan jumlah stok produk.
Pastikan kode produk sesuai format P001, P123, dll, dan harga serta stok produk valid (tidak negatif).
Contoh Input:

Masukkan kode produk (contoh: P001, P123): P001
Masukkan nama produk: Laptop
Masukkan harga produk: 10000000
Masukkan jumlah stok produk: 5
4. Pembelian oleh Pelanggan
Pilih opsi 2 untuk melakukan transaksi pembelian.
Program akan menampilkan daftar produk yang tersedia untuk dibeli.
Pelanggan dapat memilih produk dengan memasukkan kode produk dan jumlah yang ingin dibeli.
Program akan menghitung total harga, dan pelanggan dapat memasukkan kode diskon jika ada.
Setelah itu, pelanggan diminta untuk memasukkan jumlah pembayaran.
Contoh Transaksi:

Masukkan kode produk (atau 'exit' untuk selesai): P001
Masukkan jumlah Laptop yang ingin dibeli: 1

Apakah Anda memiliki kode diskon? (y/n): y
Masukkan persentase diskon: 10

Total yang harus dibayar: 9000000
Masukkan jumlah pembayaran: 10000000
5. Struk Pembelian
Setelah pembayaran diterima, program akan mencetak struk pembelian yang mencakup:

Nama produk, jumlah yang dibeli, dan subtotal.
Total harga, diskon (jika ada), total setelah diskon, jumlah pembayaran, dan kembalian.
Contoh Struk:

--- Struk Pembelian ---
Laptop x1 = 10000000
Total: 10000000
Diskon: 10%
Total setelah diskon: 9000000
Pembayaran: 10000000
Kembalian: 1000000

Terima kasih telah berbelanja!
Cara Menambahkan Produk
Admin dapat menambahkan produk baru kapan saja selama aplikasi berjalan dengan memilih opsi 1 (Input Produk).
Admin akan diminta untuk memasukkan informasi produk sesuai urutan yang benar: kode produk, nama produk, harga produk, dan jumlah stok produk.
Jika kode produk sudah ada, admin akan diminta untuk memasukkan kode yang berbeda.
Nama produk dan harga produk juga akan divalidasi agar tidak kosong dan valid.
Cara Mengelola Pembelian
Pelanggan dapat memilih produk yang ingin dibeli dengan memasukkan kode produk yang tersedia.
Pembayaran akan diproses setelah pelanggan memasukkan jumlah pembayaran yang valid.
Jika pembayaran kurang, pelanggan akan diminta untuk memasukkan jumlah pembayaran yang cukup.
Validasi dan Kesalahan Input
Kode Produk: Harus diawali dengan huruf P diikuti dengan tiga digit angka (misalnya: P001).
Harga Produk: Harus berupa angka dan tidak boleh negatif.
Jumlah Stok: Harus berupa angka bulat dan tidak boleh negatif.
Jumlah Pembayaran: Harus berupa angka dan lebih besar atau sama dengan total harga.
Diskon: Harus berupa angka antara 0 hingga 100 persen.
Teknologi yang Digunakan:
Python 3: Program ini dibuat menggunakan Python versi 3.x.
Regex: Digunakan untuk memvalidasi format kode produk.
Troubleshooting:
Input Tidak Valid:
Jika Anda memasukkan data yang tidak valid, program akan meminta Anda untuk mengulang input dengan benar.
Produk Tidak Tersedia:
Jika Anda mencoba membeli produk dengan kode yang tidak ada dalam daftar produk, program akan memberi tahu Anda bahwa produk tersebut tidak ditemukan.
