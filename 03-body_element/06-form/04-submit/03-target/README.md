# Submit Target

Attribut ini berbeda dengan yang biasa-nya, karena biasa-nya attribut harus berada di dalam tag yang bersangkutan, berbeda dengan atribut `target`. Atribut `target` akan dipasangkan dengan tag `form` dan ketika tag `input` dengan type `submit` di klik, maka isian dari tag `form` akan diperlakukan sesuai isian atribut `target`.

Rada membingungkan bukan? sekarang kita coba lihat contoh penulisan-nya

```html
<form action="proses.php" method="get" target="_blank">
    // isian form disini
    // isian form disini
</form>
```

Sama seperti atribut kebanyakan, nilai dari atribut `target` bisa diisi selain `_blank`. Namun isian ini cukup sering digunakan agar setelah user mengklik submit maka hasil-nya akan ditampilkan pada new tab.

berikut contoh penulisan-nya secara lengkap

```html
<form action="proses.php" method="get" target="_blank">
    <p>Nama : <input type="text" name="name_user"></p>
    <p>Alamat: <input type="text" name="alamat_user"></p>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```

