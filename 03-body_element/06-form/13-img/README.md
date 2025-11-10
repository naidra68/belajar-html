# form image

Sesuai dengan nama-nya, kita bisa membuat input type `img` atau gambar sebagai inputan form. Fungsi dari `img` ini sebagai pengganti tombol submit pada form, biasanya input type `img` ini digunakan ketika terdapat form yang berhubungan dengan titik koordinat suatu peta atau grafik sistematik.

Memang rada rumit teori-nya, sekarang kita akan mencoba-nya. Berikut contoh penerapan-nya

```html
<form action="proses.php" method="get">
    <p><input type="image" src="Bundaran_HI.jpg" name="gambar"></p>
</form>
```

Perlu diperhatikan, kita gunakan `get` untuk mendapatkan informasi-nya. Apabila dijalankan dan mencoba klik gambar-nya. Perhatikan bahwa URL-nya akan terdapat titik koordinat X dan Y.

Selain menjadi pencari titik koordinat gambar, input type `img` ini juga bisa menjadi pengganti input type `submit` dalam arti dapat di custom gambar-nya, kita gunakan tombol bergambar saja daripada tombol default. Berikut contoh penerapan-nya.

```html
<form action="proses.php" method="get">
    <p>Nama : <input type="text" name="nama_user"></p>
    <p>Password : <input type="text" name="password_user"></p>
    <p><input type="image" name="kirim" src="tombol.png" width="50"></p>
</form>
```