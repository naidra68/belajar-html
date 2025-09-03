# Textbox readonly

Atribut ini berfungsi untuk memberikan akses apakah sebuah inputan form dapat diubah nilainya oleh user atau tidak. Apabila atribut ini tidak ditulis, maka user dapat merubah nilai dari sebuah inputan kapanpun. Sedangkan jika terdapat atribut ini. maka inputan form tidak akan bisa diedit oleh user karena statusnya sudah readable.

berikut contoh penerapan-nya

```html
<form action="form.php" method="get">
    <p>Nama : <input type="text" name="nama" value="Tri Ardian" readonly></p>
    <p>Kelas : <input type="text" name="kelas" value="12"></p>
</form>
```

Apabila dijalankan, terlihat bahwa inputan dengan isi `Tri Ardian` tidak akan bisa di edit, namun tetap user dapat berinterasi dengan inputan tersebut dan dapat di klik.