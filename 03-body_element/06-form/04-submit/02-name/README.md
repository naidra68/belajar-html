# Submit name

Attribute name ini digunakan untuk mendefinisikan atau memberikan nama pada type `submit`-nya. Perbedaan antara atribute `name` dengan `value` bisa dilihat ketika berurusan dengan server. Dimana atribute `name` ini sangat penting dan harus di definisikan karena untuk berinteraksi kepada server nanti-nya, sedangkan `value` hanya untuk memberikan nama pada type `submit` kepada user.

Selain itu, atribute `name` ini dapat ditulis bebarengan dengan atribut `value`, berikut contoh penulisan-nya

```html
<p><input type="submit" value="Kirim Data" name="kirim"></p>
```

Jika dijalankan, tidak terlihat perbedaan-nya karena atribut ini hanya berfungsi untuk memberikan nama dan nantinya akan berinteraksi dengan server.

berikut contoh penulisan lengkap dengan form-nya

```html
<form action="proses.php" method="get">
    <p>Nama : <input type="text" name="name_user"></p>
    <p>Alamat: <input type="text" name="alamat_user"></p>
    <p><input type="submit" value="Kirim Data" name="kirim"></p>
</form>
```