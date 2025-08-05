# Table Align

Secara default, tabel ditampilkan pada baris baru ketika dijalankan dan ini seperti block level element. Untuk mengatur agar tabel dapat diubah posisi-nya maka menggunakan atribut ini adalah yang paling cocok.

Atribut ini dapat diisi nilai `left`, `center`, dan `right`.

berikut contoh penerapan-nya

```html
<table border="1" wdth="300" align="right">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nulla illo doloribus vel molestiae atque aliquam. Commodi earum totam corrupti soluta minus explicabo dolores deleniti eum accusamus? Voluptatem nihil enim quos.</p>
<table border="1" wdth="300" align="left">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi incidunt aliquam, enim soluta perspiciatis nisi id velit tenetur nulla fuga! Eligendi dolorum molestias autem non vitae omnis aperiam est natus?</p>
<table border="1" wdth="300" align="center">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<br><br>
<hr>
<br><br>
<table border="1" wdth="300" style="float: right;">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nulla illo doloribus vel molestiae atque aliquam. Commodi earum totam corrupti soluta minus explicabo dolores deleniti eum accusamus? Voluptatem nihil enim quos.</p>
<table border="1" wdth="300" style="float: left;">
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi incidunt aliquam, enim soluta perspiciatis nisi id velit tenetur nulla fuga! Eligendi dolorum molestias autem non vitae omnis aperiam est natus?</p>
<table border="1" wdth="300" style="margin: auto;">
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

Selain itu, untuk mengatur posisi isi konten dari table tersebut, dapat mengubah atribut `align` nya dari yang awalnya didalam `<table>` ke dalam `<td>`.

```html
<h3>align in cell table</h3>
<table border="1" width="350">
    <tr>
        <td align="left">Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum repellat, dolorum odio quisquam, quia quam nam, blanditiis soluta neque cumque tempore velit eius? Nam provident veritatis atque. Adipisci, magni in?</td>
    </tr>
    <tr>
        <td align="center">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Accusamus ab eos doloremque vero iusto, ex atque enim, ut amet laborum, eius quo suscipit repudiandae mollitia blanditiis unde aliquid incidunt earum.</td>
    </tr>
    <tr>
        <td align="right">Lorem ipsum dolor sit amet consectetur adipisicing elit. Saepe laborum harum repellat debitis aspernatur! Temporibus iste ipsam, dicta reprehenderit rem obcaecati itaque harum commodi fuga hic cumque quaerat repellendus eaque.</td>
    </tr>
</table>
```