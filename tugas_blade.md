# Memasangkan Template dengan Laravel Blade
<br/>

Challenge kali ini kalian ditantang untuk memasangkan template Admin LTE ke project Laravel kalian.
<br><br>

## Pasang Template Admin LTE
<br/>
Pasangkan template adminLTE pada project Laravel tugas. Lakukan seperti pada video tutorial mulai dari membuat master template, copy paste asset ke folder public dan terakhir merapikan.
<br/><br/>
link adminLTE : <a href="https://github.com/ColorlibHQ/AdminLTE/releases">admin-LTE</a>
<br/><br/>
<br/>

## Extend Template 
<br/><br/>

### Buat Route
<br/>
Pada project kali ini buatlah dua route : '/table' dan '/data-tables.
<br/><br/><br/>

#### Route '/table'
<br/>
Route '/table' berisi halaman yang menampilkan tabel berikut: <br/>
<a href="source/blade/table.html" download>table.html</a>
<br/><br/><br/>

#### Route '/table'
<br/>
Route '/table' berisi halaman yang menampilkan tabel berikut: <br/>
<a href="source/blade/datatables.html" download>datatables.html</a>
<br/><br/><br/>

Pada halaman data-tables kita membutuhkan asset CSS dan JS dari plugin data-tables. asset Javascript di antaranya datatables dan datatables-bs4 berikut ini script yang dibutuhkan (sesuaikan alamat asset dengan alamat yang ada di dalam project public).<br/>
<a href="source/blade/js.js" download>js.js</a>
<br/><br/>

Script dari datatables hanya dibutuhkan di view yang menampilkan route '/data-tables' dan tidak dibutuhkan di route '/' . gunakan directive @stack dan @push dari Blade untuk membuat kondisi tersebut terpenuhi.
<br/>
<br/>
<br/>

Output table "/table"
![alt text](source/blade/image-52-1024x544.png)
<br/><br/>

Output datatable "/data-table"
![alt text](source/blade/ss-baru-1024x514.png)