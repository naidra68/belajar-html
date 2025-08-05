# Table Valign

Atribut ini digunakan untuk mengatur posisi isi content cell nya jika terdapat tinggi cell telah ditentukan.

Secara default, web browser memposisikan teks berada di tengah cell tabel. Untuk mengatur posisi ini maka atribut `valign` harus ditulis.

Untuk mengatur atribut ini dapat di taruh didalam tag `<tr>` atau bisa juga di taruh pada tag `<td>` untuk mengatur setiap cell secara terpisah.

Nilai yang dapat diisi atribut ini adalah `top`, `middle`, `bottom`, `baseline`.

berikut contoh penerapan-nya

```html
<h2>Valign</h2>
<table border="1">
    <tr height="100">
        <td>Baris 1, Kolom 1</td>
        <td valign="top">Baris 1, Kolom 2</td>
        <td valign="middle">Baris 1, Kolom 3</td>
        <td valign="bottom">Baris 1, Kolom 4</td>
        <td valign="baseline">Baris 1, Kolom 5</td>
    </tr>
    <tr height="50" valign="bottom">
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
        <td>Baris 2, Kolom 3</td>
        <td>Baris 2, Kolom 4</td>
        <td>Baris 2, Kolom 5</td>
    </tr>
</table>
```