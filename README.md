nabila tabaika (07352311111)

Penjelasan Program:
Program ini dirancang untuk menghitung gaji bersih seorang karyawan berdasarkan beberapa parameter, yaitu jumlah jam kerja per minggu, upah per jam, dan status karyawan(apakah karyawan tetap atau kontrak). Dengan menggunakan input yang diberikan oleh pengguna, program ini menghitung gaji kotor, menghitung pajak yang berlaku sesuai dengan status karyawan, dan akhirnya menghitung gaji bersih setelah pajak dipotong.

Langkah-langkah yang dilakukan oleh program ini:

1. Meminta Input dari Pengguna
   * Nama Karyawan: Program pertama kali meminta nama karyawan.
   * Jam Kerja Per Minggu: Pengguna diminta memasukkan jumlah jam kerja yang dilakukan oleh karyawan dalam seminggu. Program memvalidasi bahwa jumlah jam kerja harus lebih        dari 0.
   * Upah per Jam: Program meminta informasi tentang upah yang diterima karyawan per jam kerja. Upah per jam juga harus lebih dari 0.
   * Status Karyawan:Pengguna diminta untuk memilih apakah karyawan adalah tetap atau kontrak. Ini akan mempengaruhi tarif pajak yang diterapkan.

2. Menghitung Gaji Kotor dan Pajak:
    * Gaji Kotor dihitung dengan mengalikan jumlah jam kerja per minggu dengan upah per jam.
    * Pajak:** Pajak dihitung berdasarkan status karyawan:
    * Karyawan tetap dikenakan pajak 10% dari gaji kotor.
    * Karyawan kontrak dikenakan pajak 5% dari gaji kotor.

3. Menampilkan Slip Gaji:**
   * Program kemudian menampilkan slip gaji yang berisi nama karyawan, jam kerja per minggu, upah per jam, status karyawan, gaji kotor, pajak yang dikenakan, dan gaji bersih      setelah pajak.

Cara Menjalankan Program:
Berikut adalah langkah-langkah untuk menjalankan program ini di komputer Anda:

1. Persiapkan Lingkungan Dart:

* Pastikan Anda sudah menginstal Dart SDK di komputer Anda. Jika belum, Anda dapat mengunduhnya dari [situs resmi Dart](https://dart.dev/get-dart).

 Setelah berhasil menginstal Dart, periksa apakah Dart sudah terpasang dengan membuka terminal atau command prompt dan mengetikkan perintah:

  ```
  dart --version
  ```
  Jika Dart terpasang dengan benar, versi Dart yang terpasang akan ditampilkan.

2. Buat File Program:
* Buka editor teks (seperti Notepad, VS Code, atau Sublime Text).
* Salin kode program Dart yang telah disiapkan dan simpan ke dalam file dengan ekstensi `.dart`, misalnya dengan nama `gaji.dart`.

3. Menjalankan Program:
* Buka terminal atau command prompt.
* Arahkan ke folder tempat Anda menyimpan file `gaji.dart` menggunakan perintah `cd`. Misalnya:

  ```
  cd C:\Users\NamaPengguna\Documents
  ```
* Setelah berada di folder yang benar, jalankan program dengan mengetikkan perintah:

  ```
  dart run gaji.dart
  ```
4. Mengikuti Proses Input:

* Program akan meminta Anda untuk memasukkan beberapa informasi seperti nama karyawan, jam kerja per minggu, upah per jam, dan status karyawan.
* Setelah Anda memasukkan semua data yang diperlukan, program akan menghitung gaji kotor, pajak, dan gaji bersih, kemudian menampilkan slip gaji yang berisi informasi tersebut.

Catatan Penting:
* Pastikan Anda memasukkan nilai yang valid untuk jam kerja dan upah per jam. Program akan meminta Anda untuk mengulang input jika Anda memasukkan nilai yang kurang dari atau sama dengan 0.
* Saat diminta untuk memasukkan status karyawan, pastikan Anda mengetikkan "tetap" untuk karyawan tetap dan "kontrak" untuk karyawan kontrak. Program akan terus meminta input jika Anda memberikan nilai selain kedua pilihan ini.
