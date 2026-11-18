Sistem Informasi Pencarian dan Pemantauan Stok Barang
Dengan Pembaruan Stok Otomatis Berbasis Desktop

Repository ini berisi dokumentasi dan pengembangan proyek mata kuliah
Pemrograman Berorientasi Objek (PBO), yaitu sistem informasi untuk
membantu toko mengelola data barang, melakukan pencarian, mencatat
transaksi, dan memantau persediaan.
Status proyek: Tahap perancangan / usulan sistem. Fitur-fitur di
bawah merupakan rancangan berdasarkan laporan, bukan klaim bahwa
aplikasi sudah selesai diimplementasikan.

Latar Belakang
Pengelolaan stok secara manual menggunakan buku atau spreadsheet dapat
menyebabkan pencarian barang menjadi lambat, pembaruan stok terlambat,
kesalahan pencatatan, serta kesulitan mengetahui barang yang hampir
habis. Sistem ini diusulkan untuk membantu proses pengelolaan persediaan
secara lebih teratur, cepat, dan akurat.
Tujuan
- Memudahkan pengelolaan data barang.
- Mempercepat pencarian barang berdasarkan nama atau kata kunci.
- Membantu pencatatan transaksi penjualan dan barang masuk.
- Memperbarui jumlah stok secara otomatis setelah transaksi penjualan
  dikonfirmasi.
- Memantau stok terkini serta memberikan peringatan ketika stok
  menipis atau habis.
- Memungkinkan penggunaan fitur utama secara offline melalui basis
  data lokal.
Fitur yang Direncanakan
1. Pengelolaan Data Barang --- menambah, melihat, mengubah, dan
   menghapus data barang.
2. Pencarian Barang --- mencari barang berdasarkan nama atau kata
   kunci.
3. Transaksi Penjualan --- memilih barang, menentukan jumlah
   pembelian, menghitung total harga, dan mengonfirmasi transaksi.
4. Pembaruan Stok Otomatis --- mengurangi stok setelah transaksi
   berhasil dikonfirmasi dan mencegah stok menjadi negatif.
5. Pencatatan Barang Masuk --- mencatat penambahan persediaan dari
   pemasok.
6. Pemantauan Stok --- menampilkan jumlah stok terkini.
7. Peringatan Stok Menipis dan Habis --- memberi informasi ketika
   stok mencapai batas minimum atau tidak tersedia.
8. Riwayat Transaksi dan Pergerakan Stok --- menyimpan catatan
   penjualan dan barang masuk.
9. Penggunaan Offline --- menjalankan fitur utama tanpa koneksi
   internet selama aplikasi dan basis data lokal tersedia.
Target Pengguna
- Pemilik toko: memantau persediaan, melihat barang yang hampir
  habis, dan memeriksa riwayat transaksi.
- Petugas toko/kasir: mencari barang dan melayani transaksi
  penjualan.
- Petugas gudang: mencatat barang masuk dan memeriksa persediaan
  serta lokasi penyimpanan.
Teknologi yang Direncanakan
  Bagian                              Teknologi / Keterangan
  Bahasa pemrograman                  PHP

  Konsep pemrograman                  Pemrograman Berorientasi Objek
(PBO)

  Basis data                          SQLite atau MySQL lokal

  Platform                            Aplikasi desktop
Identifikasi barang                 Pencarian nama/kata kunci; pemindai
barcode USB bersifat opsional
Teknologi tersebut merupakan pilihan yang tercantum dalam rancangan
laporan dan dapat disesuaikan saat tahap implementasi.
Ruang Lingkup dan Batasan
Fokus sistem adalah pengelolaan data barang, pencarian, transaksi
penjualan, pembaruan stok otomatis, pencatatan barang masuk, dan
pemantauan persediaan secara offline.

Hal-hal yang tidak termasuk dalam ruang lingkup awal:
- Sinkronisasi otomatis antarperangkat atau antarcabang.
- Integrasi dengan marketplace atau platform pihak ketiga.
- Pemesanan otomatis kepada pemasok.
- Notifikasi melalui WhatsApp, SMS, atau email.
- Penggunaan RFID atau IoT.
- Pengelolaan keuangan usaha secara menyeluruh.
- Penggantian pemeriksaan fisik barang.
