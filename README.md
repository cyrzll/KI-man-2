# Portofolio — Rasyid (Web Developer)

Website portofolio pribadi modern dan minimalis yang dirancang untuk menampilkan profil profesional, riwayat pendidikan, portofolio proyek terpilih, dan informasi kontak. Proyek ini dikembangkan dengan fokus pada kode yang bersih (*clean code*), tipografi editorial yang rapi, dan tata letak yang sepenuhnya responsif.

---

## 🌟 Fitur Utama

- **Desain Minimalis & Terstruktur**: Terinspirasi dari gaya desain modern dengan palet warna netral *Slate* dan aksen *Sky Blue*.
- **100% Flexbox Layout**: Menggunakan murni CSS Flexbox (`flex`, `flex-col`, `flex-wrap`) tanpa CSS Grid untuk tata letak yang konsisten dan adaptif di berbagai resolusi layar.
- **Navigasi Mobile Responsif (Zero-Jump & Pure CSS Toggle)**:
  - Menu hamburger yang mulus dengan toggle ikon (`bi-list` berganti ke `bi-x-lg` saat terbuka).
  - Menggunakan sistem CSS murni tanpa lompatan/pergeseran scroll saat tombol dibuka atau ditutup.
  - Menu otomatis menutup dan melakukan *smooth scroll* langsung ke bagian yang dipilih.
- **Setiap Section Memiliki Tinggi Penuh (*Viewport Height*)**: Menggunakan `min-h-screen` agar setiap bagian fokus dan nyaman dibaca.
- **Bebas Emoji & Ikonografi Konsisten**: Menggunakan [Bootstrap Icons](https://icons.getbootstrap.com/) untuk menjaga kesan profesional dan editorial.
- **Bagian Lengkap**:
  - **Beranda (Hero)**: Judul utama, ringkasan keahlian, tombol *Call-to-Action* (CTA), metrik pengalaman, dan daftar fokus teknologi.
  - **Tentang Saya**: Foto profil, narasi singkat, riwayat pendidikan terstruktur, serta keahlian & *tools*.
  - **Portofolio Terpilih**: Kartu proyek interaktif (Finansial Core Dashboard, Portal Informasi MAN 2, Landing Page Modern).
  - **Kontak**: Formulir pesan langsung, detail email, telepon, lokasi, dan tautan sosial (LinkedIn & GitHub).
  - **Footer**: Hak cipta dan navigasi cepat.

---

## 🛠️ Teknologi yang Digunakan

| Komponen | Teknologi | Keterangan |
| :--- | :--- | :--- |
| **Markup** | HTML5 Semantik | Struktur dokumen semantik dan aksesibel |
| **Styling** | [Tailwind CSS v4](https://tailwindcss.com/) (CDN) | *Utility-first CSS framework* |
| **Kustom CSS** | CSS3 (`style/style.css`) | Pengaturan tipografi dan mekanisme toggle menu mobile |
| **Ikonografi** | [Bootstrap Icons v1.11.3](https://icons.getbootstrap.com/) | Ikon vektor berbasis web font |
| **Tipografi** | [Google Fonts](https://fonts.google.com/) | *Plus Jakarta Sans* (Heading) & *Inter* (Body) |

---

## 📁 Struktur Direktori

```text
portofolio/
├── index.html          # Halaman utama portofolio
├── README.md           # Dokumentasi proyek
├── media/
│   └── profile.jpeg    # Foto profil
└── style/
    └── style.css       # Definisi font dan styling toggle navigasi mobile
```

---

## 🚀 Cara Menjalankan

Proyek ini dibuat menggunakan standar web statis murni sehingga tidak memerlukan proses *build* atau instalasi paket khusus.

1. **Buka Langsung di Browser**:
   - Cukup buka file `index.html` dengan peramban favorit Anda (Google Chrome, Firefox, Safari, Edge, dll.).

2. **Menggunakan Live Server (VS Code)**:
   - Pasang ekstensi **Live Server** di VS Code.
   - Klik kanan pada `index.html` lalu pilih **Open with Live Server** (berjalan di `http://127.0.0.1:5500`).

3. **Menggunakan Python HTTP Server**:
   ```bash
   # Masuk ke direktori portofolio
   cd portofolio

   # Jalankan server lokal sederhana
   python3 -m http.server 8000
   ```
   Buka peramban di `http://localhost:8000`.

---

## 👤 Pembuat

- **Nama**: Rasyid
- **Institusi**: MAN 2 (Madrasah Aliyah Negeri 2)
- **Fokus**: Web Development, Frontend Design, & Desain Antarmuka

---

## 📄 Hak Cipta & Lisensi

&copy; 2026 Rasyid. All rights reserved.
