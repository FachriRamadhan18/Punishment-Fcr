

# Select Lanjutan
Setelah mempelajari select di materi sebelumnya sekarang kita akan masuk ke dalam materi select lanjutan, fungsi dari select select ini ialah untuk mendapatkan hasil yang lebih spesifik dan lebih luas, sekarang kita akan mempelajari 7 select lanjutan **(AND ,OR ,BETWEEN-AND ,NOT BETWEEN ,<= ,>= ,<> ATAU !=)** Untuk penjelasan lebih lanjutnya ialah seperti berikut :

> [!info]- Isi Table yang akan digunakan :
>>![Gambar19](Aset/IMG4/IMG4(1).png)
>

## AND
untuk **AND** ini akan mengambil "data 1" *dan* "data 2", contoh kodenya adalah seperti berikut :
```mysql
SELECT warna,pemilik FROM mobil WHERE warna="Hitam" AND pemilik="ibrahim";
```
Dan hasilnya akan seperti berikut :
![Gambar20](Aset/IMG4/IMG4(2).png)

## OR
Untuk **OR** ini akan mengambil "data 1" *atau* "data 2", contoh kodenya ialah seperti berikut :
```mysql
SELECT warna,pemilik FROM mobil WHERE warna="Hitam" OR pemilik="ibrahim";
```
Dan hasilnya akan seperti berikut :
![Gambar21](Aset/IMG4/IMG4(3).png)

## BETWEEN-AND
Untuk **BETWEEN-AND** ini akan mengambil antara "data 1" *sampai* "data 2" dibantu dengan **AND**, contoh kodenya ialah seperti berikut :
```mysql
SELECT * FROM mobil WHERE harga_rental BETWEEN 100000 AND 200000;
```
Dan hasilnya akan seperti berikut :
![Gambar22](Aset/IMG4/IMG4(4).png)

## NOT BETWEEN 
Untuk **NOT BETWEEN** ini akan mengambil "data" yang *bukan antara* "data 1" *dan* "data 2", contoh kodenya ialah seperti berikut :
```mysql
MariaDB [rental_nero]> SELECT * FROM mobil WHERE harga_rental NOT BETWEEN 100000 AND 200000;
```
Dan hasilnya akan seperti berikut :
![Gambar23](Aset/IMG4/IMG4(5).png)


## <=
Untuk **<=** ini akan mengambil "data"  lebih kecil atau sama dengan "nilai data", contoh kodenya ialah seperti berikut :
```mysql
MariaDB [rental_nero]> SELECT * FROM mobil WHERE harga_rental <= 50000;
```
Dan hasilnya akan seperti berikut :
![Gambar24](Aset/IMG4/IMG4(6).png)


## >=
Untuk **>=** ini akan mengambil "data"  lebih besar atau sama dengan "nilai data", contoh kodenya ialah seperti berikut :
```mysql
MariaDB [rental_nero]> SELECT * FROM mobil WHERE harga_rental >= 50000;
```
Dan hasilnya akan seperti berikut :
![Gambar25](Aset/IMG4/IMG4(7).png)


## <> atau !=
Untuk **<> atau !=** ini akan mengambil "data"  yang tidak sama dengan "nilai data", contoh kodenya ialah seperti berikut :
```mysql
MariaDB [rental_nero]> SELECT * FROM mobil WHERE harga_rental <> 50000;
```
Dan hasilnya akan seperti berikut :
![Gambar26](Aset/IMG4/IMG4(8).png)

