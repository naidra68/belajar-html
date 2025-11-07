# Input Reset

Terkadang setelah kita mengisi dan mengirim data-nya ke server, tulisan yang telah kita ketik sebelumnya masih ada. Untuk menghilangkan atau menghapus semua isian data maka kita bisa menggunakan type `reset` ini.

berikut contoh penulisan bersama-an dengan type `submit`.

```html
<input type="submit" value="Kirim Data">
<input type="reset" value="Kosongkan Form">
```

Perlu diingatkan bahwa type `reset` ini bersifat tombol seperti type `submit`. Maka dari itu, kita berikan attribut `value` agar ada custom tulisan ada tombol-nya.

berikut penulisan secara lengkap dengan tag `form`.

```html
<form action="proses.php" method="get" target="_blank">
    <p>Nama : <input type="text" name="name_user"></p>
    <p>Alamat: <input type="text" name="alamat_user"></p>
    <p>
        <input type="submit" value="Kirim Data">
        <input type="reset" value="Kosongkan Form">
    </p>
</form>
```