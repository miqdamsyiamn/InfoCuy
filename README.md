# 🗺️ InfoCuy - Interactive Geo-Location App

> **Temukan, Bagikan, dan Kelola Lokasi Favoritmu di Bandung!**
> Aplikasi peta interaktif berbasis web yang memudahkan pengguna untuk memetakan dan menemukan lokasi-lokasi penting secara real-time.

<img width="1915" height="945" alt="image" src="https://github.com/user-attachments/assets/9ca1585d-bdd7-43e3-80b5-3b10aeef0b91" />




---

## 🚀 Tentang InfoCuy

**InfoCuy** adalah sebuah platform Sistem Informasi Geografis (GIS) modern yang dirancang untuk menjadi wadah berbagi informasi lokasi di kota Bandung. Aplikasi ini menjembatani kebutuhan pengguna akan peta digital yang interaktif namun tetap mudah digunakan (*user-friendly*).

Dengan InfoCuy, pengguna tidak hanya sekadar melihat peta, tetapi juga dapat berpartisipasi aktif dalam memperkaya data lokasi. Baik itu menemukan museum bersejarah, mencari tempat belanja terdekat, atau membagikan lokasi taman favorit, InfoCuy menyediakan antarmuka yang intuitif untuk semua kebutuhan tersebut.

---

## ✨ Fitur Unggulan

### 🌍 Peta Interaktif & Visualisasi Data
* **Marker Berwarna:** Lokasi dikategorikan secara visual dengan warna marker yang berbeda (Pendidikan, Belanja, Museum, Taman) untuk memudahkan identifikasi cepat.
* **Penanda Kepemilikan:**
    * 🔵 **Marker Biru:** Menandakan lokasi yang Anda tambahkan sendiri.
    * 🔴 **Marker Merah:** Menandakan lokasi yang ditambahkan oleh pengguna lain.
* **Smart Filter:** Fitur penyaringan canggih yang memungkinkan pengguna menampilkan lokasi berdasarkan kategori tertentu saja.

### 🔐 Manajemen Pengguna (Autentikasi)
* **Akses Aman:** Sistem registrasi dan login yang aman menggunakan email.
* **Hak Akses Bertingkat (RBAC):**
    * **User:** Memiliki kontrol penuh untuk menambah lokasi baru serta mengedit atau menghapus data milik sendiri.
    * **Admin:** Memiliki akses supervisi untuk mengelola seluruh data lokasi dan manajemen pengguna dalam sistem.

### 📝 Kemudahan Kelola Data (CRUD)
* **Tambah Lokasi Instan:** Cukup klik titik mana saja pada peta, dan formulir akan otomatis terisi dengan koordinat yang akurat.
* **Dashboard Terintegrasi:** Pusat kendali bagi pengguna untuk melihat daftar lokasi yang telah mereka kontribusikan.
* **Validasi Real-time:** Notifikasi interaktif (menggunakan SweetAlert) untuk setiap aksi sukses atau gagal, memberikan pengalaman pengguna yang responsif.

---

## 🛠️ Teknologi yang Digunakan

Aplikasi ini dibangun menggunakan tumpukan teknologi (*Tech Stack*) modern untuk menjamin performa dan skalabilitas:

### Frontend (Sisi Pengguna)
* ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) **HTML5 & CSS3** — Membangun antarmuka yang responsif dan estetis.
* ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) **Vanilla JavaScript** — Menangani logika interaktif tanpa *overhead* framework berat.
* ![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=Leaflet&logoColor=white) **Leaflet.js** — *Library* peta open-source terkemuka untuk interaksi peta yang mulus.
* **SweetAlert2** — Mempercantik notifikasi dan dialog konfirmasi.

### Backend (Sisi Server)
* ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) **Golang (Go)** — Bahasa pemrograman yang cepat dan efisien untuk menangani request server.
* ![Gin](https://img.shields.io/badge/Gin-008ECF?style=for-the-badge&logo=go&logoColor=white) **Gin Gonic** — Web framework HTTP berkinerja tinggi.
* ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) **MongoDB Atlas** — Database NoSQL berbasis *cloud* yang fleksibel dan skalabel.

---

## 🤝 Kontribusi

Proyek ini bersifat *open-source* dan terbuka untuk kontribusi. Kami mengundang pengembang lain untuk ikut serta mengembangkan InfoCuy, baik itu penambahan fitur baru, perbaikan *bug*, atau peningkatan dokumentasi.

---

## 📄 Lisensi

InfoCuy didistribusikan di bawah lisensi **[MIT License](LICENSE)**.
Dibuat dengan ❤️ oleh **Miqdam Syiam**.
