# Tugas OOP
<br/>

Sebelum mengerjakan challenge ini, buatlah sebuah folder dengan nama “oop” di dalam direktori htdocs kalian. Di dalam folder oop tersebut buatlah sebuah file index.php sebagai entry dari program yang akan dibuat.<br/><br/>

## Class Animal
<br/>
Terdapat sebuah class Animal yang memiliki sebuah constructor name, default property legs = 4 dan cold_blooded = no.
<br/><br/>

### Release 0
<br/>
Buatlah class Animal tersebut di dalam file animal.php.Lakukan instance terhadap class Animal tersebut di file index.php. Lakukan import class Animal dari animal.php di dalam index.php menggunakan require atau require once (mengenai require bisa baca dari artikel berikut).
<br/><br/>
Tampilkan nama dari Animal yang baru dibuat tersebut.<br/>

![alt text](source/oop/gambar1.png)

<br/>

### Release 1
<br/>
Buatlah class Frog dan class Ape yang merupakan inheritance dari class Animal. Masing-masing class dibuat ke dalam satu file (Frog.php & Ape.php). Perhatikan bahwa Ape (Kera) merupakan hewan berkaki 2, hingga dia tidak menurunkan sifat jumlah kaki 4. class Ape memiliki function yell() yang mengeprint “Auooo” dan class Frog memiliki function jump() yang akan mengeprint “hop hop”.<br/><br/>

![alt text](source/oop/gambar2.png)

<br/>

### output akhir
<br/>

![alt text](source/oop/gambar3.png)
