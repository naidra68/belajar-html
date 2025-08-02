# Audio

Sesuai dengan nama-nya, tag ini akan menjalankan file audio dan apapun jenis extensi file-nya yang merujuk kepada audio maka bisa menggunakan tag ini.

berikut contoh penulisan-nya

```html
<p>Audio without controls</p>
<p><audio src="../lagu.mp3"></audio></p>
```

Apakah sudah selesai? Jelas belum, ketika dijalankan, maka tidak akan tampil apa=apa pada web browser.

Untuk menjalankan atau melihat apakah audio ini dapat bekerja atau tidak maka harus menggunakan atribut controls.

## Controls

Atribut ini digunakan untuk mengontrol tag audio agar dapat digunakan semestinya.

berikut contoh penerapan-nya

```html
<!-- Audio with controls -->
<p>Audio with controls</p>
<p><audio src="../lagu.mp3" controls></audio></p>
```

Selain atribut controls, terdapat atribut lain yang bisa dipakai. Atribut tersebut ada yang biasanya digunakan dan ada yang jarang digunakan.

## Autoplay

Atribut ini digunakan untuk membuat sebuah tag file audio akan otomatis diputar ketika website dimuat.

Penggunaan atribut ini jarang dipakai untuk sekarang karena terkesan mengganggu bagi pengunjung website.

berikut contoh penerapan-nya

```html
<!-- Audio with controls autoplay -->
<p>Audio with controls autoplay</p>
<p><audio src="../lagu.mp3" controls autoplay></audio></p>
```

## Loop

Atribut ini digunakan untuk memutar ulang otomatis file audio ketika telah selesai diputar pada website.

berikut contoh penerapan-nya

```html
<!-- Audio with controls loops-->
<p>Audio with controls loops</p>
<p><audio src="../lagu.mp3" controls loop></audio></p>
```

## Muted

Atribut ini digunakan untuk meredam file audio ketika pertama kali website dimuat.

berikut contoh penerapan-nya

```html
<!-- Audio with controls muted-->
<p>Audio with controls muted</p>
<p><audio src="../lagu.mp3" controls muted></audio></p>
```

## Preload

Atribut ini digunakan untuk memberitahu web browser bahwa bagaimana sebuah file audio akan di jalankan pertama kali atau bisa disebut juga dengan men-buffer file audio-nya.

Hal ini akan sangat berpengaruh ketika sudah membuat website yang memiliki audio karena saat user akan membuka audionya, maka web browser akan melakukan download sebagian kecil file nya tergantung dari isi atribut preload.

berikut contoh penerapan-nya

```html
<!-- Audio with controls preload none-->
<p>Audio with controls preload none</p>
<p><audio src="../lagu.mp3" controls preload="none"></audio></p>

<!-- Audio with controls preload auto-->
<p>Audio with controls preload auto</p>
<p><audio src="../lagu.mp3" controls preload="auto"></audio></p>

<!-- Audio with controls preload meta-->
<p>Audio with controls preload meta</p>
<p><audio src="../lagu.mp3" controls preload="meta"></audio></p>
```

1. `auto` : Mengintruksikan web browser bahwa download seluruh file audio saat website pertama kali ditampilkan terlepas dari file audio-nya diputar atau tidak.

2. `none` : Menginstruksikan web browser bahwa untuk tidak mendownload seluruh file audio sampai user mengklik tombol putar audio-nya.

3. `meta` : Menginstruksikan web browser bahwa download sedikit file audio saat website pertama kali ditampilkan dan akan beranjut jika user memutar file audio-nya.