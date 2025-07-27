# Whitespace

**Whitespace** adalah istilah yang merujuk ke karakter **spasi** yang tidak tampil di layar. Tidak hanya **spasi**, karakter whitespace juga mencakup **tab** dan karakter **enter**.

Pada HTML, whitespace akan diabaikan dan tidak akan diproses oleh web browser meskipun pada file html terdapat banyak whitespace.

berikut contoh penerapannya tanpa whitespace

```html
<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Belajar HTML</title></head><body><h1>Belajar HTML</h1><p>Sebuah pargraf sederhana.</p>
<p>Whitespace tidak berpengaruh pada tampilan</p></body></html>
```

Jika kode diatas dijalankan, web browser akan tetap menggap hal itu valid dan bisa diproses dengan baik.

berikut contoh penerapannya dengan whitespace

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Belajar HTML</title>
</head>
<body>
    <h1>Belajar HTML</h1>
    <p>Sebuah paragraf sederhana</p>
    <p>Whitespace tidak berpengaruh pada tampilan</p>
</body>
</html>
```

Mengapa hal ini perlu diperhatikan? Alasannya sederhana, agar terlihat lebih rapi saja jika menggunakan whitespace, toh juga whitespace tidak berpengaruh pada hasilnya. Dalam beberapa kasus untuk web kompleks, penggunaan whitespace ini akan mempengaruhi performa web tersebut.