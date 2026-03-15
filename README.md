# Landing Page PT. Gading Gardatama Perkasa

Website landing page resmi untuk perusahaan jasa pengamanan swasta terkemuka di Indonesia.

## 📋 Deskripsi Proyek

Proyek ini merupakan website landing page yang dibangun untuk **PT. Gading Gardatama Perkasa**, perusahaan penyedia jasa keamanan swasta yang terpercaya di Indonesia. Website ini dirancang untuk memperkenalkan layanan keamanan profesional kepada calon klien dan memberikan informasi lengkap tentang perusahaan.

### Profil Singkat Perusahaan

**PT. Gading Gardatama Perkasa** adalah perusahaan jasa pengamanan swasta yang berlokasi di:
- **Alamat**: RT 05, RW 02, Ds. Pulai Gading, Kec. Bayung Lencir, Kab. Musi Banyuasin, Sumatera Selatan
- **Telepon**: +62 821-1472-5042
- **Email**: info@gadinggardatama.co.id
- **Website**: gadinggardatama.co.id

Perusahaan ini menyediakan layanan keamanan terintegrasi，包括：

- **Penyedia Tenaga Keamanan** - Personel Satpam profesional bersertifikasi
- **Peralatan Keamanan** - Instalasi CCTV & Access Control
- **Event Security** - Pengamanan acara dan kegiatan masyarakat
- **Security Pabrik** - Pengamanan kawasan industri dan manufaktur

---

## 🗂️ Struktur Folder dan File

```
Landing Page Satpam/
├── index.html              # Halaman Utama (Beranda)
├── tentang.html            # Halaman Tentang Kami
├── layanan.html           # Halaman Layanan Keamanan
├── kontak.html            # Halaman Kontak & Formulir
├── preview.html           # Halaman Preview
├── README.md              # Dokumentasi proyek ini
└── assets/                # Folder aset/gambar
    ├── logo.jpeg                           # Logo perusahaan
    ├── Keamanan Kantor.png                # Gambar keamanan kantor
    ├── Keamanan Pabrik.jpg                # Gambar keamanan pabrik
    ├── Patroli Malam.png                  # Gambar patroli malam
    ├── Pemantauan CCTV.png                # Gambar pemantauan CCTV
    ├── Sambut Tamu.jpg                    # Gambar menyambut tamu
    ├── Event Security.png                 # Gambar event security
    ├── Membantu Pengunjung.png            # Gambar bantuan pengunjung
    └── Membantu Pengunjung di Pusat Perbelanjaan.png
```

---

## 🛠️ Teknologi yang Digunakan

Website ini dibangun menggunakan teknologi modern berikut:

| Teknologi | Deskripsi | Versi |
|-----------|-----------|-------|
| **Tailwind CSS** | Framework CSS utility-first untuk styling responsif | v3.x (CDN) |
| **Flowbite** | Komponen UI berbasis Tailwind CSS | v2.3.0 |
| **Google Fonts** | Tipografi profesional | DM Sans, Outfit |
| **Phosphor Icons** | Ikon vektor modern | v2.x (CDN) |
| **jQuery** | Library JavaScript untuk form submission | v3.2.1 |

### Fitur Utama

- ✅ Desain responsif (mobile-friendly)
- ✅ Navigasi halus (smooth scroll)
- ✅ Animasi interaktif (floating, pulse)
- ✅ Floating WhatsApp button
- ✅ Formulir kontak terintegrasi dengan Google Forms
- ✅ SEO-friendly structure
- ✅ Loading cepat (CDN-based)

---

## 📱 Halaman Website

### 1. Halaman Utama (`index.html`)

Halaman landing utama yang berisi:
- Hero section dengan tagline profesional
- Mengapa memilih kami (keunggulan kompetitif)
- Profil perusahaan singkat
- Daftar layanan utama (4 layanan)
- Bagian legalitas (izin operasional)
- FAQ (Pertanyaan Umum)
- Call-to-Action
- Footer dengan informasi kontak

### 2. Halaman Tentang Kami (`tentang.html`)

Halaman yang menampilkan:
- Profil perusahaan detail
- Visi dan Misi
- Nilai Inti (Core Values): Integritas, Profesional, Responsif, Hospitality
- Galeri operasional lapangan

