# Anchor Element

Untuk membuat sebuah teks dapat di klik oleh pengguna maka diperlukan Anchor tag. Penulisan tag ini cukup simple karena hanya menulis `<a>` saja.

Untuk membuat sebuah link teks yang dapat diklik membutuhkan 1 hal yaitu alamat link nya harus didefinisikan.

berikut contoh penerapan-nya

```html
<p>
    <a href="#">Text ini bisa di klik</a>
</p>
```

Tag `<a>` ini masuk kedalam kelompok **inline level element** dimana dia akan tampil mengikuti element sebelum atau setelahnya dan tidak akan membuat baris baru.

## href

Contoh diatas telah melihatkan bahwa sebuah tag `<a>` harus memiliki atribut `href`. Atribut ini digunakan untuk menentukan lokasi atau URL jika link telah di klik.

Terdapat 2 link yang bisa diisi didalah atribut ini yaitu **Link Absolut** dan **Link Relatif**.

Link Absolut adalah alamat URL seperti contoh nya google, facebook, dan lain-lain

berikut contoh penerapan-nya

```html
<p><a href="https://www.google.com/">Google</a></p>
<p><a href="https://www.facebook.com/">Facebook</a></p>
```

Sedangkan Link Relatif adalah alamat relatif seperti struktur folder ataupun link yang lebih spesifik.

berikut contoh penerapan-nya

```html
<p><a href="README.md">Menuju ke Readme</a></p>
```

## target

Atribut ini yang sering digunakan jika berurusan dengan teks link karena sangat berguna.  Isi dari atribut ini ada beberapa, namun coba menggunakan isi yang biasanya digunakan kebanyakan programmer saja.

berikut contoh penerapan-nya

```html
<p><a href="#" target="_blank">Text ini bisa di klik dan tampil ditab berikutnya</a></p>
```

## rel

Atribut ini berfungsi untuk memberitahukan ke web browser bahwa link yang akan dituju berhubungan dengan halaman terkait.

Atribut `rel` tidak akan nampak hasilnya karena hanya untuk web browser. Isi dari atribut ini ada banyak.

Sebenarnya, atribut ini dipakai untuk SEO. SEO sendiri sebuah teknik untuk mengoptimalkan website yang telah dibuat agar dapat terlacak oleh mesin pencarian.

Untuk pembelajaran HTML, bisa skip untuk menambahkan atribut ini.

berikut contoh penerapan-nya

```html
<p><a href="https://www.facebook.com/" rel="nofollow">Facebook</a></p>
```