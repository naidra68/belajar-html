# Form Radio

Sama seperti input type `checkbox`. Pada input type `radio` juga memiliki fungsi untuk membuat pilihan pada form, namun perbedaan antara kedua-nya terdapat pada pilihan yang terbatas. Jika kita menggunakan `checkbox` kita dapat mengisi beberapa pilihan sedangkan jika menggunakan `radio` kita hanya bisa mengisi satu pilihan saja.

> checkbox : beberapa pilihan
> radio : hanya 1 pilihan

Berikut contoh penggunaan `radio` pada pemilihan jenis kelamin yang ada di dalam form.

```html
<!-- Normal Radio -->
<h3>Pilih Jenis Kelamin</h3>
<form action="proses.php" method="get">
    <p><input type="radio" name="jenis_kelamin" value="laki_laki"> Laki-Laki</p>
    <p><input type="radio" name="jenis_kelamin" value="perempuan"> Perempuan</p>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```

Karena jenis kelamin harus dipilih satu saja, maka fungsi dari `radio` ini sangat cocok digunakan daripada `checkbox`. Selain itu, kita bisa mencoba buat pilihan bahasa pemrograman terbaik, karena memilih bahasa terbaik maka kita perlu gunakan `radio` untuk pemilihan satu-satu.

berikut contoh penulisan secara lengkap.

```html
<!-- List Radio -->
<h3>Best Programming Language</h3>
<form action="proses.php" method="get">
    <p><input type="radio" name="pro" value="HTML"> HTML</p>
    <p><input type="radio" name="pro" value="JS"> Javascript</p>
    <p><input type="radio" name="pro" value="JAVA"> Java</p>
    <p><input type="radio" name="pro" value="PHP"> PHP</p>
    <p><input type="radio" name="pro" value="PYTHON"> Python</p>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```

# Form Radio (Checked)

Pada type `radio` ini juga terdapat kondisi `checked`. Rada berbeda dengan `checkbox` yang dapat menggunakan kondisi ini beberapa kali. Pada `radio` kita hanya bisa menggunakan pada satu inputan saja karena sesuai fungsi dari si `radio` ini harus pilih salah satu.

berikut contoh penulisan lengkap=nya

```html
 <!-- List Radio -->
 <h3>Best Programming Language</h3>
 <form action="proses.php" method="get">
     <p><input type="radio" name="pro" value="HTML" checked> HTML</p>
     <p><input type="radio" name="pro" value="JS"> Javascript</p>
     <p><input type="radio" name="pro" value="JAVA"> Java</p>
     <p><input type="radio" name="pro" value="PHP"> PHP</p>
     <p><input type="radio" name="pro" value="PYTHON"> Python</p>
     <p><input type="submit" value="Kirim Data"></p>
 </form>
```



