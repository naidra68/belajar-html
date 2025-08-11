# Semantic Tag Table

Perkembangan HTML saat ini cukup pesat dan cepat, maka dari itu penggunaan semantic tag khusus untuk tag table harus dilakukan agar website yang telah dibuat dapat ditampilkan oleh search engine.

Untuk tag table ini memiliki 3 semantic tag yang dibagi menjadi 3 yaitu pada judul, isi, dan penutup.

berikut ini table dari ketiga tag tersebut

|  No  |       Nama      |      Tag      |
|:----:| :-------------: | :---------:   |
|  01  | Judul Table     | ```<thead>``` |
|  02  | Isi Table       | ```<tbody>``` |
|  03  | Penutup Table   | ```<tfoot>``` |


berikut contoh penerapan dari ketiga tag tersebut

```html
<table border="1">
    <thead>
        <tr>
            <th>No</th>
            <th>Nama Peserta</th>
            <th>Alamat</th>
            <th>Simpanan</th>
        </tr>
    </thead>
    <tfoot>
        <tr>
            <td></td>
            <td>Total</td>
            <td>---</td>
            <td>400.000</td>
        </tr>
    </tfoot>
    <tbody>
        <tr>
            <td>1</td>
            <td>Hadi Winarto</td>
            <td>Jl. Merdeka No.12</td>
            <td>150.000</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Sukim Hariatun</td>
            <td>Jl. Soekarno No.18</td>
            <td>250.000</td>
        </tr>
    </tbody>
</table>
```

Apabila dijalankan, terlihat bahwa tidak ada efek apapun ada tag tersebut, ini dikarenakan tag tersebut hanyalah semantic tag yang dapat dibaca oleh bot search engine.

Namun, jika diperhatikan ada suatu hal menarik dari kode diatas yaitu, tag `<tbody>` berada dibawah tag `<tfoot>`, secara logika maka hasilnya pasti element tag `<tbody>` akan berada dibawah. Namun hal tersebut tidak terjadi dan tetap seperti semula. Disinilah letak fungsi kecilnya dari semantic tag ini.