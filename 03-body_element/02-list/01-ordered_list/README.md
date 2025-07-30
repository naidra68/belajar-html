# Ordered List

Tag ini digunakan untuk membuat list yang menggunakan angka atau huruf sebagai penentu urutan.

Tag ini bagus digunakan untuk membuat daftar yang harus tersusun berdasarkan instruksi.

berikut contoh penerpan-nya

```html
<p>Cara membuat telur dadar: </p>
<ol>
    <li>Siapkan daun bawang serta daun seledri, lalu cuci bersih dan potong kecil-kecil.</li>
    <li>Kocok telur dalam wadah, masukan bumbu halus daun bawang, seledri dan garam secukupnya.</li>
    <li>Goreng telur pada wajan, tuangkan adonan pada tengah wajan dan goreng hingga matang.</li>
    <li>Balik adonan agar sisi atasnya juga ikut matang.</li>
    <li>Setelah kedua sisi matang, angkat, dan tiriskan.</li>
    <li>telur dadar siap disajikan.</li>
</ol>
```

Selain itu, list juga dapat dibuat dengan nested list. Dimana terdapat list didalam list.

berikut contoh penerapan-nya

```html
<!-- Nested list -->
 <ol>
    <li>Pilihan pertama</li>
    <li>Pilihan kedua
        <ol type="a">
            <li>sub pertama pilihan kedua</li>
            <li>sub kedua pilihan kedua</li>
            <li>sub ketiga pilihan kedua</li>
        </ol>
    </li>
    <li>Pilihan ketiga</li>
 </ol>
```