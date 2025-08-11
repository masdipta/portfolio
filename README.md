# Dipta Creative Portfolio
Portfolio website untuk desainer grafis, ilustrator, dan motion artist.

## Fitur
- Portfolio responsive dengan filter kategori
- Carousel project dengan navigasi
- Testimonials section
- Form kontak
- SEO optimized
- Google Analytics integration

## Edit Gambar & Video
### Cara Mengganti Gambar:
1. Ganti file gambar di folder `images/`
2. Update path di file `index.html` dan `project.html`
3. Pastikan ukuran gambar sesuai (rekomendasi: 1200x800px)

### Cara Menambahkan Video:
1. Di file `project.html`, cari bagian `projectsData`
2. Tambahkan video ke dalam array `media`:
   ```javascript
   {
     type: "video",
     provider: "native", // atau "youtube"
     src: "path/to/your/video.mp4" // untuk native
     // atau
     videoId: "VIDEO_ID" // untuk youtube
   }

   Format Video:
Video lokal: gunakan provider: "native"
YouTube: gunakan provider: "youtube" dan videoId


### 5. **Struktur Folder**
Struktur Folder
├── index.html # Halaman utama
├── project.html # Halaman detail project
├── images/ # Folder gambar
│ ├── Dipta Photo.png
│ └── [gambar lainnya]
└── README.md # Dokumentasi ini


### 6. **Konfigurasi Google Analytics**
Google Analytics
Buat akun Google Analytics
Dapatkan Measurement ID
Ganti G-XXXXXXXXXX di file index.html dan project.html dengan ID kamu


### 7. **Kontak**
Kontak
Email: [email kamu]
Instagram: [@username]
