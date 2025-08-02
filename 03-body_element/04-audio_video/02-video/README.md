# Video

Sesuai dengan nama-nya, tag ini akan menjalankan file video dan apapun jenis extensi file-nya yang merujuk kepada video maka bisa menggunakan tag ini.

berikut contoh penulisan-nya

```html
<!-- Audio without controls -->
<!-- (tidak tampil apa-apa dan tidak bisa diapa-apain)  -->
<p>Video without controls</p>
<p><video src="video.mp4" width="300"></video></p>
```

Sama seperti Audio, tanpa menggunakan atribut controls. tag Video ini tidak akan menampilkan apa-apa dan tidak dapat diputar video-nya.

## Controls

Atribut ini digunakan untuk mengontrol tag video agar dapat digunakan semestinya.

berikut contoh penerapan-nya

```html
<!-- Audio with controls -->
<p>Video with controls</p>
<p><video src="video.mp4" controls width="300"></video></p>
```

## Autoplay

Atribut ini digunakan untuk membuat sebuah tag file video akan otomatis diputar ketika website dimuat.

Penggunaan atribut ini jarang dipakai untuk sekarang karena terkesan mengganggu bagi pengunjung website.

berikut contoh penerapan-nya

```html
<!-- Audio with loop -->
<p>Video with loop</p>
<p><video src="video.mp4" controls loop width="300"></video></p>
```

## Loop

Atribut ini digunakan untuk memutar ulang otomatis file video ketika telah selesai diputar pada website.

berikut contoh penerapan-nya

```html
<!-- Audio with loop -->
<p>Video with loop</p>
<p><video src="video.mp4" controls loop width="300"></video></p>
```

## Muted

Atribut ini digunakan untuk meredam file video ketika pertama kali website dimuat.

berikut contoh penerapan-nya

```html
<!-- Video with controls muted-->
<p>Video with controls muted</p>
<p><video src="video.mp4" controls muted width="300"></video></p>
```

## Preload

Atribut ini digunakan untuk memberitahu web browser bahwa bagaimana sebuah file video akan di jalankan pertama kali atau bisa disebut juga dengan men-buffer file video-nya.

Hal ini akan sangat berpengaruh ketika sudah membuat website yang memiliki video karena saat user akan membuka video-nya, maka web browser akan melakukan download sebagian kecil file nya tergantung dari isi atribut preload.

berikut contoh penerapan-nya

```html
<!-- Video with controls preload none-->
<p>Video with controls preload none</p>
<p><video src="video.mp4" controls preload="none" width="300"></video></p>

<!-- Video with controls preload auto-->
<p>Video with controls preload auto</p>
<p><video src="video.mp4" controls preload="auto" width="300"></video></p>

<!-- Video with controls preload meta-->
<p>Video with controls preload meta</p>
<p><video src="video.mp4" controls preload="meta" width="300"></video></p>
```

1. `auto` : Mengintruksikan web browser bahwa download seluruh file video saat website pertama kali ditampilkan terlepas dari file video-nya diputar atau tidak.

2. `none` : Menginstruksikan web browser bahwa untuk tidak mendownload seluruh file video sampai user mengklik tombol putar video-nya.

3. `meta` : Menginstruksikan web browser bahwa download sedikit file video saat website pertama kali ditampilkan dan akan beranjut jika user memutar file video-nya.

## Poster

atribut ini digunakan untuk menampilkan gambar placeholder sebelum video dijalankan. Kalau di youtube ini bisa disebut sebagai thumbnail video. Atribut ini dapat diisi oleh URL gambar-nya.

berikut contoh penerapan-nya

```html
<!-- Video poster -->
<p>Video poster</p>
<p><video src="video.mp4" controls width="300" poster="poster.jpg"></video></p>
```