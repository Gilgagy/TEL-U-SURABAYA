# 💼 Freelance Project Tracker App

Aplikasi Manajemen dan Tracking Kegiatan Freelance berbasis desktop modern yang dibangun menggunakan **Python** dan **ttkbootstrap**. Proyek ini dikembangkan sebagai pemenuhan Tugas Besar untuk mata kuliah **Algoritma Pemrograman**.

---

## 🌟 Fitur Utama

Aplikasi ini dilengkapi dengan fitur-fitur manajemen proyek esensial untuk mempermudah alur kerja para *freelancer*:

* **✨ Modern GUI:** Tampilan antarmuka estetik dan bersih menggunakan tema *"Flatly"* dari `ttkbootstrap`.
* **📝 CRUD System:** Manajemen data penuh (Tambah, Lihat, Ubah, Hapus) melalui jendela pop-up interaktif.
* **📊 Live Dashboard:** Kalkulasi statistik keuangan dan status proyek secara langsung (*real-time*).
* **⚡ Pencarian Ganda (Searching):** Mendukung pencarian berbasis nama Proyek atau Klien menggunakan algoritma **Sequential Search** dan **Binary Search**.
* **📌 Pengurutan Cerdas (Sorting):** * Mengurutkan tenggat waktu terdekat menggunakan **Selection Sort**.
    * Mengurutkan nilai bayaran tertinggi menggunakan **Insertion Sort**.
* **🛡️ Human-Error Protection:** Validasi ketat untuk mencegah data rusak akibat salah ketik format tanggal atau nominal keuangan.

---

## 🛠️ Teknologi yang Digunakan

Aplikasi ini memanfaatkan ekosistem Python modern berikut:

* **Bahasa Pemrograman:** Python 3.10+
* **Framework GUI:** Tkinter & [ttkbootstrap](https://ttkbootstrap.readthedocs.io/)
* **Algoritma Utama:** Selection Sort, Insertion Sort, Sequential Search, Binary Search


---

## 🧩 Analisis Algoritma (Spesifikasi Teknis)

Aplikasi ini menerapkan konsep struktur data dinamis `List of Dictionaries` dengan detail kompleksitas algoritma sebagai berikut:

| Fitur | Algoritma | Kompleksitas Waktu (Time Complexity) | Keterangan |
| --- | --- | --- | --- |
| **Sort Deadline** | Selection Sort | $O(N^2)$ | Menyeleksi tanggal terkecil (terdekat). |
| **Sort Bayaran** | Insertion Sort | $O(N^2)$ | Menyisipkan data bayaran secara *descending*. |
| **Cari Proyek/Klien** | Sequential Search | $O(N)$ | Pencarian linear tanpa syarat urutan data. |
| **Cari Proyek/Klien** | Binary Search | $O(\log N)$ | Pencarian bagi-dua dengan pengurutan data internal terlebih dahulu. |

---

## 📸 Tampilan Aplikasi


| Halaman Utama & Dasbor | Formulir Input Pop-up |
| --- | --- |
|  |  |

---

## 👥 Anggota Tim / Pengembang

* **Ferio Ilham Bayu Prihadno** - (108102530002)
* **Boy Rohtuah Tumanggor**     - (108102500004) 
