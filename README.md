# percetakan_online
Project Kelompok
1. Anisa Auliana Rizkika
2. Ibnu Sahrul Anwar 
3. Ramzi Selpora Widiyanto

---
# 🖨️ Website Percetakan Online Berbasis IoT (ESP32)

## 📌 Deskripsi Project

Project ini adalah sistem **percetakan online berbasis website** yang terintegrasi dengan **mikrokontroler ESP32 (IoT)**.
User dapat melakukan pemesanan cetak secara online, dan sistem akan memproses serta memonitor status cetakan secara real-time.

---

# 🚀 Tahapan Pengembangan Sistem

## 🔷 1. Perencanaan Sistem

* Menentukan konsep:

  * Website percetakan online
  * Mitra percetakan
  * Integrasi IoT (ESP32)
* Menentukan fitur:

  * Login & register
  * Upload file
  * Pilih jenis cetak
  * Status order

---

## 🔷 2. Desain Sistem

* Arsitektur:

  * User → Website → Database → ESP32 → Printer
* Desain database:

  * Tabel `users`
  * Tabel `mitra`
  * Tabel `orders`

---

## 🔷 3. Pembuatan Website (Frontend & Backend)

* Menggunakan:

  * HTML, CSS, Bootstrap
  * PHP (Native)
  * MySQL (Database)

Fitur:

* Halaman login/register
* Dashboard user
* Form upload file
* Sistem order

---

## 🔷 4. Pembuatan REST API

* API untuk ESP32:

  * Ambil data order
  * Update status order
* Format data: JSON

---

## 🔷 5. Implementasi ESP32

* Koneksi WiFi
* Ambil data dari API
* Proses data (simulasi cetak)
* Update status ke server

---

## 🔷 6. Integrasi Sistem

Alur:

1. User melakukan order
2. Data masuk database
3. ESP32 mengambil data
4. Proses cetak
5. Update status
6. Website menampilkan status

---

## 🔷 7. Testing

* Uji upload file
* Uji koneksi database
* Uji API
* Uji komunikasi ESP32

---

## 🔷 8. Dokumentasi

* Flowchart sistem
* Diagram arsitektur
* Penjelasan:

  * ALU
  * Control Unit
  * Interrupt
  * Addressing Mode

---

# 📁 Struktur Folder Project

```
percetakan-iot/
│
├── 📁 frontend/                # Tampilan Website
│   ├── index.php
│   ├── login.php
│   ├── register.php
│   ├── dashboard.php
│   ├── upload.php
│   └── assets/
│       ├── css/
│       ├── js/
│       └── images/
│
├── 📁 backend/                # Logic Server
│   ├── config/
│   │   └── koneksi.php
│   ├── models/
│   ├── controllers/
│   └── functions.php
│
├── 📁 api/                    # REST API untuk ESP32
│   ├── get_order.php
│   ├── update_status.php
│   └── koneksi.php
│
├── 📁 database/
│   └── percetakan.sql
│
├── 📁 esp32/                  # Kode Mikrokontroler
│   └── esp32.ino
│
├── 📁 docs/                   # Dokumentasi
│   ├── flowchart.png
│   ├── arsitektur.png
│   └── laporan.pdf
│
├── README.md
└── .gitignore
```

---

# 🔗 Alur Sistem

```
User → Website → Database → API → ESP32 → Printer
                         ↑                 ↓
                      Update Status ←------
```

---

# 🛠️ Teknologi yang Digunakan

* Frontend: HTML, CSS, Bootstrap
* Backend: PHP Native
* Database: MySQL
* IoT: ESP32
* API: REST (JSON)

---

# 🎯 Tujuan Project

* Mempermudah pemesanan percetakan
* Mengintegrasikan sistem web dengan perangkat fisik
* Menerapkan konsep IoT dalam dunia nyata

---

# 🔥 Pengembangan Selanjutnya

* Integrasi pembayaran online
* Notifikasi WhatsApp
* Tracking lokasi percetakan (Google Maps)
* Dashboard real-time

---

# 👨‍💻 Author

Nama: (Isi Nama Kamu)
Project: Tugas Project Based Learning
