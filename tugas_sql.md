# Berlatih SQL
<br/>

Tugaskali ini kamu diminta untuk menuliskan SQL Queries untuk membuat database, membuat table, mengisi data ke table, mengambil dan mengubah data ke table. Tulislah jawaban jawaban ke dalam sebuah file dengan nama jawaban.txt.
<br/><br/>

## Soal 1 Membuat Database
Buatlah database dengan nama “myshop”. Tulislah di text jawaban pada nomor 1.<br/><br/>

## Soal 2 Membuat Table di Dalam Database
Buatlah tabel – tabel baru di dalam database myshop sesuai data-data berikut.<br/><br/>
![alt text](source/sql/sql1.png)<br/>
![alt text](source/sql/sql2.png)
<br/>
![alt text](source/sql/sql3.png)
<br/>
tuliskan jawaban pada file text jawaban dengan nomor 2.<br/><br/>

## Soal 3 Memasukkan Data pada Table
Masukkanlah data data berikut dengan perintah SQL “INSERT INTO . . ” ke dalam table yang sudah dibuat pada soal sebelumnya.<br/><br/>
![alt text](source/sql/sql4.png)
<br/>
![alt text](source/sql/sql5.png)
<br/>
![alt text](source/sql/sql6.png)
<br/><br/>

## Soal 4 Mengambil Data dari Database
- Mengambil data users<br/>
Buatlah sebuah query untuk mendapatkan data seluruh user pada table users. Sajikan semua field pada table users KECUALI password nya.<br/><br/>
- Mengambil data items<br/>
a. Buatlah sebuah query untuk mendapatkan data item pada table items yang memiliki harga di atas 1000000 (satu juta).<br/>
b. Buat sebuah query untuk mengambil data item pada table items yang memiliki name serupa atau mirip (like) dengan kata kunci “uniklo”, “watch”, atau “sang” (pilih salah satu saja).<br/><br/>

- Menampilkan data items join dengan kategori<br/>
Buatlah sebuah query untuk menampilkan data items yang dilengkapi dengan data nama kategori di masing-masing items (gunakan join). Berikut contoh tampilan data yang ingin didapatkan<br/>
![alt text](source/sql/sql7.png)
<br>
<br/>

## Soal 5 Mengubah Data dari Database
Ubahlah data pada table items untuk item dengan nama sumsang b50 harganya (price) menjadi 2500000. Masukkan query pada text jawaban di nomor ke 5.
<br/><br/><br/><br/>

### Format tugas
buat file jawaban.txt dan copy sintax sql di jawaban.txt<br/>
contoh:<br/><br/>
1. Buat Database<br/>
create Database nama_database<br/><br/>

2. Membuat Table di Dalam Database<br/>
........