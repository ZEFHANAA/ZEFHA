# Website Portofolio

Website portofolio responsif dan modern dibuat dengan HTML, CSS, dan JavaScript murni (tanpa framework).

## Fitur

- Desain responsif dan modern
- Navigasi yang halus (smooth scrolling)
- Animasi saat scroll
- Filter portofolio interaktif
- Formulir kontak
- Tampilan sesuai dengan ukuran layar (mobile-friendly)
- Optimasi performa web

## Cara Menggunakan dengan GitHub Pages

1. Buat repository GitHub baru dengan nama `username.github.io` (ganti "username" dengan nama pengguna GitHub Anda)
2. Clone repository tersebut ke komputer Anda
3. Salin semua file dari folder web ini ke repository yang baru dibuat
4. Push ke GitHub:
   ```
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```
5. Website Anda akan otomatis dipublikasikan di `https://username.github.io`

## Cara Kostumisasi

### 1. Informasi Personal

Edit file `index.html` untuk mengubah:
- Nama
- Profesi
- Deskripsi tentang diri
- Informasi kontak
- Link sosial media

### 2. Tampilan Visual

Edit file `css/style.css` untuk mengubah:
- Warna tema (ubah variabel di bagian `:root`)
- Font (ubah import Google Fonts di bagian atas)
- Jarak dan ukuran elemen

### 3. Portofolio

Untuk menambah/mengedit proyek portofolio, modifikasi bagian portfolio-grid di `index.html`:

```html
<div class="portfolio-item" data-category="kategori-anda">
    <div class="portfolio-img">
        <img src="url-gambar-anda" alt="Nama Proyek">
    </div>
    <div class="portfolio-info">
        <h3>Nama Proyek</h3>
        <p>Jenis Proyek</p>
        <a href="link-proyek" class="portfolio-link">
            <i class="fas fa-link"></i>
        </a>
    </div>
</div>
```

## Dukungan Browser

- Chrome (terbaru)
- Firefox (terbaru)
- Safari (terbaru)
- Edge (terbaru)
- Opera (terbaru)

## Kredit

- Font Awesome untuk ikon
- Google Fonts untuk tipografi
- Placeholder.com untuk gambar placeholder

---

Dibuat dengan ❤️ sebagai portofolio pribadi. Silakan kustomisasi sesuai kebutuhan Anda! 