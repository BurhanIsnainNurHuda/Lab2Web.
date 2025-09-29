# Praktikum Lab2Web.

    Nama: Burhan Isnain Nur Huda 
    NIM: 312410266 
    Kelas: TI.24.A.2
    Mata Kuliah: Pemograman Web 1

 
# Deskripsi Singkat

Repositori ini adalah hasil praktikum Pemrograman Web 1 pada pertemuan Lab2Web. Website ini memakai tema `Blockchain & Crypto` dengan gaya dark aesthetic agar lebih modern. Tugas ini juga melatih penggunaan `HTML, CSS eksternal, ID vs Class selector,` serta memahami prioritas `CSS (inline, internal, eksternal).`


Di dalamnya terdapat file:
 `index.html` → struktur HTML
 `style.css` → styling CSS
dan Screenshot hasil website

# Jawaban Pertanyaan & Tugas

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
    Yang tampil di browser: merah (inline).

4. Jika Elemen Punya ID & Class

Selector ID lebih spesifik dibanding Class.

Jika ada style berbeda, style ID akan menang.

Contoh:

    <style>
    .text-paragraf { color: blue; } /* class */
    #paragraf-1 { color: red; }     /* ID */
    </style>

    <p id="paragraf-1" class="text-paragraf">Teks ini?</p>
    Hasilnya: merah karena ID #paragraf-1 menang.

### Penjelasan HTML

Header: menampilkan judul website.

Motivation Quotes: dua bar berisi kalimat motivasi.

Intro Section: sambutan dengan id="intro".

Crypto Section: daftar coin (BTC, ETH, SOL, BNB, XRP) ditampilkan dalam <ul>.

Inline CSS: contoh penggunaan style langsung pada tag.

Footer: copyright.

### Penjelasan CSS

Body: dark aesthetic dengan gradient abu gelap.

Header & Footer: background gelap dengan shadow ringan.

Motivation Quotes: blok dengan warna aksen hijau olive dan pink lembut.

Crypto Section: kotak dengan box-shadow dan border-radius.

Warna Coin: tiap coin punya warna sesuai identitas aslinya.

Hover Effect: efek zoom untuk interaksi pengguna.

### Hasil Screenshot
![Gambar WhatsApp 2025-09-29 pukul 14 12 50_4211b0da](https://github.com/user-attachments/assets/fb2a8c87-4dc8-4ddc-9cdd-b57bc41b1283)


