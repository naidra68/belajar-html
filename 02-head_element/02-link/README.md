# Link Element

Tag `<link>` digunakan untuk membuat hubungan antara halaman HTML dengan file lain. Namun saat ini penggunaan  paling banyak adalah untuk menginput file CSS external ke halaman HTML. Link element memiliki beberapa atribut, diantaranya **herf** dan **rel**.

Atribut **href** (singkatan dari hypertext references) dipakai untuk menulis alamat lokasi file external yang akan dituju.

Atribut **rel** (singkatan dari relationship) berisi jenis hubungan dengan file tersebut.

berikut contoh penerapan-nya

```html
<link href="style.css" rel="stylesheet">
```

## Favicon

Selain untuk menginput file CSS, tag ini juga bisa dipakai untuk menginput favicon ke file HTML. **Favicon** adalah gambar kecil yang biasanya dilihat pada tampilan kecil di tab web browser ketika mengunjungi sebuah website.

berikut contoh penerapan-nya

```html
<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
```

## Alternate

Alternate digunakan untuk web khususnya berita karena web tersebut untuk RSS Feed, yah kegunaan-nya hanyalah untuk SEO dan user experience.

```html
<link rel="alternate" href="atom.xml" type="application/atom+xml" title="Atom">
```

## Import

Import digunakan untuk menampilkan halaman lain ke halaman yang bersangkutan, biasanya ini dipakai jika memiliki 2 halaman yang ingin dijadikan satu halaman.

```html
<link rel="import" href="component.html">
```

## Manifest

Manifest digunakan untuk menjadikan web kita dapat dimuat dengan mobile. Intinya itu web kita bisa seperti aplikasi kebanyakan kek gitu. Tapi ini rada rumit karena menggunakan teknik PWA.

```html
<link rel="manifest" href="manifest.json">
```