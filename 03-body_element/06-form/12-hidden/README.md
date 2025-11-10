# Hidden

Untuk membuat sebuah inputan yang dapat di sembunyikan dari tampilan user, bisa gunakan input type `hidden`. Biasa-nya sangat berguna apabila terdapat sesuatu data yang tidak perlu dilihat oleh user namun penting ditampilkan di web sebagai data website secara tersembunyi. Selain itu, data-nya juga tidak dapat diubah oleh user karena tersembunyi.

Input type `hidden` ini kelihatan berguna apabila sudah berurusan dengan server. Berikut contoh penulisan singkat-nya

```html
<input type="hidden" name="tersembunyi">
```

Contoh kasus paling berguna ketika sebuah form memiliki token atau identitas, dimana identitas ini tersembunyi dan tidak dapat dilihat user. Berikut contoh penerapan lengkap-nya.

```html
<form action="form.php" method="get">
    <p>Nama : <input type="text" name="nama_user"></p>
    <p>Password : <input type="text" name="password_user"></p>
    <input type="hidden" name="token" value="ash78rej883s">
    <p><input type="submit" value="Kirim Data"></p>
</form>
```