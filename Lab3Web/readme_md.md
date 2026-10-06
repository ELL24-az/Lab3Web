# Praktikum 3: CSS Dasar - Pemrograman Web

Repository ini dibuat untuk menyelesaikan tugas **Praktikum 3: CSS Dasar** pada mata kuliah **Pemrograman Web** di Universitas Pelita Bangsa.

# Tujuan Praktikum
1. Mahasiswa mampu memahami konsep dasar CSS.
2. Mahasiswa mampu memahami aturan penulisan pada CSS.
3. Mahasiswa mampu memahami selector sebagai pengontrol CSS.
4. Mahasiswa mampu membuat pengaturan CSS pada HTML.

---

# Langkah-Langkah Praktikum

 1. Membuat Dokumen HTML (`lab2_css_dasar.html`)
Membuat struktur dasar dokumen HTML yang berisi bagian header, navigasi, serta konten dengan elemen `div` (ber-ID `#intro`) dan tautan ber-kelas (`button btn-primary`).

 2. Mendeklarasikan CSS Internal
Menambahkan tag `<style>` di dalam bagian `<head>` dokumen HTML untuk mengatur font global, header, elemen `h1`, serta format teks miring di dalam `h1`.

 3. Menambahkan Inline CSS
Menambahkan atribut `style` secara langsung pada tag paragraf `<p>` untuk mengatur perataan teks dan warna secara spesifik pada baris tersebut.

 4. Membuat CSS Eksternal (`style_eksternal.css`)
Memisahkan kode styling ke dalam file eksternal `style_eksternal.css` dan menghubungkannya menggunakan tag `<link>` pada bagian `<head>` HTML. Mengatur tampilan elemen navigasi dan link agar lebih rapi serta interaktif (`hover`).

 5. Menambahkan CSS Selector (ID & Class Selector)
Menambahkan deklarasi ID Selector (`#intro`, `#intro h1`) dan Class Selector (`.button`, `.btn-primary`) pada file CSS eksternal untuk mempercantik tata letak kotak konten dan tombol interaktif.

---

## Jawaban Pertanyaan & Tugas

1. **Eksperimen CSS Cheat Sheet:** 
   Eksperimen properti tambahan seperti `box-shadow`, `border-radius`, dan `transition` pada tombol berhasil diterapkan untuk memperkaya tampilan antarmuka.
2. **Perbedaan `h1 {...}` dengan `#intro h1 {...}`:**
   Jika terdapat CSS internal, eksternal, dan inline pada elemen yang sama, maka inline CSS memiliki prioritas lebih tinggi sehingga aturan inline yang akan diterapkan pada browser. Inline CSS ditulis langsung pada elemen HTML, sedangkan internal dan eksternal ditulis pada bagian atau file CSS terpisah
3. **Prioritas Deklarasi CSS (Internal vs Eksternal vs Inline):**
   Jika terdapat CSS internal, eksternal, dan inline pada elemen yang sama, maka inline CSS memiliki prioritas lebih tinggi sehingga aturan inline yang akan diterapkan pada browser. Inline CSS ditulis langsung pada elemen HTML, sedangkan internal dan eksternal ditulis pada bagian atau file CSS terpisah.                          
4. **Prioritas ID Selector vs Class Selector:**
   Jika sebuah elemen memiliki ID dan Class yang sama-sama memiliki deklarasi CSS, maka ID selector memiliki prioritas lebih tinggi daripada Class selector. Oleh karena itu, apabila terdapat perbedaan aturan antara ID dan Class, aturan dari ID yang akan diterapkan pada elemen tersebut. 
