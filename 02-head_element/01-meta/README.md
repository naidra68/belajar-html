# Meta Element

Meta merupakan singkatan dari metadata, yakni istilah untuk meneybut data yang menjelaskan informasi tentang suatu dokumen.

Tag ini berfungsi untuk memberi informasi mengenai halaman HTML yang sedang ditampilkan. Tag ini ditujukan bukan kepada pengunjung website, tetapi kepada web browser dan robot seperti mesin pencari.

Tag `meta` juga termasuk kelompok **void element** sehingga tidak memiliki pasangan tag penutup. Seluruh tag meta opsional untuk ditulis karena tidak semua akan digunakan kecuali meta :

## UTF-8

```html
<meta charset="UTF-8">
```

Jika hal tersebut tidak ditulis, validator HTML5 akan mengeluarkan error.

Mengapa bisa error?

**Meta charset** berfungsi untuk memebri informasi kepada web browser tentang bagaimana cara menerjemahkan karakter-karakter yang ada di dalam file HTML.

Charset sendiri merupakan singkatan dari character set yang isitlahnya berarti kumpulan daftar kode bit komputer dengan pasangan karakter.

Penjelasan ini cukup teknis karena melibatkan bit komputer yang dimulai dari 0 dan 1. Apabila meta charshet ini tidak ditulis maka jika terdapat sebuah karakter yang tidak dikenali maka dia akan menjadi error.

> Error yang dimaksud adalah ketika anda melihat teks yang menjadi kotak kotak atau karakter aneh.

## Meta Author, Keywords, dan Description

Ketiga meta tag ini funginya mirip yaitu ditujukan untuk memeprmudah mesin pencarian (seperti Google) dalam menggali informasi dari sebuah halaman web.

Meta tag ini ditulis dengan atribut **name** untuk jenis informasi, dan atribut **content** untuk isi informasinya.

berikut contoh penerapan-nya

```html
<meta name="author" content="naidra68">
<meta name="keywords" content="Tutorial HTML,CSS,JS,PHP,MYSQL">
<meta name="description" content="Naidra68 adalah sebuah web archive dimana anda dapat melihat penulis menceritakan kehidupan-nya disini.">
```

Ketiga tag ini bersifat opsional dan tidak harus ditulis karena masih tahap pembelajaran. Tag ini wajib ditulis ketika berurusan dengan teknik SEO dan website yang siap dipakai dan sudah online.

## Meta Refresh

Meta tag ini cukup menarik, biasanya dipakai untuk membuat halaman web refresh secara otomatis setiap beberapa detik. Meta tag refresh butuh atribut **http-equiv** dengan nilai refresh, dan atribut **content** yang berisi angka dalam satuan detik.

Tag meta ini biasanya ditambahkan ke dalam halaman web yang konten-nya selalu di update seperti situs berita. Karena berita setiap detik pasti ada yang terbaru maka diperlukan meta refresh ini.

berikut contoh penerapan-nya

```html
<meta http-equiv="refresh" content="60">
```

Selain untuk memuat ulang konten setiap detik, meta ini juga dapat digunakan sebagai redirect, yakni mengalihkan web browser ke halaman lain.

berikut contoh penerapan-nya

```html
<meta http-equiv="refresh" content="10; url=https://www.google.com/">
```

## Meta tag X-UA-Compatible

Meta tag ini berfungsi untuk emnangani permasalah terkait web browser Internet Explorer. IE memiliki mode **compatibility view** ynag aktif ketika halaman web diakses dari komputer lokal atau diakses dari dalam intranet.

Fitur compatibility view ini membuat perlakuan berbeda dalam menangani halaman web (mirip **quirks mode**). Meta tag di atas akan memaksa IE agar tidak masuk ke mode compatibility view,

berikut contoh penerapan-nya

```html
<meta http-equiv="X-UA-Compatible" content="IE=edge">
```

## Meta tag Viewport

Meta tag ini digunakan pada web dengan **desain responsive** (responsive web design). Secara garis besar, meta tag viewport diperlukan agar desain responsive dapat tampil sempurna di dalam layar berukuran kecil (seperti tablet atau smartphone).

berikut contoh penerapan-nya

```html
<meta name="viewport" content="width=device-width, initial-scale=1">
```

## Meta tag Robots

Meta tag ini digunakan untuk memberi pesan kepada mesin pencari seperti Google bagaimana halaman web akan diproses.

Jika nilai atribut **content** adalah **index,follow**. Maka mesin pencari akan mengindex halaman tersebut.

Namun jika nilai atribut **content** adalah **noindex, nofollow**, maka isi web tidak akan dimasukkan ke hasil pencarian.

Secara garis besar, tag ini digunakan untuk SEO saat website sudah siap digunakan dan online.

berikut contoh penerapan-nya

```html
<meta name="robots" content="index, follow">
```