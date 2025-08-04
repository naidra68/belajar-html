# Table Cellspacing

Atribut ini digunakan untuk mengatur jarak antar satu cell dengan cell yang lain. Nilai yang dapat diisi pada atribut ini berupa angka dengan satuan pixel.

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
<h4>cellspacing = 2</h4>
<table border="1" cellspacing="2">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h4>cellspacing = 6</h4>
<table border="1" cellspacing="6">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h4>cellspacing = 0</h4>
<table border="1" cellspacing="0">
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

Jika dilihat, terdapat sebuah table yang memiliki atribut `border` namun tidak ada cellspacing-nya. Jika diperhatikan secara seksama, terdapat juga sebuah table yang memiliki atribut `border` dan cellspacing sebesar `2`.

Hasilnya dari mereka berdua adalah sama, jadi bisa disimpulkan bahwa atribut `border` memiliki default cellspacing sebesar `2`.