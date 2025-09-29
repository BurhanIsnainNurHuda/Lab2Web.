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

# Penjelasan Kode HTML

File `index.html` terdiri dari:

 1. Deklarasi HTML5 dan `<head>`

Menentukan charset UTF-8.

Mengatur viewport supaya responsif.

Memanggil file CSS eksternal `style.css.`

2. Bagian Motivasi Atas (NO RISK NO STORY)

`<div class="motivation-top">` digunakan untuk menampilkan quote motivasi di bagian atas halaman.

3. Header

`<header>` berisi judul utama “🚀 Blockchain & Crypto Dashboard”.

Dibuat agar terlihat jelas dan berada di tengah.

4. Intro Section

`<div id="intro">` menampilkan heading kedua dan paragraf pembuka.

Menggunakan ID supaya styling-nya lebih spesifik dibanding selector umum.

5. Crypto Section

`<section class="crypto-section">` berisi daftar coin teratas: BTC, ETH, SOL, BNB, XRP.

Tiap coin diberi `<li>` yang nanti warnanya diatur lewat CSS sesuai identitas masing-masing.

6. Inline CSS Contoh

`<p style="...">` menunjukkan contoh pemakaian inline CSS agar kita bisa membandingkan prioritasnya.

7. ID & Class Contoh

`<p id="paragraf-1" class="text-paragraf">` sengaja diberi ID dan Class sekaligus supaya kita bisa lihat CSS mana yang lebih kuat.

8. Bagian Motivasi Bawah

`<div class="motivation-bottom">` menampilkan quote kedua: “FAILURE IS NOT THE OPPOSITE OF SUCCESS: IT'S PART OF SUCCESS”.

9. Footer

`<footer>` berisi teks penutup dan sumber praktikum.

# Penjelasan Kode CSS

File `style.css` terdiri dari:

1. Global Styles

Background dark gradien (#121212 ke #1e1e1e).

Font Arial supaya clean.

Warna teks #d0d0d0 agar kontras tapi tetap lembut.

2. Heading

`<h1>` diberi warna biru-keabu-abuan (#b0c4de).

Ada efek text-shadow untuk kesan glow lembut.

3. #intro h1

Dibedakan warnanya (ungu pastel) agar tidak sama dengan heading umum.

Menunjukkan spesifikasi selector `#intro h1` hanya berlaku di dalam ID intro.

4. Paragraf & ID

`.text-paragraf` → warna teks ungu pucat.

`#paragraf-1` → warna kuning tebal (ID lebih kuat daripada Class).


### Hasil Screenshot
![Gambar WhatsApp 2025-09-29 pukul 14 12 50_4211b0da](https://github.com/user-attachments/assets/fb2a8c87-4dc8-4ddc-9cdd-b57bc41b1283)


