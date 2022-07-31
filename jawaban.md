### Apa perbedaan antara static web server dan dynamic web server?
```js
1. Interaksi antara pengunjung dan pemilik web
Dalam web statis tidak dimungkinkan terjadinya interaksi antara pengunjung dengan pemilik web. Sementara dalam web dinamis terdapat interaksi antara pengunjung dengan pemilik web seperti memberikan komentar, transaksi online, forum, dll.
2. Bahasa Script yang digunakan
Web statis hanya menggunakan HTML, CSS, JS dan frameworknya saja. Sedangkan web dinamis menggunakan bahasa pemrograman web yang lebih kompleks.
3. Penggunaan Database
Web statis tidak menggunakan database karena tidak ada data yang perlu disimpan dan diproses. Sedangkan web dinamis menggunakan database seperti MySQL, Oracle, dll untuk menyimpan dan memroses data.
4. Konten
Konten dalam web statis hanya diberikan oleh pemilik web dan jarang di-update, sementara konten dalam web dinamis bisa berasal dari pengunjung dan lebih sering di-update. Konten dalam web dinamis bisa diambil dari database sehingga isinya pun bisa berbeda-beda walaupun kita membuka web yang sama.
```

### Jelaskan arsitektur static site dan dynamic site
```js
Static Site, client side meminta http request kemudian diterima oleh web server
    dimana terdapat file seperti html css javascript, dan responese yang ditampilkan
    hanya berupa file file tadi. tidak ada processing data di webserver
Dynamic site, Client side meminta GET request dan akan masuk ke web server
    dan selanjutnya masuk ke dalam web application. kemudian didalam web application
    dilakukan processing data dari database dan akan dibawa ke web server
    dan dilakukan response sehingga tampilah di dalam browser.
```

### Apa saja yang dapat kita buat pada sisi server?
```js
Simpan informasi sesi/status.
Pengalaman pengguna yang disesuaikan.
Penyimpanan dan pengiriman informasi yang efisien.
Akses terkontrol ke konten.
Pemberitahuan dan komunikasi.
Analisis data. 
```

### Mohon jelaskan apa itu RESTful?
```js
RESTful : Sebuah jenis layanan web API yang menggunakan REST, atau Representational State Transfer. REST adalah gaya arsitektur untuk sistem hypermedia yang digunakan untuk World Wide Web.
```

### Apa saja jenis HTTP verbs yang ada (jelaskan fungsinya masing-masing)
```js
GET, menyediakan hanya akses baca pada resource
PUT, digunakan untuk menciptakan resource baru
DELETE, digunakan untuk menghapus resource
POST, digunakan untuk memperbarui resource yang ada atau membuat resource baru
OPTIONS, digunakan untuk mendapatkan operasi yang disupport pada resource
```

### Apa fungsi dari Response Codes?
```js
Kode respons standar yang diberikan oleh server website di internet.
Kode ini membantu mengidentifikasi penyebab masalah saat laman website atau sumber daya lain tidak dimuat dengan benar.
```
