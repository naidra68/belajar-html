# Structure HTML

Sebagian besar pada struktur HTML, semua tag memiliki pasangan masing-masing kecuali tag `<!DOCTYPE html>` dan `<meta charset="UTF-8">`. Tag `<!DOCTYPE html>` adalah tag khusus yang dikenal dengan sebutan DTD (Document Type Declaration). DTD berfungsi untuk menginformasikan web browser tentang aturan penulisan dari suatu dokumen.

# Mengapa perlu DTD?

DTD harus ditulis diawal document HTML agar web browser tidak menampilkan sebuah website dalam bentuk **Quirks Mode**. **Quirks Mode** adalah sebuah model tampilan yang dipakai web browser ketika menampilkan kode HTML yang tidak standar. Biasanya model yang tidak standar berasal dari website tua yang dibuat puluhan tahun yang lalu.

Ketika sebuah file html di proses dalam **Quirks Mode**, web browser membuat beberapa perlakuan khusus yang bisa mempengaruhi tampilan. Hal tersebut akan menjadi masalah karena desain web yang telah dirancang tampilannya bisa berantakan.

berikut penulisan file html tanpa DTD

```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>No DTD</title>
</head>
<body>
    <h1>Belajar HTML</h1>
    <p>Hello World</p>
    <p>Halaman ini dimuat pada quirks mode karena tidak ada-nya DOCTYPE html</p>
</body>
</html>
```

Terlihat bahwa diawal penulisan tidak menyertakan DTD yang biasanya ada pada file HTML. Apabila dijalankan maka akan menampilkan web dalam **Quirks Mode**.

> Untuk melihat tampilan antara **Quirks Mode** atau tidak, silahkan gunakan web browser Mozilla Firefox.

berikut penulisan file html dengan DTD

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DTD</title>
</head>
<body>
    <h1>Belajar HTML</h1>
    <p>Hello World</p>
</body>
</html>
```

Terlihat terdapat DTD diawal penulisan file HTML. Jika dijalankan akan menampilkan mode normal yang dinamakan **Standards Compliance Mode**.