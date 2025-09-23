    Nama: Anggriani Hermawan
    NIM: 312410175
    Kelas: TI.24.A2
    Mata Kuliah: Pemrograman Web 1
        
    #Praktikum1
    Soal
    1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
    error ketika terjadi kesalahan penulisan tag?
    2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
    3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
    4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
    proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
    5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
    _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
    Jawaban
    1. Sebenernya tidak akan terjadi error kalau misalnya terjadi kesalahan penulisan tag di HTML, karena browser akan tetap mencoba menampilkan meskipun ada tag yang           salah. Tetapi tampilannya tidak akan sesuai seperti yang di harapakan. 
    2. Tag <p> digunakan untuk membuat paragraf baru, sedangkan Tag <br> berfungsi memecah baris di dalam teks tanpa membentuk paragraf baru. Jadi perbedaannya, <p>             mengatur struktur teks, sedangkan <br> lebih ke tata letak baris.
    3. Atribut alt berfungsi sebagai teks alternatif jika gambar tidak bisa ditampilkan juga penting untuk aksesibilitas (screen reader) dan SEO. Sedangkan atribut title        memberikan informasi tambahan berupa tooltip ketika kursor diarahkan ke gambar. Jadi perbedaannya, alt menggantikan isi gambar, sementara title hanya menambahkan            keterangan.
    4. Supaya gambar tetap proporsional cukup mengisi salah satu atribut width atau height. Jika keduanya diisi manual tanpa perbandingan rasio asli, gambar bisa terlihat       gepeng atau melebar.
    5.- _blank → membuka link di tab/jendela baru.
      - _self → membuka link di tab/jendela yang sama (default).
      - _top → membuka link di jendela utama, menimpa semua frame.
      - _parent → membuka link di frame induk satu level di atas frame aktif.

    Screenshot setiap perubahannya.
    1. Membuat Paragraf  
    code:
    <!-- Ini adalah paragraf pertama -->
    <p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
    Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
    HTML.</p>
    <!-- Ini adalah paragraf kedua -->
    <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
    mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
    tag dasar html.</p>
    output:
<img width="1919" height="351" alt="Cuplikan layar 2025-09-22 135636" src="https://github.com/user-attachments/assets/d9c6d5cf-d243-4074-8d04-9b6d0ad56a03" />

    Penjelasan:
    - Tag <p> digunakan untuk membuat sebuah paragraf dalam HTML.
    - Setiap teks yang ada di dalam <p>...</p> akan ditampilkan sebagai satu blok paragraf.
    - Paragraf pertama berisi pengenalan materi, sedangkan paragraf kedua berisi penjelasan tambahan.
    - Komentar <!-- ... --> hanya untuk catatan dan tidak tampil di browser.
    
    2. Menambahkan Judul
    code:
    <!-- judul paragraf pertama -->
    <h1>Belajar Dasar HTML</h1>
    <!-- judul paragraf kedua -->
    <h2>Paragraf pada HTML</h2>
    output:
<img width="1900" height="517" alt="Cuplikan layar 2025-09-22 140716" src="https://github.com/user-attachments/assets/e633990b-8446-4b88-ab37-4ef58a399153" />

    Penjelasan:
    - Tag <h1> sampai <h6> digunakan untuk membuat heading (judul) dengan tingkat hierarki berbeda.
    - <h1> adalah judul utama (paling besar), <h2> subjudul, dan seterusnya hingga <h6> (paling kecil).
    - Dalam contoh ini, <h1> dipakai untuk judul utama “Belajar Dasar HTML”, lalu <h2> untuk subjudul “Paragraf pada HTML”.
    
    3. Memformat teks
    code:
    <!-- judul paragraf pertama -->
    <h1>Belajar Dasar HTML</h1>
    <p align="justify">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    rag-rag dasar HTML.</p>
    <!-- judul paragraf kedua -->
    <h2>Paragraf pada HTML</h2>
    <!-- Ini adalah paragraf kedua-->
    <p align="left">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehungga menjadi satu kesatuan. Pragraf dibuat
    dengan menggunakan tag dasar html.</p>
    output:
<img width="1919" height="493" alt="Cuplikan layar 2025-09-22 141837" src="https://github.com/user-attachments/assets/77085dda-bb2f-46ad-adb2-7e67cf78e66c" />

    Penjelasan:
    - align="justify" membuat paragraf rata kanan-kiri.
    - <mark> → memberi highlight kuning pada teks.
    - <b> → membuat teks tebal (bold).
    - <i> → membuat teks miring (italic).
    - <u> → memberi garis bawah pada teks.
    - Hasilnya: teks menjadi lebih bervariasi dan mudah dibaca.
    
    4. Menyisipkan Gambar
    code:
    <!-- sub judul paragraf -->
    <h3>Menambahkan Gambar</h3>
    <!-- menambahkan gambar pada dokumen -->
    <img src="Logo-Universitas-Pelita-Bangsa.png" width="200" "Logo Universitas Pelita Bangsa">
    output:
<img width="1919" height="754" alt="Cuplikan layar 2025-09-22 170309" src="https://github.com/user-attachments/assets/dc58c12c-a4b5-44f7-a610-20dc3d55d0c4" />

    Penjelasan:
    - Tag <img> digunakan untuk menampilkan gambar.
    - src → lokasi file gambar.
    - width="200" → mengatur ukuran lebar gambar (dalam piksel).
    - title → teks yang muncul saat kursor diarahkan ke gambar.
    - alt → teks alternatif jika gambar tidak bisa ditampilkan.
    - Judul <h3> digunakan untuk memberi label pada bagian gambar.
    
    5. Menambahkan Hyperlink
    code:
    <!-- menambahkan link navigasi -->
    <nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
    output:
<img width="1919" height="857" alt="Cuplikan layar 2025-09-22 171113" src="https://github.com/user-attachments/assets/554121ec-dc3d-4a60-b389-1ca3ec3f8e49" />

    Penjelasan:
    - Tag <a> digunakan untuk membuat link.
    - href → alamat tujuan link.
    - Bisa diarahkan ke file lokal (lab1_halaman2.html) atau web eksternal (google.com).
    - target="_blank" → membuka link di tab baru.
    - Tag <nav> dipakai untuk membungkus link navigasi.
    - <hr> menambahkan garis horizontal sebagai pemisah.
    
    HASIL KESELURUHAN
    code:
    <!DOCTYPE html>
    <html>
    <head>
    <title>Tag HTML Dasar</title>
    </head>
    <body>
    
    </body>
    </html>
    <!-- menambahkan link navigasi -->
    <nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
    <!-- judul paragraf pertama -->
    <h1>Belajar Dasar HTML</h1>
    <p align="justify">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    rag-rag dasar HTML.</p>
    <!-- judul paragraf kedua -->
    <h2>Paragraf pada HTML</h2>
    <!-- Ini adalah paragraf kedua-->
    <p align="left">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehungga menjadi satu kesatuan. Pragraf dibuat
    dengan menggunakan tag dasar html.</p>
    <!-- sub judul paragraf -->
    <h3>Menambahkan Gambar</h3>
    <!-- menambahkan gambar pada dokumen -->
    <img src="Logo-Universitas-Pelita-Bangsa.png" width="200" "Logo Universitas Pelita Bangsa">
    
    output:
<img width="1919" height="857" alt="Cuplikan layar 2025-09-22 171113" src="https://github.com/user-attachments/assets/a8b633ab-306f-445c-ab8f-693f5e0a062e" />



    
