# Table Width and Height

Sesuai dengan nama-nya, kedua atribut ini digunakan untuk mengatur lebar dan tinggi table pada document HTML.

Perlu diperhatikan bahwa yang diatur lebar dan tinggi nya adalah cell pada table tersebut.

berikut contoh penerapan-nya

```html
<h3>border 1 default</h3>
<table border="1">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique quibusdam a sint, rerum modi ducimus saepe maxime illum facere nihil rem reiciendis repellat aliquam sed soluta perspiciatis. Quibusdam, accusamus quod!</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h3>width 300px</h3>
<table border="1" width="300">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique quibusdam a sint, rerum modi ducimus saepe maxime illum facere nihil rem reiciendis repellat aliquam sed soluta perspiciatis. Quibusdam, accusamus quod!</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h3>width 300px in table, 120px td, 180px td</h3>
<table border="1" width="300">
    <tr>
        <td width="120">Baris 1, Kolom 1</td>
        <td width="180">Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique quibusdam a sint, rerum modi ducimus saepe maxime illum facere nihil rem reiciendis repellat aliquam sed soluta perspiciatis. Quibusdam, accusamus quod!</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h3>width percent</h3>
<table border="1" width="50%">
    <tr>
        <td width="25%">Baris 1, Kolom 1</td>
        <td width="75%">Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Similique quibusdam a sint, rerum modi ducimus saepe maxime illum facere nihil rem reiciendis repellat aliquam sed soluta perspiciatis. Quibusdam, accusamus quod!</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<br><br>
<hr>
<br><br>
<h3>height 200</h3>
<table border="1" height="200">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h3>height 200px tr, 50px tr</h3>
<table border="1">
    <tr height="200">
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr height="50">
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
```