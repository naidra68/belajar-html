# Table Cellpadding

Atribut ini digunakan untuk mengatur jarak antara garis tepi dan isi konten didalam cell itu sendiri. Nilai yang dapat diisi pada atribut ini adalah angka dalam satuan pixel.

berikut contoh penerapan-nya

```html
<h4>border 1</h4>
<table border="1">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h4>cellpadding = 1</h4>
<table border="1" cellpadding="1">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h4>cellpadding = 6</h4>
<table border="1" cellpadding="6">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h4>cellpadding = 0</h4>
<table border="1" cellpadding="0">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
```

Jika dilihat secara seksama, atribut border juga memiliki default cellpadding yang bernilai sebesar `1`.