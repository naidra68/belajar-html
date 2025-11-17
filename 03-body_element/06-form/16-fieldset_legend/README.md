# Form Fieldset dan Legend

Tag fieldset dan legend berfungsi sebagai element yang mempercantik tampilan sebuah form. Dengan menggunakan dua tag ini maka setiap form akan tampil menarik an dikelompokkan sesuai pembagian-nya. Untuk melihat-nya lebih jelas, sekarang kita coba praktekkan.

berikut contoh penerapan-nya

```html
<form action="proses.php" method="get">
    <fieldset style="width: 300px;">
        <legend>Resolusi tahun ini</legend>
        <p><input type="checkbox" name="target1" value="HTML"> Menguasai HTML</p>
        <p><input type="checkbox" name="target2" value="CSS"> Paham CSS</p>
        <p><input type="checkbox" name="target3" value="PHP"> Jago PHP</p>
    </fieldset>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```

Kode diatas merupakan form dengan inputan checkbox untuk memilih resolusi tahun. Dengan ada-nya tag fieldset dan legend ini terdapat sebuah garis kota dengan tulisan `Resolusi tahun ini`. Itu merupakan fungsi dari kedua tag ini. Sekarang kita coba satu lagi form yaitu register dengan tambahan kedua tag tersebut.

berikut contoh penulisan lengkap-nya

```html
<form action="proses.php" method="get">
    <fieldset style="width: 300px;">
        <legend>Biodata</legend>
        <p>Nama : <input type="text" name="nama"></p>
        <p>Password : <input type="password" name="password"></p>
    </fieldset>
    <fieldset style="width: 300px;">
        <legend>Resolusi Tahun ini</legend>
        <p><input type="checkbox" name="target1" value="HTML"> Menguasai HTML</p>
        <p><input type="checkbox" name="target2" value="CSS"> Paham CSS</p>
        <p><input type="checkbox" name="target3" value="PHP"> Jago PHP</p>
    </fieldset>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```