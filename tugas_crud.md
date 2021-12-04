# Berlatih CRUD di Laravel
<br/><br/>

## Siapkan Database Dengan Migration<br/>
---
Melanjutkan project laravel kemarin, pastikan database sudah siap dengan melakukan migration untuk tabel-tabel yang diperlukan.
Untuk saat ini, tabel yang diperlukan hanya tabel cast saja.<br/><br/>

## Proses CRUD<br/>
---
Setelah table tersedia, maka kita dapat mulai membuat proses CRUD. Buatlah CRUD untuk fitur Cast. Berikut ini gambaran Route dan Controller yang diinginkan<br/><br/>

| Url      | Method | Handler | Keterangan
| ----------- | ----------- | ----------- | ----------- |
| /cast      | GET       | CastController@index | menampilkan list data para pemain film (boleh menggunakan table html atau bootstrap card)
| /cast/create   | GET        | CastController@create | menampilkan form untuk membuat data pemain film baru
| /cast      | POST       | CastController@store | menyimpan data baru ke tabel Cast
| /cast/{cast_id}   | GET        | CastController@show | menampilkan detail data pemain film dengan id tertentu
| /cast/{cast_id}/edit      | GET       | CastController@edit | menampilkan form untuk edit pemain film dengan id tertentu
| /cast/{cast_id}   | PUSH        | CastController@update | menyimpan perubahan data pemain film (update) untuk id tertentu
| /cast/{cast_id}   | DELETE        | CastController@destroy | menghapus data pemain film dengan id tertentu