### 3. Halaman Layanan (`layanan.html`)

Halaman detail layanan yang mencakup:
- Penyedia Tenaga Keamanan
- Penerapan Peralatan Keamanan (CCTV, Access Control)
- Event Security
- Security Pabrik
- Alur kerja operasional (metodologi)

### 4. Halaman Kontak (`kontak.html`)

Halaman kontak lengkap dengan:
- Informasi kontak perusahaan
- Formulir pesan langsung
- Peta lokasi Google Maps
- Jam operasional kantor

---

## 🚀 Cara Menjalankan Proyek

### Persyaratan

- Browser modern (Chrome, Firefox, Edge, Safari)
- Koneksi internet (untuk memuat CDN resources)

### Langkah-langkah

1. **Clone/Download** repositori ini ke komputer lokal Anda

2. **Buka folder proyek** di file explorer

3. **Buka file `index.html`** dengan cara:
   - Klik dua kali pada file `index.html`, atau
   - Drag file ke browser, atau
   - Buka dengan VS Code dan gunakan Live Server

4. Website akan dapat diakses di browser dengan URL:
   ```
   file://path/to/Landing Page Satpam/index.html
   ```

### Menggunakan Live Server (VS Code)

1. Buka proyek di VS Code
2. Install ekstensi "Live Server"
3. Klik kanan pada `index.html`
4. Pilih "Open with Live Server"

---

## ⚙️ Konfigurasi

### Warna Tema (Tailwind Config)

Website menggunakan warna khusus:

| Nama Warna | Kode Hex | Penggunaan |
|------------|----------|------------|
| Navy 500 | #1e293b | Secondary color |
| Navy 800 | #141f38 | Navbar, footer |
| Navy 900 | #0f172a | Background dark |
| Gold 400 | #facc15 | Accent highlight |
| Gold 500 | #d9a520 | Primary accent |
| Gold 600 | #ca8a04 | Hover state |

### Font Family

- **Heading**: Outfit (Bold, Semi-Bold)
- **Body**: DM Sans (Regular, Medium)

---

## 📝 Kustomisasi

### Mengubah Konten Teks

Buka file HTML yang ingin diedit dan cari teks yang ingin diubah. Contoh:

```html
<!-- Mengubah nama perusahaan -->
<span class="text-gold-500">PT. GADING GARDATAMA PERKASA</span>

<!-- Mengubah nomor telepon -->
<span>+62 821-1472-5042</span>
```

### Mengubah Gambar

Ganti file gambar di folder `assets/` dengan gambar baru dengan nama yang sama, atau ubah path di file HTML:

```html
<!-- Mengubah logo -->
<img src="assets/logo.jpeg" alt="Logo">

<!-- Ubah menjadi -->
<img src="assets/logo-baru.png" alt="Logo">
```

### Mengubah Warna

Edit konfigurasi Tailwind di bagian `<script>` setiap file HTML:

```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                navy: {
                    500: '#1e293b',
                    // Ubah sesuai warna yang diinginkan
                },
                gold: {
                    500: '#d9a520',
                }
            }
        }
    }
}
```

---

## 🔧 Integrasi Formulir Kontak

Formulir kontak di [`kontak.html`](kontak.html:249) saat ini terintegrasi dengan Google Forms. Untuk menggunakan Google Forms Anda sendiri:

1. Buat formulir di [Google Forms](https://forms.google.com)
2. Ambil URL formulir
3. Update attribute `action` pada tag `<form>`:

```html
<form action="https://docs.google.com/forms/d/e/YOUR_FORM_ID/formResponse" ...>
```

4. Update entry ID untuk setiap input:

```html
<!-- Cari name="entry.XXXXX" dan ganti dengan ID dari Google Forms Anda -->
<input type="text" name="entry.YOUR_ENTRY_ID" ...>
```

---

## 📄 Lisensi

Copyright © 2024 PT. Gading Gardatama Perkasa. All Rights Reserved.

---

## 📞 Dukungan

Untuk pertanyaan atau masalah terkait proyek ini, silakan hubungi tim pengembang.

---

*Dibuat dengan ❤️ menggunakan Tailwind CSS dan Flowbite*
