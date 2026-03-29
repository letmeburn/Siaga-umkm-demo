# SiAGA UMKM Demo

## Gambaran Umum

SiAGA UMKM Demo adalah prototype web aplikasi yang dirancang untuk membantu pelaku UMKM dalam memantau harga bahan baku, menemukan supplier lokal, serta mendapatkan insight bisnis melalui chatbot sederhana.

Aplikasi ini dibuat dengan pendekatan ringan (tanpa backend) menggunakan HTML, CSS, dan JavaScript murni, sehingga mudah dijalankan dan dikembangkan lebih lanjut.

---

## Fitur Utama

### 1. Dashboard Harga

* Menampilkan harga bahan baku (contoh: tepung, beras, dll)
* Grafik tren harga mingguan menggunakan Chart.js
* Filter berdasarkan:

  * Komoditas
  * Lokasi
  * Brand
* Simulasi perubahan harga secara dinamis

### 2. Local Material Finder

* Kategori industri:

  * Makanan & Minuman
  * Fashion & Tekstil
  * Kerajinan & Furnitur
  * Kecantikan
  * Pertanian & Peternakan
  * Rumah Tangga
* UI berbasis grid interaktif
* Placeholder untuk integrasi supplier lokal

### 3. Chat SiAGA (AI Assistant)

* Chatbot berbasis rule-based (bukan AI real-time)
* Respon otomatis untuk:

  * Analisis harga
  * Strategi bisnis
  * Prediksi pasar
  * Supplier lokal
* Quick reply untuk interaksi cepat

### 4. Profil Pengguna

* Edit data pengguna (nama, email, telepon, alamat)
* Statistik sederhana (dummy data)
* Menu pengaturan (placeholder)

### 5. Sistem Login (Simulasi)

* Login email/password (tanpa autentikasi backend)
* Social login (dummy)
* State login menggunakan variabel JavaScript

---

## Teknologi yang Digunakan

* HTML5
* CSS3 (custom styling, dark mode)
* JavaScript (Vanilla JS)
* Chart.js (visualisasi data)
* Font Awesome (ikon)

---

## Struktur Project

```
siaga-umkm-demo/
│
├── index.html   # File utama (semua fitur ada di sini)
└── README.md    # Dokumentasi project
```

Catatan:
Project ini masih dalam bentuk single file untuk kemudahan demo.

---

## Cara Menjalankan

1. Download atau clone repository ini
2. Buka file `index.html`
3. Jalankan langsung di browser (Firefox/Chrome)

Tidak memerlukan:

* Instalasi
* Server
* Database

---

## Catatan Pengembangan

Beberapa bagian masih berupa simulasi / placeholder:

* Data harga belum terhubung ke API real
* Chatbot masih rule-based (if-else)
* Supplier lokal belum terintegrasi database
* Sistem login belum menggunakan autentikasi sebenarnya

---

## Ide Pengembangan Selanjutnya

* Integrasi API harga bahan pokok (misalnya dari pemerintah atau marketplace)
* Backend (Node.js / Firebase / Supabase)
* Sistem autentikasi real (JWT / OAuth)
* Chatbot berbasis AI (OpenAI / LLM lokal via Ollama)
* Fitur pencarian supplier berbasis lokasi (Geo API)
* Notifikasi harga real-time

---

## Tujuan Project

Project ini dibuat sebagai:

* Prototype / demo ide
* Bahan presentasi
* Dasar pengembangan aplikasi UMKM yang lebih kompleks

---

## Lisensi

Bebas digunakan untuk pembelajaran dan pengembangan lebih lanjut.

Jika digunakan untuk production, disarankan untuk menambahkan:

* Backend
* Security
* Data validation

---

## Penutup

Project ini masih sederhana, tapi sudah mencakup konsep inti:

* Dashboard data
* Interaksi user
* Simulasi AI
* Navigasi multi-halaman dalam satu file

Silakan dikembangkan sesuai kebutuhan.
