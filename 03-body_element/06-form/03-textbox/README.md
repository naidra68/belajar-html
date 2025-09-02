# Form Textbox

Textbox merupakan inputan awal ketika membuat form pada document HTML, biasanya textbox ini ditulis dengan atribut `type` dan isi-nya ditulis dengan `text`. Textbox sendiri berada didalam tag `<input>`. Tag tersebut digunakan untuk membuat semua inputan form. Tag ini termasuk kedalam kelompok void element yang tidak memiliki tag penutup.

berikut contoh penerapan-nya

```html
<form action="form.php" method="get">
    <input type="text">
    <input type="text">
</form>
```

Kode diatas akan menjalankan inputan normal yang tampil pada document HTML, untuk memberikan penjelasan mengenai inputan apa yang akan di-isi, dapat menambahkan tag `<p>` pada tag `<input>`.

berikut contoh penerapan-nya

```html
<form action="form.php" method="get">
    <p>Nama : <input type="text"></p>
    <p>Kelas : <input type="text"></p>
</form>
```