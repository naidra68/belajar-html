# Form Submit

Form ini merupakan sebuah form biasa yang ditambah inputan type `submit`. Inputan submit inilah yang dapat membuat sebuah form bekerja semesti-nya karena terdapat tombol untuk mengirim data yang telah di isi.

berikut contoh penulisan-nya

```html
<p><input type="submit"></p>
```

Untuk penerapan-nya pada element form sebagai berikut

```html
<form action="form.php" method="get">
    <p>Nama : <input type="text" name="nama_user"></p>
    <p>Alamat : <input type="text" name="alamat_user"></p>
    <p><input type="submit"></p>
</form>
```

Tidak ada yang spesial dengan ini dan informasi-nya hanya seperti itu, namun perlu diingat bahwa semua form pasti memiliki input type `submit` ini, jadi pastikan menulis kode-nya dan taruh dipaling bawah.