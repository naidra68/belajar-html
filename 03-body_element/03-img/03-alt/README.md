# Alternate

Atribut ini digunakan untuk menampilkan keterangan pada gambar, atribut ini tidak akan terlihat jika sebuah gambar berhasil dimuat di website.

berikut contoh penerapan-nya

```html
 <!-- Normal -->
<img src="../Bundaran_HI.jpg" alt="Bundaran HI">
```

Apabila user tidak memiliki internet dan gambar tidak berhasil dimuat, maka atribut ini akan menampilkan tulisan-nya untuk memberitahu bahwa gambar ini ada.

```html
<!-- Normal -->
<img src="../Bundaran_HI.jpg" alt="Bundaran HI">

<!-- Gambar Error/Network Lemot -->
<img src="../undaran_HI.jpg" alt="Bundaran HI">
```