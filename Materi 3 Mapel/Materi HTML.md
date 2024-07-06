# Form
form adalah sebuah perintah yang berisikan point point untuk membuat sebuah form, mulai dari bar untuk mengisi nama, password dan hal hal lainnnya.

## Input
Elemen `<input>` adalah elemen form yang paling penting. Elemen `<input>`dapat ditampilkan dalam beberapa cara, tergantung pada nilai atribut type yang digunakan. Berikut adalah beberapa contoh nilai dari atribut type:

1. text digunakan untuk mengambil isian berupa teks. Contohnya seperti nama. contohnya ialah seperti berikut.
**Contoh Program :**
 ```html
<b>Nama:</b><br>
<input type="text"><br><br>
```
**Hasil Program :**
![Gambar 18](Aset/IMG7/IMG7_(1).jpg)

2. password digunakan untuk mengambil isian berupa kata sandi atau sesuatu yang bersifat rahasia. Tipe ini akan mengubah semua karakter yang diketikkan ke dalam karakter bulat. Contoh ialah seperti berikut.
  **Contoh Program :**
 ```html
<label> Password Anda : </label>
<input type="password>">
```
 **Hasil Program :**
![Gambar 22](Aset/IMG7/IMG7_(2).jpg)

3. radio digunakan sebagai kolom isian bertipe pilihan yang menawarkan beberapa opsi kepada user namun tetapi hanya satu opsi saja yang boleh dipilih. Contohnya seperti jenis kelamin atau agama. Contohnya ialah seperti berikut.
  **Contoh Program :**
```html
<b>Jenis Pembyaran:</b><br>
<input type="radio" name="JP">
<label>Tunai</label>

<input type="radio" name="JP">
<label>Transfer</label><br><br>  
```
**Hasil Program :**
![Gambar 24](Aset/IMG7/IMG7_(3).jpg)

Perlu diperhatikan bahwa untuk penggunaan tipe radio yang berkategori set pilihan yang sama mengharuskan nilai name -nya juga sama.

Opsi default dapat dilakukan dengan menambahkan atribut checked pada elemen opsi yang dijadikan sebagai opsi default.

4. checkbox digunakan untuk memberikan daftar pilihan dalam satu set opsi. User dapat memilih satu atau bahkan lebih dari satu pilihan pada tipe ini. Hal ini berbeda dengan tipe sebelumnya yaitu radio yang hanya memungkinkan user untuk memilih satu pilhan saja. Contoh penggunaan checkbox seperti daftar makanan kesukaan, daftar olahraga yang tidak disukai, dan yang semisalnya.
Elemen `<form>` HTML digunakan untuk mendefinisikan form yang digunakan untuk mengumpulkan inputan dari pengguna website. Tag ini digunakan untuk mengkoleksi inputan dari user, konsep ini sama seperti konsep formulir di dunia nyata. Contohnya ialah seperti berikut.
  **Contoh Program :**
```html
<b>Waktu Pengiriman:</b><br>
    <input type="checkbox">
    <label>Pagi</label>

    <input type="checkbox">
    <label>Siang</label>

    <input type="checkbox">
    <label>Sore</label>

    <input type="checkbox">
    <label>Malam</label><br><br>
```
**Hasil Program :**
![Gambar 25](Aset/IMG7/IMG7_(4).jpg)
  

### Label
- Elemen label memiliki fungsi khusus untuk melabeli sebuah kolom inputan. Ketika screen reader membaca konten halaman HTML, lalu menemukan sebuah inputan, ia akan membaca label yang bersangkutan.
- Fungsi lain dari tag `<label>` adalah ketika kita mengklik label, maka browser akan meletakkan fokus pada kolom isian yang terhubung dengannya. Syarat yang perlu diperhatikan yaitu dengan menghubungkan sebuah `<label>`dan `<input>` dengan atribut `<for>` untuk `<label>`, dan atribut `<id>` pada  dengan nilai untuk kedua atribut tersebut mesti sama persis.

## Select
- Elemen `<select>` berguna dalam mendefinisikan sebuah tombol ==dropdown== yang dimana user dapat memilih salah satu dari banyak pilihan. 
- `<aside>`Elemen `<select>` nantinya berperan sebagai kontainer atau pembungkus dari elemen `<option>` yang berperan sebagai daftar pilihan atau opsi.`</aside>`
- Elemen `<select>` hampir mirip fungsinya dengan `<input type=”radio">` akan tetapi baiknya elemen `<select>` digunakan untuk memilih satu pilihan yang terdapat banyak opsi di dalamnya, sedangkan `<input type=”radio">` lebih baiknya untuk digunakan jika  user diarahkan memilih hanya satu pilihan yang opsi pilihannya tidak terlalu banyak. Contoh penggunaan elemen ini seperti memasukkan pilihan berupa asal daerah atau yang semisalnya.Penting untuk diketahui  bahwasanya opsi yang aktif secara default adalah adalah opsi yang pertama. Akan tetapi, kita bisa mengatur opsi mana yang aktif secara default dengan menambahkan atribut selected pada suatu `<option>` yang ingin dijadikan sebagai opsi default. Contohnya ialah seperti berikut.
**Contoh Program :**
```html
<b>Jenis Bunga:</b>
 <Select>
	 <option>Bunga 1</option>
	 <option>Bunga 1</option>
 <Select>
```
  **Hasil Program :**
![Gambar 26](Aset/IMG7/IMG7_(5).jpg)

## Text Area
- Elemen `<textarea>` berguna untuk mengambil inputan user berupa teks yang dapat memuat *lebih dari satu baris*. Jika dibandingkan dengan elemen `<input>` teks biasa, elemen `<textarea>` memiliki ukuran tinggi yang lebih besar. Element textarea bisa diisi lebih dari satu baris dengan menekan enter. Atribut yang dapat digunakan untuk mengatur kuran dari textarea yaitu rows untuk jumlah baris, sedangkan atribut cols untuk lebarnya.
**Contoh Program :**
```html
 <input type="text area">
```
  **Hasil Program :**
![Gambar 27](Aset/IMG7/IMG7_(6).png)

## Button
- Elemen `<button>` yang berada di dalam sebuah form akan otomatis dianggap sama fungsinya seperti `<input type="submit">`. Jika ingin membuat tombol biasa yang tidak men-submit `<form>` dapat dilakukan dengan menambahkan atribut type="button".
- Beberapa atribut yang digunakan pada contoh di atas yang perlu untuk diperjelas yaitu sebagai berikut:
**Contoh Program :**
```html
 <input type="submit" value="kirim">
 <input type="reset" value="reset">
```
**Hasil Program :**
![Gambar 28](Aset/IMG7/IMG7_(7).png)

