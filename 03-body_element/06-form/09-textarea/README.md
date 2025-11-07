# Form Textarea

Pernah melihat sebuah form yang memiliki inputan besar dan panjang? <s>seperti punya gw</s> Untuk membuat sebuah inputan seperti maka diperlukan tag yang bernama `<textarea>`. Berbeda dnegan tag `<input>` yang menggunakan void element tanpa penutup. Untuk `<textarea>` harus menggunakan tag penutup-nya yaitu `</textarea>`.

Selain itu, tag ini dapat dikontrol untuk lebar dan tinggi inputan-nya dengan cara menambahkan atribut `rows` dan `cols`.

> rows : baris (merujuk pada lebar)

> cols : kolom (merujuk pada tinggi)

sekarang, kita coba praktek gunakan tag ini. Berikut contoh penulisan-nya

```html
<p>Alamat : <textarea name="alamat" rows="4" cols="50"></textarea></p>
```

Apabila dijalankan, maka tag tersebut akan berukuran sesuai baris dan kolom yang telah diisi. Hitungnya baris dan kolom. Maka dari itu berhitungan baris dan kolom diperlukan disini. Kita coba penulisan lengkap jika berada didalam tag `<form>`.

Berikut conoh penulisan lengkap-nya.

```html
<h3>Textarea rows cols</h3>
<form action="proses.php" method="get">
    <p>Nama : <input type="text" name="nama"></p>
    <p>Alamat : <textarea name="alamat" rows="4" cols="50"></textarea></p>
    <input type="submit" value="Kirim Data">
</form>
```

Selain penulisan atribut `name`, kita juga bisa menambahkan atribut `value` untuk memberikan isi terlebih dahulu jika diperlukan ATAU? kita bisa gunakan penulisan langsung tanpa atribut `value`. Caranya cukup dengan menulis teks-nya diantara tag pembuka dan tag penutup. Berikut contoh penulisan-nya

```html
<p>Alamat : <textarea name="alamat" rows="4" cols="50">
    Jl Kemerdekaan No.225
</textarea></p>
```

Ketika dijalankan, terlihat bahwa ada tulisan "<b>Jl Kemerdekaan No.225</b>" tepat berada diatas tengah pada sebuah `<textarea>`. Untuk penulisan lengkap-nya bisa lihat dibawah ini.

```html
 <h3>Textarea nilai awal</h3>
 <form action="proses.php" method="get">
    <p>Nama : <input type="text" name="nama"></p>
    <p>Alamat : <textarea name="alamat" rows="4" cols="50">
        Jl Kemerdekaan No.225
    </textarea></p>
    <input type="submit" value="Kirim Data">
 </form>
```

# Form Textarea Maxlength

Atribut ini berfungsi untuk membatasi karakter yang dapat ditulis pada tag `<textarea>`. Biasanya digunakan ketika ingin membatasi user untuk menginput lebih banyak karakter yang telah ditentukan. Langsung saja, berikut contoh penulisan lengkap-nya.

```html
<form action="proses.php" method="get">
    <p>Nama : <input type="text" name="nama"></p>
    <p>Alamat : <textarea name="alamat" maxlength="10"></textarea></p>
    <input type="submit" value="Kirim Data">
</form>
```

Apabila dijalankan, ketika user mengetik sebanyak <b>10 kata</b> maka akan dibatasi dan tidak bisa mengetik lebih dari itu. Hal ini sebenarnya dapat diakali jika sudah paham mengenai inspect element. Namun itu hal lain, kita bahas tentang `maxlength` dulu saja.