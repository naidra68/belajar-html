# Atribut Method

Atribut ini digunakan untuk memberitahu web browser bahwa proses pengiriman data form ini akan seperti apa dan bagaimana, isi dai atribut ini ada dua yaitu **get** atau **post**.

## get

Nilai dari **get** ini akan membuat pengiriman data dari form diteruskan atau disambung ke alamat URL (terlihat pada address bar web browser) yang nantinya akan diteruskan kepada web server.

berikut contoh penerapan-nya

```html
<form action="form.php" method="get">
    <!-- Isi form disini -->
    <!-- Isi form disini -->
    <!-- Isi form disini -->
</form>
```

Apabila dijalankan, tidak akan terlihat apapun karena tidak ada tag pendukung untuk form tersebut, yang pasti adalah ketika form ini akan dikirim maka dia akan tampil didalam url data form-nya.

## post

Berbeda dengan **get**, nilai dari **post** ini tidak akan dikirim ke URL namun nilai-nya tidak akan terlihat dan tetap akan diteruskan ke web server.

```html
<form action="form.php" method="post">
    <!-- Isi form disini -->
    <!-- Isi form disini -->
    <!-- Isi form disini -->
</form>
```

Apabila dijalankan, tidak akan terlihat apapun karena tidak ada tag pendukung untuk form tersebut, yang pasti adalah ketika form ini akan dikirim maka dia akan tampil didalam url data form-nya.

<hr>

Untuk pengunaan-nya pada projek website real. Biasanya **get** ini digunakan untuk mengambil data dari web server seperti form pencarian. Sedangkan **post** ini digunakan untuk menyimpan data dari user ke dalam web server, karena data itu penting maka tidak disarankan data tersebut terlihat di URL web browser-nya.

Apabila method ini tidak ditulis dan lupa untuk didefinisikan, maka secara otomatis web browser akan menetapkan form tersebut menggunakan method **get**.