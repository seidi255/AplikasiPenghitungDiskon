# AplikasiPenghitungDiskon
 Tugas 3- SEIDI RAHMAT(2210010262)

Fungsi Utama Aplikasi

Aplikasi ini dirancang untuk membantu pengguna menghitung harga akhir suatu produk setelah diberikan diskon. Selain itu, aplikasi juga dapat menyimpan riwayat perhitungan untuk referensi di kemudian hari.

**Cara Kerja Aplikasi**

Input Data:

Pengguna memasukkan harga asli produk pada kolom yang disediakan.
Pengguna memilih persentase diskon yang berlaku atau memasukkan kode kupon untuk mendapatkan diskon tambahan.
Proses Perhitungan:

Aplikasi akan mengambil nilai harga asli dan persentase diskon yang telah dipilih.
Jika ada kode kupon yang dimasukkan, aplikasi akan memeriksa apakah kode kupon tersebut valid dan memberikan diskon tambahan sesuai dengan ketentuan yang telah ditetapkan.
Aplikasi kemudian menghitung total diskon yang berlaku dengan menambahkan persentase diskon dari pilihan pengguna dan diskon tambahan dari kode kupon (jika ada).
Harga akhir dihitung dengan mengurangi harga asli dengan total diskon.
Jumlah penghematan yang didapatkan juga dihitung dengan nilai total diskon.
Tampilan Hasil:

Hasil perhitungan, yaitu harga akhir dan jumlah penghematan, akan ditampilkan pada kolom yang telah disediakan.
Riwayat perhitungan akan ditambahkan ke dalam text area, sehingga pengguna dapat melihat kembali perhitungan sebelumnya.
Komponen Utama dalam Kode:

- JTextField: Komponen untuk menerima input berupa teks, seperti harga asli dan kode kupon.
- JComboBox: Komponen dropdown untuk memilih persentase diskon.
- JSlider: Komponen slider untuk memilih persentase diskon secara visual.
- JButton: Tombol untuk memulai proses perhitungan.
- JTextArea: Area teks untuk menampilkan riwayat perhitungan.
**Logika Pemrograman:**

EventHandler: Ketika tombol "Hitung" ditekan, sebuah event handler akan dijalankan.
Validasi Input: Aplikasi akan memeriksa apakah input harga asli berupa angka. Jika tidak, akan muncul pesan error.
Perhitungan Diskon: Aplikasi akan menghitung total diskon berdasarkan persentase diskon yang dipilih dan diskon tambahan dari kode kupon (jika ada).
Perhitungan Harga Akhir: Harga akhir dihitung dengan mengurangi harga asli dengan total diskon.
Pembaruan Tampilan: Hasil perhitungan akan ditampilkan pada komponen yang sesuai dan riwayat perhitungan akan diperbarui.
Keunggulan Aplikasi:

Mudah digunakan: Antarmuka pengguna yang sederhana dan intuitif.
Fleksibel: Pengguna dapat memilih persentase diskon dan menggunakan kode kupon.
Akurat: Perhitungan diskon dilakukan dengan benar.
Praktis: Menyimpan riwayat perhitungan untuk referensi di kemudian hari.

![Demo GIF](https://github.com/seidi255/AplikasiPenghitungDiskon/blob/main/img/demo%20diskon.gif)
