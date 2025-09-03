# Textbox maxlength

Sesuai dengan nama-nya, atribut ini berfungsi untuk tidak memberikan akses user pada inputan form. Berbeda dengan `readonly` yang dapat berinteraksi dengan inputan form dan dapat di klik, atribut `disabled` tidak bisa di klik dan tampilan inputan form-nya akan berwarna abu-abu.

berikut contoh penerapan-nya

```html
<form action="form.php" method="get">
    <p>Nama : <input type="text" name="nama" value="Tri Ardian" disabled></p>
    <p>Kelas : <input type="text" name="kelas" value="12" disabled></p>
</form>
```

Apabila dijalankan, terlihat bahwa semua inputan tidak bisa di klik dan diapa-apakan karena statusnya sudah dinonaktifkan.