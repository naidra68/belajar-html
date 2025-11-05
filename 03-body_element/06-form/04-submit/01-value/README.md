# Submit Value

Sama seperti hal-nya dengan textbox, type `submit` ini juga memiliki attribute yang menunjang agar type ini jelas kegunaan ataupun fungsi-nya untuk pengguna. Pada post ini yaitu atribut `value`. Dimana attribut ini sesuai nama-nya dapat memberikan nama custom pada type `submit` nya agar nama-nya tidak default `submit`.

langsung saja kita coba penulisan-nya dibawah ini 

```html
<p><input type="submit" value="Kirim Data"></p>
```

Apabila dijalankan pada form lengkap, maka akan menampilkan tombol dengan tulisan "Kirim Data". Inilah yang dimaksud custom nama tersebut. Attribute ini menekankan untuk UI yaitu User inferface dimana user dapat melihat-nya secara langsung.

berikut penulisan lengkap-nya dengan form

```html
<form action="form.php" method="get">
    <p>Nama : <input type="text" name="nama_user"></p>
    <p>Alamat : <input type="text" name="alamat_user"></p>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```