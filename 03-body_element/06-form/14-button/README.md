# Form Button

Selain menggunakan input type `button`, kita juga bisa gunakan tag `<button>` dimana memiliki fungsi yang hampir mirip. Perbedaan-nya pada perilaku masing-masing tag. Biasanya tag `<button>` ini digunakan berbarengan dengan kode javascript sebagai validasi form.

Validasi form berfungsi untuk menentukan apakah form yang diisi oleh user sesuai aturan atau ketentuan atau tidak. Meskipun input type `button` juga bisa digunakan berbarengan dengan kode javascript, namun tag `<button>` lebih dominan digunakan.

berikut contoh penulisan-nya secara singkat dengan form

```html
<form action="proses.php" method="get">
    <p>Nama : <input type="text" name="nama_user"></p>
    <p>Password : <input type="password" name="password_user"></p>
    <p><button name="kirim">Cek Data</button></p>
</form>
```

Jika dijalankan, normal dan sama seperti input type `button`. Perbedaan yang paling mencolok adalah penamaan tombol itu sendiri. Dimana input type `button` untuk penulisan nama tombol custom harus menggunakan atribut `value` sedangkan tag `<button>` ini tidak perlu, karena memiliki penutup tag.

Selanjutnya, kita coba berikan validasi dengan javascript meskipun ini tidak bisa dibilang validasi, namun hanya sebagai contoh agar mengerti cara penerapan-nya. Berikut contoh penulisan kode-nya.

```html
<form action="proses.php" method="get">
    <p>Nama : <input type="text" name="nama_user"></p>
    <p>Password : <input type="password" name="password_user"></p>
    <p><button name="kirim" onclick="alert('Username dan Password tidak sama')">Cek Data</button></p>
</form>
```

Saat dijalankan, ketika user klik tombol Cek Data, maka akan tampil pop up seperti kode-nya, hal ini bisa terjadi karena terdapat kode javscript berupa `onlick`. Lebih lanjut untuk javascript kita pelajari ketika sudah masuk ke javascript.

