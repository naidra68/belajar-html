# form color

Untuk mendapatkan sebuah warna yang diklik dan dibuah, HTML menyediakan tag input type `color`. Pada saat dipilih, inputan form akan menampilkan 'jendela warna' (color picker) tergantung jenis web browser dan sistem operasi yang digunakan.

berikut contoh kode-nya

```html
<form action="proses.php" method="get">
    <p>Warna Kesukaan : <input type="color" name="warna"></p>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```

Ketika dijalankan dan mencoba kirim form, terdapat sebuah kode warna yang dikirim dibagian url-nya (pastikan gunakan method get). Sebagai contoh, ketika kita memilih warna merah. Maka yang muncul di URL adalah sebagai berikut :

> http://127.0.0.1:5500/03-body_element/06-form/18-color/proses.php?warna=%23ff0000

`%23` merupakan kode ASCII dari karakter tagar `#`.