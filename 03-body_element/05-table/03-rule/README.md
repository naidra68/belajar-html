# Table Rule

Atribut `rule` ini digunakan untuk mengatur garis tepi atau border pada table secara spesifik pada document HTML.

Atribut ini memiliki nilai seperti `cols`, `rows`, `none`, `all`. Masing-masing nilai ini memiliki fungsi masing-masing.

- **Cols** digunakan untuk mengatur kolom.
- **Rows** digunakan untuk mengatur baris
- **None** digunakan untuk menghapus aturan rule.
- **All** digunakan untuk mengatur baris dan kolom.

berikut contoh penerapan-nya

```html
<h4>rules rows</h4>
<table rules="rows">
    <tr>
        <td>Judul 1</td>
        <td>Judul 2</td>
    </tr>
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h4>rules cols</h4>
<table rules="cols">
    <tr>
        <td>Judul 1</td>
        <td>Judul 2</td>
    </tr>
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h4>rules all</h4>
<table rules="all">
    <tr>
        <td>Judul 1</td>
        <td>Judul 2</td>
    </tr>
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
</table>
<h4>rules none</h4>
<table rules="none" border="1">
    <tr>
        <td>Judul 1</td>
        <td>Judul 2</td>
    </tr>
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