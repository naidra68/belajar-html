# Form file

Biasanya, ketika ada form pasti-nya ada hal yang perlu di upload, contohnya ketika ada formulir diri. Maka dibagian bawah formulir biasanya terdapat file upload untuk mengunggah dokumen penting yang harus di siapkan. Untuk proses upload ini HTML menyediakan input type `file`.

berikut contoh penulisan singkat-nya

```html
<p>Upload Foto : <input type="file" name="file_gambar"></p>
```

Seperti biasa, kita pakai atribut name hanya sekedar sebagai penamaan saja, fungsinya akan jalan jika berurusan dengan server. Untuk penulisan lengkap dengan form-nya adalah sebagai berikut.

```html
<form action="proses.php" method="post">
    <p>Nama : <input type="text" name="nama"></p>
    <p>Upload Foto : <input type="file" name="file_gambar"></p>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```


## enctype

Biasanya, setiap form yang memiliki file upload, pada tag `<form>` terkadang ditambahkan sebuah attribut baru bernama `enctype` dengan isian `multipart/form-data`. Fungsi dari enctype ini hanyalah sebagai encode serta berkaitan dengan cara pengiriman data ke server.

Sebenarnya, web browser secara default sudah memiliki atribut `enctype` pada tag `<form>`, apabila atribut `enctype` tidak di tulis atau didefinisikan. Default-nya adalah `application/x-www-form-urlencoded`. Perbedaan anatara kedua `enctype` ini pada proses encoding-nya, dimana encoding ini merujuk pada pengiriman data karakter khusus yang akan diubah menjadi karakter ASCII.

Untuk `multipart/form-data` semua datanya akan dikirim semesti-nya meskipun ada karakter khusus seperti spasi akan dikirim spasi. Namun berbeda dengan `application/x-www-form-urlencoded` ketika ada spasi maka dia akan dikirim sebagai simbol `+`.

Teori diatas memang cukup rumit dipahami ketika baru belajar mengenai `enctype` ini, penjelasan lebih detail ketika belajar mengenai bahasa pemrograman untuk server seperti PHP. Berikut contoh penulisan lengkap=nya.

```html
<form action="proses.php" method="post" enctype="multipart/form-data">
    <p>Nama : <input type="text" name="nama"></p>
    <p>Upload Foto : <input type="file" name="fle_gambar"></p>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```

## accept

Ketika ingin memberikan batasan kepada file apa saja yang dapat diupload oleh user/admin. Maka atribut `accept` ini sangat direkomendasikan. Fungsi dari atribut ini sama seperti `maxlength` dimana sama-sama memiliki batasan kepada kondisi masing-masing.

Batasan yang dimaksud seperti kita ingin hanya file gambar saja yang dapat diupload, selain file gambar maka tidak akan terkirim file-nya. Berikut contoh penulisan lengkap=nya.

```html
<form action="proses.php" method="post" enctype="multipart/form-data">
    <p>Nama : <input type="text" name="nama"></p>
    <p>Upload Foto : <input type="file" name="fle_gambar" accept="image/*"></p>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```