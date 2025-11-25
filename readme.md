# 🧮 Scientific JS Calculator - Dashboard (Tugas Akhir Web)

Aplikasi kalkulator ilmiah berbasis web dengan antarmuka *dashboard* modern, fitur riwayat perhitungan (*History Log*), dan visualisasi memori (*Memory Stack*).

Proyek ini dibuat untuk memenuhi **Tugas Akhir Praktikum Pemrograman Web (Modul 5: JavaScript Dasar)**, mendemonstrasikan kemampuan manipulasi DOM, *Event Handling*, dan logika algoritma matematika menggunakan JavaScript murni (Vanilla JS).

[**Lihat Live Demo**](https://exyluminate.github.io/Scientific_Calculator/)
## ✨ Fitur Utama

Kalkulator ini dirancang bukan hanya untuk menghitung, tapi memberikan pengalaman pengguna (UX) yang informatif:

* **🎨 Modern Dashboard UI** — Tata letak terbagi menjadi 3 panel (Kalkulator, History, Memory) yang responsif (Mobile & Desktop).
* **🌙 Dark Mode Support** — Dilengkapi tombol *toggle* tema Gelap/Terang yang otomatis tersimpan di *Local Storage* browser.
* **📝 Smart History Log** — Menyimpan 5 riwayat perhitungan terakhir. Riwayat bisa diklik untuk menggunakan kembali angkanya.
* **🧠 Visual Memory Stack** — Indikator visual untuk fitur memori (M+, M-, MR, MC) yang menampilkan angka tersimpan secara *real-time*.
* **🇮🇩 Format Angka Indonesia** — Otomatis memberikan format titik ribuan (contoh: `1.000.000`) agar mudah dibaca.
* **🛡️ Error Handling** — Mencegah *crash* akibat pembagian dengan nol atau format rumus yang salah.
* **⌨️ Keyboard Support** — Mendukung input langsung menggunakan keyboard laptop/PC (Numpad).

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dibangun tanpa *dependencies* berat, hanya menggunakan teknologi web standar:

| Teknologi | Penggunaan Utama |
| :--- | :--- |
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Struktur semantik halaman dan layout grid dasar. |
| ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) | *Utility-first framework* untuk styling responsif, *dark mode*, dan tata letak modern. |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Logika perhitungan, manipulasi DOM, algoritma format angka, dan manajemen *state* (History/Memory). |

---

## 📦 Struktur File

📂 Scientific-JS-Calculator
 ┣ 📜 index.html      # File utama (HTML + CSS CDN + Logic JS)
 ┗ 📜 README.md       # Dokumentasi proyek ini