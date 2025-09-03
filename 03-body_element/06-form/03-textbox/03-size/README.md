# Textbox size

Atribut ini digunakan untuk mengatur panjang sebuah textbox. Nilai dari atribut ini berupa angka yang dinyatakan dalam satuan huruf.

contoh :

> `size="5"` berarti panjang sebuah textbox akan diset agar pas sebanyak 5 karakter.

berikut contoh penerapan-nya

```html
<form action="form.php" method="get">
    <p>Nama : <input type="text" name="nama" size="5"></p>
    <p>Kelas : <input type="text" name="kelas" size="2"></p>
</form>
```

Apabila dijalankan, terlihat bahwa textbox akan menyesuaikan size-nya karena telah ditambahkan atribut nya pada tag `<input>`. Biasanya, atribut ini sangat dipakai apabila ingin custom ukuran dari sebuah textbox agar tidak terlalu panjang.