# Height

Atribut `height` digunakan untuk mengatur tinggi sebuah gambar pada document HTML.

Apabila sebuah gambar didefinisikan dengan tingginya tanpa mendefinisikan lebar-nya, maka lebar tidak akan menyesuaikan. Konsep seperti ini, kebalikan dari konsep atribut `width` dimana tinggi-nya akan menyesuaikan.

Jadi, berhati-hatilah untuk menggunakan tinggi gambar tanpa mencantumkan lebar-nya, karena nanti gambar bisa gepeng keatas.

Sama seperti `width`, untuk mengisi atribut ini dapat diisi satuan pixel dengan angka satuan saja dan juga satuan percent.

berikut contoh penerapan-nya

```html
<h3> Height dengan satuan pixel </h3>
<p>
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" height="300">
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" height="200">
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" height="100">
</p>
<h3> Height dengan satuan persen </h3>
<p>
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" height="75%">
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" height="50%">
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" height="25%">
</p>
```