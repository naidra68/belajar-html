# Textbox Name

Tag `<input>` dapat ditambah dengan berbagai atribut. Salah satu yang paling penting adalah atribut `name`. Atribut ini berperan sebagai penanda inputan form dan berguna pada saat form diproses menggunakan kode PHP nantinya. Atribut name bisa dipakai untuk semua inputan form.

berikut contoh penerapan-nya

```html
<form action="form.php" method="get">
    <p>Nama : <input type="text" name="nama"></p>
    <p>Kelas : <input type="text" name="kelas"></p>
</form>
```

Ketika dijalankan, tidak akan terlihat perbedaan dan tampilan-nya tetap sama seperti sebelum menambahkan atribut `name`. Perubahan ini akan berpengaruh pada sisi server dan bukan pada sisi client, jadi pengunjung tidak dapat melihatnya.

Atribut ini sangat berguna dan sering digunakan jika sudah ber-urusan dengan server dan form validation karena pembeda antara inputan satu dengan yang lain menggunakan atribut ini.


