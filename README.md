# CSS Layout

Praktikum 4 merupakan latihan pemrograman web yang membahas pembuatan tata letak (*layout*) halaman website menggunakan HTML5 dan CSS. Pada praktikum ini, dipelajari konsep **Box Element, CSS Float, Clearfix**, serta penggunaan elemen semantik HTML5 untuk membangun layout website sederhana yang terstruktur dan mudah dipahami.

## Result

![Gambar 1](screenshot/ss1.png)

Gambar 1 menunjukkan tampilan awal halaman sebelum diberikan styling CSS.

Hasil setelah diberikan style CSS:

## Result

![Gambar 2](screenshot/ss2.png)

Gambar 2 menunjukkan perubahan tampilan halaman setelah CSS diterapkan, seperti pengaturan jarak, ukuran, dan posisi elemen.

## 1. Box Element

Box Element merupakan konsep dasar CSS yang menjelaskan bahwa setiap elemen HTML tersusun atas beberapa bagian, yaitu:

- **Content:** bagian yang berisi teks, gambar, atau konten lainnya.
- **Padding:** jarak antara content dan border.
- **Border:** garis tepi yang mengelilingi elemen.
- **Margin:** jarak antara elemen dengan elemen lainnya.

Konsep ini digunakan untuk mengatur ukuran, jarak, dan posisi elemen agar tata letak halaman terlihat lebih rapi.

## 2. CSS Float Property

Properti `float` digunakan untuk mengatur posisi elemen agar berada di sisi kiri atau kanan container. Properti ini dapat digunakan untuk menyusun beberapa elemen secara berdampingan.

Contoh penggunaan CSS Float:

```css
div {
    float: left;
    padding: 10px;
}
```

Pada contoh tersebut, elemen `div` ditempatkan di sisi kiri dan diberikan jarak bagian dalam sebesar 10 piksel.

## 3. Clearfix

Clearfix digunakan untuk mengatasi masalah tata letak ketika elemen di dalam container menggunakan `float`, sehingga container tetap dapat menyesuaikan tinggi elemen di dalamnya. Sementara itu, properti `clear` digunakan untuk mencegah elemen berikutnya berada di samping elemen yang di-*float*.

Contoh kode CSS:

```css
.div4 {
    background-color: blue;
    clear: both;
    float: none;
}
```

Pada contoh tersebut, elemen `.div4` memiliki latar belakang biru, tidak menggunakan `float`, dan ditempatkan setelah elemen yang menggunakan `float` di kedua sisi.

## Result

![Gambar 3](screenshot/ss3.png)

Gambar 3 menunjukkan hasil penerapan Box Element, Float, dan Clear pada tata letak halaman.

# Membuat Layout Sederhana

Pada tahap ini, dilakukan pembuatan layout website sederhana menggunakan HTML5 dan CSS. Halaman dibagi menjadi beberapa bagian, seperti header, navigasi, hero panel, widget, konten utama, artikel, dan footer.

## Result

![Gambar 4](screenshot/ss4.png)

Gambar 4 menunjukkan tampilan halaman `home.html` sebelum atau pada tahap awal penerapan styling CSS.

Hasil setelah diberikan style CSS pada halaman `home.html`:

## Result

![Gambar 5](screenshot/ss5.png)

Gambar 5 memperlihatkan tampilan navigasi setelah diberikan styling CSS. Pengaturan ini bertujuan agar menu terlihat lebih rapi dan memudahkan pengguna berpindah antarhalaman.

## Result

![Gambar 6](screenshot/ss6.png)

Gambar 6 menunjukkan proses pembuatan panel hero. Panel hero merupakan bagian utama yang biasanya digunakan untuk menampilkan judul, deskripsi, gambar, atau informasi penting pada halaman website.

## Result

![Gambar 7](screenshot/ss7.png)

Gambar 7 memperlihatkan panel hero setelah diberikan styling CSS, seperti pengaturan warna, ukuran, jarak, dan tata letak agar tampilannya lebih menarik.

## Result

![Gambar 8](screenshot/ss8.png)

Gambar 8 menunjukkan tampilan widget setelah diberikan styling CSS. Widget digunakan untuk menampilkan informasi atau elemen tambahan yang mendukung konten utama website.

## Result

![Gambar 9](screenshot/ss9.png)

Gambar 9 menunjukkan tampilan footer setelah diatur menggunakan CSS. Footer merupakan bagian bawah halaman yang dapat berisi informasi hak cipta, identitas website, atau informasi pendukung lainnya.

## Result

![Gambar 10](screenshot/ss10.png)

Gambar 10 memperlihatkan hasil styling pada bagian konten utama (*main content*). Pada bagian ini, ditambahkan elemen-elemen berbentuk lingkaran yang diatur menggunakan CSS untuk memperjelas tampilan dan susunan konten.

## Result

![Gambar 11](screenshot/ss11.png)

Gambar 11 menunjukkan tampilan keseluruhan halaman `home.html` setelah penambahan artikel dan penerapan styling CSS. Setiap bagian halaman telah disusun untuk membentuk layout website yang lebih terstruktur.

## Result

![Gambar 12](screenshot/ss12.png)

![Gambar 13](screenshot/ss13.png)

Gambar 12 dan Gambar 13 merupakan hasil akhir praktikum yang memperlihatkan tampilan halaman website setelah seluruh elemen HTML5 dan styling CSS diterapkan.

# Kesimpulan

Melalui Praktikum 4, dapat dipahami bahwa HTML5 berperan dalam membentuk struktur halaman website, sedangkan CSS digunakan untuk mengatur tampilan dan tata letaknya. Konsep Box Element membantu mengatur ukuran dan jarak elemen, CSS Float digunakan untuk mengatur posisi elemen, dan Clearfix membantu menangani tata letak yang melibatkan elemen *float*.

Dengan menerapkan konsep-konsep tersebut, halaman website sederhana dapat dibuat dengan struktur yang lebih teratur, tampilan yang lebih menarik, dan pembagian bagian halaman yang jelas.