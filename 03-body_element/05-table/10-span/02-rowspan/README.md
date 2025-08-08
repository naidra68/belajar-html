# Table Rowspan

Berbeda dengan atribut `colspan` yang menggabungkan cell dalam bentuk kolom, atribut `rowspan` akan menggabungkan cell dalam bentuk baris.

berikut contoh penerapan-nya

```html
<table border="1">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
        <td>Baris 1, Kolom 3</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
        <td>Baris 2, Kolom 3</td>
    </tr>
    <tr>
        <td rowspan="2"> Baris 3 & 4, Kolom 1</td>
        <td rowspan="2"> Baris 3 & 4, Kolom 1</td>
        <td> Baris 3, Kolom 3</td>
    </tr>
    <tr>
        <td> Baris 4, Kolom 3</td>
    </tr>
</table>
```