# Pertanyaan

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

# Jawaban

1. 
* sebelum dirubah :

![gambar 1](screenshot/foto1.png)

* tampilan dibrowser :

![gambar 2](screenshot/foto2.png)

* sesudah dirubah :

![gambar 3](screenshot/foto3.png)

* tampilan dibrowser :

![gambar 4](screenshot/foto4.png)

2. => Kalau h1{...} Untuk memberikan style pada semua element h1

=> Kalau #intro h1{...} Awalan simbol hash (#) memungkinkan kita untuk memberi style pada id. selector id bersifat kaku dan tidak bisa digunakan kembali pada element yang lainnya. Menurut saya lebih baik gunakan selektor class untuk mendefinisikan element yang ingin diberi nilai.

3. semua deklarasi akan ditampilkan di browser

contoh :
* deklarasi css internal dan inline css
![gambar 5](screenshot/foto5.png)

* deklarasi css eksternal
![gambar 6](screenshot/foto1.png)

* css eksternal di sisipkan dengan menambahkan tag link untuk merujuk file css yang sudah dibuat pada bagian head
![gambar 7](screenshot/foto7.png)

tampilan di browser :
![gambar 8](screenshot/foto2.png)

4. ketika deklarasi css selector dimasukan maka akan keluar pada browser

* sebelum ada deklarasi selector
![gambar 9](screenshot/foto8.png)

* setelah dimasukan deklarasi selector
![gambar 10](screenshot/foto10.png)

* tampilan di browser :
![gambar 11](screenshot/foto9.png)