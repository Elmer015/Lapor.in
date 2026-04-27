"# Lapor.in" 

System Overview
Lapor.In bertujuan untuk memudahkan masyarakat dalam melaporkan kejadian darurat atau masalah tertentu secara cepat melalui aplikasi. Sistem ini membantu pengguna mengirim laporan, melihat lokasi melalui GPS, serta menghubungi kontak darurat sehingga laporan dapat diterima dan ditindaklanjuti oleh pusat panggilan atau pihak berwenang.
Pengguna Aplikasi Lapor.In:
User, masyarakat yang ingin melaporkan kejadian atau melakukan panggilan darurat secara instan.
Pusat Panggilan, petugas yang menerima laporan dari pengguna, melihat detail laporan, serta menentukan tindakan lanjutan seperti menerima atau menolak laporan dan mengirimkan laporan tersebut ke pihak berwenang.
Mengirim laporan, melakukan panggilan darurat, melihat GPS.

Development View
FrontEnd
Menampilkan one-time login, formulir laporan, gps, status laporan yang telah dikirim, dan GPS.
BackEnd
Backend bertanggung jawab untuk memproses logika sistem seperti validasi data laporan, pengelolaan akun pengguna, pengiriman laporan ke pusat panggilan, serta pengolahan data yang diterima dari frontend.
Database
Database digunakan untuk menyimpan seluruh data sistem seperti data pengguna, laporan yang dikirimkan, lokasi GPS, serta status laporan yang telah diproses oleh pusat panggilan.

Process View
Pengguna membuka halaman Kirim Laporan pada aplikasi.
Sistem menampilkan formulir laporan kepada pengguna.
Pengguna mengisi formulir laporan dengan data yang diperlukan.
Sistem melakukan validasi apakah semua kolom wajib sudah terisi.
Jika ada kolom yang belum lengkap, sistem akan menampilkan notifikasi bahwa data belum lengkap.
Jika semua kolom sudah terisi, sistem akan menampilkan tombol kirim.
Pengguna menekan tombol kirim laporan.
Sistem memproses laporan dan menampilkan pesan bahwa laporan berhasil dikirim.
