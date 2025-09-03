# Textbox value

Atribut value digunakan untuk memberikan nilai awal pada sebuah inputan form. Apabila atribut ini tidak ditullis maka tidak akan terjadi apa-apa. Ketika ditulis maka ada nilai yang diisi didalam inputan.

berikut contoh penerapan-nya

```html
<form action="form.php" method="get">
    <p>Nama : <input type="text" name="nama" value="Tri Ardian"></p>
    <p>Kelas : <input type="text" name="kelas" value="12"></p>
</form>
```

Apabila dijalankan, maka akan terlihat bahwa inputan tersebut sudah terisi. Atribut ini sering dipakai jika sudah memasuki sisi server dimana setiap data yang telah diisi akan ditampilkan.