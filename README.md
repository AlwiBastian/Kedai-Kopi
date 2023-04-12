# Kedai-Kopi

Ananda Coffee adalah sebuah program sederhana yang mengimplementasikan konsep Object-Oriented Programming (OOP) untuk mengelola pemesanan menu minuman kopi.

Program ini terdiri dari dua kelas, yaitu:

Kelas MenuKopi: Kelas ini merupakan representasi dari menu minuman kopi yang terdiri dari nama dan harga. Kelas ini memiliki getter dan setter untuk mengakses dan mengubah nilai nama dan harga menu.

Kelas AnandaCoffee: Kelas ini merupakan representasi dari toko kopi Ananda Coffee yang memiliki beberapa menu minuman kopi. Kelas ini memiliki tiga metode utama:

show_menu(): Metode ini digunakan untuk menampilkan daftar menu minuman kopi beserta harga.
pesan_menu(pesan, jumlahpesan): Metode ini digunakan untuk memproses pemesanan menu minuman kopi berdasarkan input pengguna. Metode ini menghitung harga, diskon, dan PPN (Pajak Pertambahan Nilai) berdasarkan jumlah pesanan dan menampilkan detail pesanan.
__init__(): Metode inisialisasi yang digunakan untuk menginisialisasi daftar menu minuman kopi saat objek AnandaCoffee dibuat.
Program ini juga dilengkapi dengan loop while yang memungkinkan pengguna untuk terus melakukan pemesanan selama pengguna ingin melanjutkan. Program akan berhenti jika pengguna memilih untuk tidak melanjutkan.
