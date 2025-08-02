# Figure and Figcaption

Dua tag ini masih berhubungan dengan tag `<img>`. Tag ini berfungsi sebagai container bagi satu atau beberapa tag `<img>`.

Biasanya, tag figcaption akan ditempatkan setelah didefinisikan tag image.

berikut contoh penerapan-nya

```html
<figure>
    <figcaption>Suasana Bundaran HI Jakarta pada saat Car Free Day</figcaption>
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" width="300">
</figure>
<figure>
    <img src="Istiqlal_Mosque_Monas.jpg" alt="Masjid Istiqlal" width="300">
    <figcaption>Mesjid Istiqlal Jakarta</figcaption>
</figure>
<!-- Beberapa gambar dalam satu figure -->
<figure>
    <img src="Bundaran_HI.jpg" alt="Bundaran HI" width="300">
    <img src="Istiqlal_Mosque_Monas.jpg" alt="Masjid Istiqlal" width="300">
    <img src="Bus_TransJakarta.jpg" alt="Bus Transjakarta" width="300">
    <figcaption> Gambar seputaran Jakarta, diambil dari
        <a href="http://en.wikipedia.org/wiki/Jakarta">wikipedia</a>
    </figcaption>
</figure>
```