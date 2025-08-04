# Table Structure

Untuk membuat sebuah tabel pada document HTML. setidaknya perlu 3 jenis element yakni `<table>`,`<tr>`, dan `<td>`.

Ketiga tag ini memiliki fungsi agar table dapat berjalan semestinya pada document HTML.

Tag `<table>` sudah pasti sebagai pembungkusnya. Tag `<tr>` digunakan untuk mengatur baris tabel-nya dan terakhir tag `<td>` digunakan untuk emngatur data didalamnya.

berikut contoh penerapan-nya

```html
<table>
    <tr>
        <td>Baris 1, Kolom 1</td>
        <td>Baris 1, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 2, Kolom 1</td>
        <td>Baris 2, Kolom 2</td>
    </tr>
    <tr>
        <td>Baris 3, Kolom 1</td>
        <td>Baris 3, Kolom 2</td>
    </tr>
</table>
```

Ketika dijalankan, terlihat bahwa isi dari table ini seperti membuat tulisan dengan tag `<p>`. Memang mirip karena tidak menggunakan atribut border yang membedakan antara table dan element lain.