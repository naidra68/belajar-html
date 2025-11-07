# Form Checkbox

Ketika ingin membuat form dengan pilihan, maka input type `checkbox` sangat cocok digunakan. input ini memungkinkan kita dapat membuat beberapa pilihan yang dapat dipilih dan akan dikirim ke server sebagai pilihan. Kita bisa membuat pilihan seperti bahasa pemrograman yang ingin dipilih seperti : PHP,Java,Javascript.

Namun sebelum itu, kita buat yang simple terlebih dahulu seperti membuat `checkbox` untuk persyaratan yang dipenuhi. Berikut contoh penulisan-nya.

```html
<!-- Simple Checkbox -->
 <h3>Normal Checkbox</h3>
<form action="proses.php" method="get">
    <p><input type="checkbox" name="persetujuan" value="setuju">
        Saya setuju dengan syarat dan ketentuan diatas</p>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```

Jika kita lihat pada kebanyakan website sekarang pada halaman login atau yang berhubungan dengan form maka checkbox ini sering kali digunakan untuk persetujuan persyaratan pada sebuah layanan website.

Sekarang, kita coba buat `checkbox` untuk memilih beberapa bahasa pemrograman yang telah kita kuasai. Berikut contoh penulisan lengkap-nya.

```html
<!-- List Checkbox -->
<h3>List Checkbox</h3>
<form action="proses.html" method="get">
    <p><input type="checkbox" name="target1" value="HTML"> Menguasai HTML</p>
    <p><input type="checkbox" name="target2" value="CSS"> Paham CSS</p>
    <p><input type="checkbox" name="target3" value="JS"> Jago JS</p>
    <p><input type="checkbox" name="target4" value="PHP"> Mastering PHP</p>
    <p><input type="checkbox" name="target5" value="MYSQL"> Expert MYSQL</p>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```

