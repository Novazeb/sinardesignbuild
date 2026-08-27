# SINAR DESIGN & BUILD (SDB)

Website profil perusahaan resmi untuk **SINAR DESIGN & BUILD**, penyedia layanan jasa arsitektur, perencanaan tata ruang, desain interior, dan kontraktor konstruksi yang berbasis di Jakarta, Indonesia.

Project ini dibangun dengan arsitektur modern berbasis **Vue 3** dan **Vite**, mengutamakan performa loading cepat, tata letak responsif, serta visual interaktif yang elegan.

---

## 🛠️ Teknologi yang Digunakan

- **Vue.js 3 (Composition API / `<script setup>`)**: Framework frontend utama untuk komponen yang modular dan reaktif.
- **Vite 6**: Build tool generasi baru untuk proses development instan dan bundling aset yang sangat optimal.
- **Bootstrap (Grid System & Utilities)**: Tata letak responsif untuk tampilan layar desktop, tablet, hingga smartphone.
- **Swiper Slider**: Animasi slider proyek interaktif di halaman utama (Hero Section).
- **Owl Carousel**: Carousel multi-item untuk daftar anggota tim, galeri portofolio, dan ulasan testimoni klien.
- **LightGallery**: Lightbox interaktif untuk visualisasi foto proyek resolusi tinggi dan pemutar video YouTube terintegrasi.
- **RD Navbar & Core Scripts**: Navigasi sidebar/fixed yang dinamis dan mendukung *smooth scrolling* antar bagian halaman.
- **Vector Icons**: Material Design Icons (MDI), Linearicons, dan FontAwesome 4.7.

---

## ✨ Fitur-Fitur Website

1. **Preloader Animasi**: Animasi pemuatan halaman yang halus saat pertama kali dibuka.
2. **Hero Slider Rancang Bangun**: Showcase proyek unggulan dengan indikator luas area, estimasi, dan navigasi slider.
3. **Layanan & Form Estimasi Biaya**: Rangkuman layanan (Desain Arsitektur, Desain Interior, Tata Cahaya) disertai formulir konsultasi cepat.
4. **4 Tahapan Kerja Sistematis**: Tab interaktif yang menjelaskan alur kerja dari konsultasi awal, desain 3D, konstruksi fisik, hingga serah terima kunci.
5. **Profil Tim & Founder**: Daftar arsitek dan tenaga ahli di balik Sinar Design & Build, lengkap dengan tautan media sosial dan email.
6. **Statistik & Video Lightbox**: Ringkasan pencapaian (jumlah proyek, tahun pengalaman) serta preview video profil perusahaan.
7. **Portofolio Proyek Terpilih**: Galeri karya arsitektur di wilayah Jakarta yang dapat diperbesar dengan fitur zoom dan fullscreen.
8. **Edukasi & Artikel**: Tips seputar tren arsitektur tropis, panduan RAB bangunan, dan panduan konstruksi.
9. **Testimoni Klien**: Ulasan asli dari pemilik properti dan pengusaha di Jakarta.
10. **Kontak & Integrasi WhatsApp**: Tombol dan formulir kontak yang langsung terhubung ke email dan nomor WhatsApp resmi.

---

## 📂 Struktur Direktori

```text
sinardesignandbuilding/
├── public/               # Aset statis publik (gambar, font ikon, stylesheet, script legacy)
│   ├── css/
│   ├── fonts/
│   ├── images/
│   └── js/
├── src/
│   ├── components/       # Komponen Vue modular
│   │   ├── AboutSection.vue
│   │   ├── AppFooter.vue
│   │   ├── AppHeader.vue
│   │   ├── AwardsSection.vue
│   │   ├── BlogSection.vue
│   │   ├── ContactSection.vue
│   │   ├── HeroSection.vue
│   │   ├── PortfolioSection.vue
│   │   ├── Preloader.vue
│   │   ├── ProcessSection.vue
│   │   ├── TeamSection.vue
│   │   └── TestimonialsSection.vue
│   ├── App.vue           # Root component
│   └── main.js           # Entry point Vue 3
├── index.html            # File HTML utama
├── package.json          # Manajemen dependensi dan script npm
├── vite.config.js        # Konfigurasi bundler Vite
└── README.md
```

---

## 🚀 Cara Menjalankan Project

### 1. Prasyarat
Pastikan Anda sudah menginstal [Node.js](https://nodejs.org/) (versi 18 ke atas disarankan).

### 2. Instalasi Dependensi
Jalankan perintah berikut di terminal:
```bash
npm install
```

### 3. Menjalankan Server Development
```bash
npm run dev
```
Buka browser di alamat `http://localhost:3000`.

### 4. Build untuk Produksi
Untuk menghasilkan file statis yang siap di-deploy ke server/hosting (Vercel, Netlify, cPanel, dll):
```bash
npm run build
```
File hasil build akan berada di dalam folder `dist/`.

### 5. Preview Hasil Build
```bash
npm run preview
```

---

## 📞 Kontak & Informasi

- **Perusahaan**: SINAR DESIGN & BUILD
- **Lokasi**: Jakarta, Indonesia
- **WhatsApp / Telepon**: [+62 812-1893-9696](https://wa.me/6281218939696)
- **Instagram**: [@zebua_1011](https://instagram.com/zebua_1011)
- **Email**: [novaberkatsyukurzebua@gmail.com](mailto:novaberkatsyukurzebua@gmail.com)

---

**Designed & Developed by Nova**
