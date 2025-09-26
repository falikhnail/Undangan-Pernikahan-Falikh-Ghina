# Undangan Pernikahan Falikh & Ghina

Digital wedding invitation template built with HTML, CSS, and JS.  
Simple, responsive, and customizable for Indonesian wedding events.

## Demo

[Live Demo](https://undangan-pernikahan-falikh-ghina.vercel.app/)

## Fitur

- **Responsive Design**: Tampilan optimal di desktop & mobile.
- **Tema Gelap/Terang**: Otomatis atau manual.
- **Komentar & Doa**: Tamu bisa mengirim ucapan, like, dan presensi.
- **Countdown Acara**: Hitung mundur menuju hari pernikahan.
- **Galeri Foto & Video**: Carousel gambar dan video kisah cinta.
- **Love Gift**: Info rekening & kontak untuk hadiah.
- **Animasi**: Konfeti, animasi love, dan efek transisi.
- **Audio**: Musik latar opsional.
- **Admin Dashboard**: Kelola komentar, presensi, dan pengaturan undangan.

## Struktur Folder

```
public/
  index.html          # Halaman utama undangan
  dashboard.html      # Dashboard admin
  assets/
    css/              # File CSS (guest.css, admin.css, dll)
    images/           # Gambar undangan & galeri
    music/            # File audio
    video/            # File video
```

## Cara Pakai

1. **Clone Repository**
   ```sh
   git clone https://github.com/falikhnail/Undangan-Pernikahan-Falikh-Ghina.git
   ```
2. **Edit Konten**
   - Ubah data pengantin, tanggal, lokasi, dan galeri di `public/index.html`.
   - Ganti gambar di `public/assets/images/`.
   - Edit CSS di `public/assets/css/` jika ingin kustomisasi tampilan.
3. **Hosting**
   - Bisa langsung di-host di layanan static hosting (GitHub Pages, Vercel, Netlify, dll).
   - Tidak perlu build, cukup upload folder `public/`.

## Konfigurasi

- **Komentar**: Aktif/nonaktif dengan atribut di `<body>` pada `index.html`.
- **Audio**: Ganti file musik di `public/assets/music/`, dan sesuaikan atribut `data-audio`.
- **Galeri**: Tambah/hapus gambar di carousel pada bagian galeri.
- **Admin**: Akses `dashboard.html` untuk kelola komentar & pengaturan.

## Lisensi

MIT License

---

> Dibuat dengan ❤️ oleh [Falikhnail](https://github.com/falikhnail)