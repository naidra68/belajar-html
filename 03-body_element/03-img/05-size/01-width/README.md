# Width

Atribut `width` digunakan untuk mengatur lebar sebuah gambar pada document HTML.

Apabila atribut lebar gambar hanya didefinisikan tanpa atribut tinggi gambar, maka untuk tinggi gambar akan menyesuaikan tinggi-nya secara otomatis agar gambar tidak tampak gepeng atau panjang.

Untuk isi dari atribut ini dapat menggunakan satuan pixel, namun tidak perlu tulis `px` dibelakang angkanya, cukup tuliskan angka satuan saja. Selain pixel, atribut ini dapat juga di isi menggunakan satuan percent. Untuk satuan percent, harus ditulis percentage setelah angkanya.

berikut contoh penerapan-nya

```html
<h3> Width dengan satuan pixel </h3>
<p>
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" width="300">
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" width="200">
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" width="100">
</p>
<h3> Width dengan satuan persen </h3>
<p>
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" width="75%">
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" width="50%">
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" width="25%">
</p>
```