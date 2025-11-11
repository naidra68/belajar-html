# Form Label

Sesuatu yang dapat membuat tag `checkbox` dapat di klik dimanapun selain di kolom-nya adalah dengan cara menggunakan tag `<label>`. Tag ini memiliki fungsi memberikan label kepada tag yang di dalam-nya. Agar tag ini dapat berfungsi, maka diperlukan atribut tambahan didalam tag `<label>` yaitu `for` dan juga tag input type `checkbox` yaitu `id`.

Atribut `for` memiliki fungsi identitas pada tag `label`-nya dan tag `id` pada input type `checkbox` sebagai target identitas-nya. Untuk lebih jelas-nya daripada membingungkan, berikut contoh penulisan lengkap kode-nya.

```html
<form action="proses.php" method="get">
    <p><label for="HTML"><input type="checkbox" name="target1" value="HTML" id="HTML"> Menguasai HTML</label></p>
    <p><label for="CSS"><input type="checkbox" name="target2" value="CSS" id="CSS"> Paham CSS</label></p>
    <p><label for="PHP"><input type="checkbox" name="target3" value="PHP" id="PHP"> Jago PHP</label></p>
    <p><input type="submit" value="Kirim Data"></p>
</form>
```

