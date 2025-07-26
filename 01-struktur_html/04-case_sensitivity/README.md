# Case Sensitivity

**Case Sensitivity** adalah istilah programming untuk menyebut apakah sebuah bahasa pemrograman membedakan penulisan huruf kecil dan huruf besar.

Untuk HTML, tidak ada **Case Sensitivity** karena mau menulis huruf besar ataupun kecil tidak akan mempengaruhi fungsi dari tag tersebut. Namun, saat ini penulisan tag menggunakan huruf kecil sudah menjadi kebiasaan para programmer diseluruh dunia.

# Closing Tag

Setiap tag pada HTML pasti terdapat pasangan pembuka dan penutup tag-nya. Namun ada beberapa tag yang tidak memiliki penutup dan menjadi satu seperti tag `<meta>`, `<br>`, `<img>`, dan lain-lain. Tag ini disebut sebagai **void element**.

Pada HTML5, penulisan **void element** yang awalnya terdapat tanda slash diakhir kalimat, sekarang tidak diperlukan lagi.

Penulisan tag html harus ada penutupnya, apabila salah menuliskan tagnya dan yang ada hanyalah tag pembuka semua, maka tampilan dari webnya akan terkesan berantakan.

berikut contohnya

```html
<p>Teknologi web dimulai dari <strong>HTML</strong>. <em>semua berawal dari HTML<em> dan diteruskan dengan CSS serta disempurnakan dengan Javascript</p>
```

Jika dijalankan, tag `<em>` akan memberikan tulisan miring tidak hanya dikata **HTML** saja, namun tetap berlanjut hingga akhir kata.

Maka dari itu, melihat pembuka dan penutup pada sebuah tag HTML perlu diperhatikan. Berikut contoh penerapan yang benar.

```html
<p>Teknologi web dimulai dari <strong>HTML</strong>. <em>semua berawal dari HTML</em> dan diteruskan dengan CSS serta disempurnakan dengan Javascript</p>
```