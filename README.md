# peraktikum11

Nama    : Angga Muhamad Gojali

Kelas   : TI.22.C1

NIM     : 312210030

# Exception Handling
* Exception (eksepsi) merupakan suatu kesalahan (error) yang terjadi saat proses eksekusi program sedang berjalan
* Kesalahan ini akan menyebabkan program berakhir dengan tidak normal.

# Handling
* Penanganan file adalah bagian penting dari aplikasi apa pun.

# Assertion
Assertion(pernyataan) adalah kewajaran program yang kamu bisa aktif/nonaktifkan ketika kamu selesai menjalankan program.

# The Assert Statement
* Saat menemukan pernyataan, Python mengevaluasi ekspresi yang menyertainya, yang mana semoga benar. Jika ekspresi salah, Python memunculkan pengecualian AssertionError.


Sintaks untuk pernyataan yaitu :
assert Expression[, Arguments]

Jika pernyataan gagal, Python menggunakan ArgumentExpression. ArgumentExpression sebagai argumen-argumen untuk AssertionError. Pengecualian AssertionError dapat ditangkap dan ditangani seperti pengecualian lainnya menggunakan try kecuali pernyataan, tetapi jika dibiarkan mereka akan menghentikan program dan menghasilkan backtrace.

- Contoh :
* Berikut adalah fungsi fungsi yang mengubah suhu dari derajat Kelvin menjadi derajat Fahrenheit.Karena nol derajat Kelvin dingin, fungsi fungsi menyimpannya jika melihat negatif negatif suhu.
* Ketika kode di bawah dijalankan, menghasilkan hasil sebagai berikut:

![Screenshot (90)](https://user-images.githubusercontent.com/116193257/208691122-51db74b6-71a7-4a5e-8479-ce771824d5a5.png)

# Menangani Pengecualian
Jika Anda memiliki beberapa kode mencurigakan yang mungkin mengeluarkan pengecualian, Anda dapat mempertahankan program Anda letakkan kode yang mencurigakan di *try: blok. Setelah coba: blok, sertakan pernyataan sertakan *except: statement, diikuti oleh blok kode yang menangani masalah seanggun mungkin.

Contoh :
* Contoh-contoh ini membuka file, menulis konten file, dan keluar dengan aman karena ada tidak masalah
* Ketika kode di bawah dijalankan, menghasilkan hasil sebagai berikut:
![Screenshot (93)](https://user-images.githubusercontent.com/116193257/208691570-06df9b51-09a6-4a33-992c-eb65f1f6443f.png)

* Contoh ini mencoba membuka file yang Anda tidak memiliki izin menulis, sehingga membuat file pengecualian
* Ketika kode di bawah dijalankan, menghasilkan hasil sebagai berikut:

![Screenshot (94)](https://user-images.githubusercontent.com/116193257/208691907-d40508cf-b5ba-4e00-9019-16a341c607f1.png)

# Fasal kecuali tanpa Pengecualian
* Anda juga dapat menggunakan pernyataan exception tanpa exception yang didefinisikan sebagai berikut:

try: You do your operations here; ...................... except: If there is any exception, then execute this block. ...................... else: If there is no exception then execute this block.

Pernyataan coba-kecuali jenis ini menangkap semua pengecualian pengecualian yang terjadi. Menggunakan percobaan seperti try-expect pernyataan tidak dianggap sebagai praktik pemrograman yang baik, karena mereka menangkap semuanya pengecualian tetapi tidak membuat programmer mengidentifikasi kemungkinan penyebab masalah terjadi

# Klausa kecuali dengan Berbagai Pengecualian
*Anda juga dapat menggunakan pernyataan exception yang sama untuk menangani beberapa exception sebagai berikut:

try: You do your operations here; ...................... except(Exception1[, Exception2[,...ExceptionN]]]): If there is any exception from the given exception list, then execute this block. ...................... else: If there is no exception then execute this block.

  Klausa coba-akhirnya

Contoh :

* Jika Anda tidak memiliki izin untuk membuka file dalam mode tulis yang dapat ditulis, maka ini akan menghasilkan hasil berikut:

![Screenshot (95)](https://user-images.githubusercontent.com/116193257/208693018-ba7375e3-3460-404f-9b9d-6c0e99e288ce.png)

* Contoh yang sama dapat ditulis lebih bersih sebagai berikut:
* 
![Screenshot (96)](https://user-images.githubusercontent.com/116193257/208693401-2c601286-e8d7-468a-b1c7-e323b2bbe07b.png)

* Ketika exception dilempar ke dalam blok try, eksekusi segera dilanjutkan ke akhir memblok. Setelah semua pernyataan di blok akhirnya dieksekusi, pengecualian dimunculkan lagi dan ditangani dalam pernyataan kecuali jika ada di lapisan berikutnya yang lebih tinggi dari percobaan-kecuali penyataan.

# Argumen Pengecualian

Contoh :
* Berikut adalah contoh untuk satu pengecualian
* Ketika kode di bawah dijalankan, menghasilkan hasil sebagai berikut:

![Screenshot (97)](https://user-images.githubusercontent.com/116193257/208693935-e973d607-ac71-48e7-a76f-8bb04350f6de.png)

# Melempar Pengecualian

Contoh :
* Pengecualian dapat berupa string, kelas, atau objek. Sebagian besar pengecualian adalah pengecualian dari inti Python menimbulkan adalah kelas dengan argumen=argumen yang merupakan turunan dari kelas. Mendefinisikan pengecualian baru cukup mudah dan dapat dilakukan sebagai berikut:

![Screenshot (99)](https://user-images.githubusercontent.com/116193257/208694197-27179cea-ac50-4116-9910-2170e44a9818.png)

# Sekian Dan Terimakasih


