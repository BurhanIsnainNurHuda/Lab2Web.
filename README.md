# Praktikum Lab2Web.

    Nama: Burhan Isnain Nur Huda 
    NIM: 312410266 
    Kelas: TI.24.A.2
    Mata Kuliah: Pemograman Web 1

Repositori ini adalah hasil praktikum Pemrograman Web 1 tentang **CSS dasar** dengan tema **Blockchain & Crypto**.  
Di dalamnya terdapat file:
 `index.html` → struktur HTML
 `style.css` → styling CSS
 Screenshot hasil website

 Jawaban Pertanyaan & Tugas

### 1. Eksperimen Mengubah dan Menambah Properti CSS
Kami mengubah beberapa properti CSS berdasarkan **CSS Cheat Sheet**:
 Mengganti warna background menjadi **dark aesthetic** (linear-gradient).
 Menambahkan **box-shadow** dan **border-radius** pada elemen.
 Menambahkan **hover effect** pada list coin.
 Mengubah warna coin sesuai identitas aslinya:
   BTC → Orange
   ETH → Abu-Abu
   SOL → Ungu
   BNB → Kuning (text hitam)
   XRP → Hitam
 Menambahkan **motivational quotes** di atas dan bawah konten.

### 2. Perbedaan `h1 {…}` dengan `#intro h1 {…}`
 `h1 {…}` → Mengatur semua elemen `<h1>` di seluruh halaman HTML.
 `#intro h1 {…}` → Hanya mengatur `<h1>` yang berada di dalam elemen dengan **id="intro"**.  
Contoh:

    <h1>Ini kena style umum</h1>
    <div id="intro">
    <h1>Ini kena style khusus intro</h1>
    </div>
    Jadi selector #intro h1 lebih spesifik dibanding h1.

### 3. Prioritas CSS (Inline, Internal, Eksternal)

Urutan prioritas: Inline CSS > Internal CSS > External CSS

Artinya jika ada style yang sama, inline CSS akan menang.
Contoh:

    <style>
    p { color: blue; }  /* internal */
    </style>

    <link rel="stylesheet" href="style.css"> <!-- external -->

    <p style="color:red;">Teks ini berwarna merah</p> <!-- inline -->

