# SMK Negeri 64 Jakarta - Website Modern

Website resmi SMK Negeri 64 Jakarta dengan desain modern, minimalis, dan elegan.

## 🎨 Fitur Desain

- **Modern & Minimalis**: Desain clean dengan tipografi yang mudah dibaca
- **Responsive**: Optimal di semua perangkat (desktop, tablet, mobile)
- **Elegan**: Gradient warna dan animasi yang smooth
- **Fast Loading**: Optimized CSS dan struktur yang efisien
- **Accessible**: Mengikuti standar aksesibilitas web

## 🚀 Teknologi

- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Backend**: PHP
- **Database**: MySQL
- **Font**: Inter (Google Fonts)
- **Icons**: Emoji dan custom icons
- **SEO**: Sitemap XML, Robots.txt, Meta tags
- **Performance**: Gzip compression, Browser caching, Optimized assets

## 📁 Struktur File

```
pakHikmat/
├── assets/
│   ├── css/
│   │   └── style.css          # Stylesheet utama
│   ├── js/
│   │   └── animations.js      # JavaScript animations
│   └── images/
│       ├── logo.png           # Logo sekolah
│       ├── favicon.ico        # Favicon
│       └── apple-touch-icon.png # Apple touch icon
├── admin/                     # Panel admin
│   ├── dashboard.php
│   ├── login.php
│   ├── tambah_berita.php
│   ├── edit_berita.php
│   └── hapus_berita.php
├── index.php                  # Halaman utama
├── profil.php                 # Halaman profil sekolah
├── berita.php                 # Halaman berita
├── berita_detail.php          # Detail berita
├── kontak.php                 # Halaman kontak
├── navbar.php                 # Komponen navbar
├── config.php                 # Konfigurasi database
├── sitemap.xml                # Sitemap untuk SEO
├── robots.txt                 # Robots.txt untuk SEO
├── .htaccess                  # Apache configuration
├── package.json               # Project metadata
├── .gitignore                 # Git ignore rules
├── CHANGELOG.md               # History perubahan
├── LICENSE                    # MIT License
├── CONTRIBUTING.md            # Panduan kontribusi
├── SECURITY.md                # Kebijakan keamanan
└── README.md                  # Dokumentasi ini
```
```
```
```
```

## 🎯 Halaman Utama

### 1. Beranda (`index.php`)
- Hero section dengan gradient yang menarik
- Profil singkat sekolah
- Keunggulan sekolah (3 card)
- Call-to-action section
- Footer lengkap

### 2. Profil (`profil.php`)
- Informasi umum sekolah
- Visi & Misi
- Fasilitas & Mitra Industri
- Kegiatan & Prestasi

### 3. Berita (`berita.php`)
- Daftar berita terbaru
- Newsletter subscription
- Responsive grid layout

### 4. Kontak (`kontak.php`)
- Informasi kontak lengkap
- Form kontak yang user-friendly
- Peta lokasi (placeholder)

## 🎨 Komponen Desain

### Color Scheme
- **Primary**: `#667eea` to `#764ba2` (Gradient)
- **Text**: `#1a1a1a` (Dark), `#666` (Gray)
- **Background**: `#ffffff` (White), `#f8f9fa` (Light Gray)
- **Accent**: `#f0f0f0` (Border)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 400, 500, 600, 700
- **Sizes**: Responsive dengan rem units

### Components
- **Cards**: Rounded corners, subtle shadows
- **Buttons**: Gradient primary, outline secondary
- **Navigation**: Fixed navbar dengan backdrop blur
- **Hero Sections**: Full-width dengan gradient background

## 📱 Responsive Design

- **Desktop**: 1200px+ (3-column grid)
- **Tablet**: 768px - 1199px (2-column grid)
- **Mobile**: <768px (1-column grid)

## 🎭 Animations

- **Fade-in-up**: Elemen muncul dari bawah saat scroll
- **Hover effects**: Cards dan buttons
- **Smooth transitions**: Semua interaksi
- **Scroll effects**: Navbar transparency dan shadow
- **Mobile menu**: Smooth toggle animation

## 🔒 Security & Performance

- **Security headers**: XSS protection, content type options
- **HTTPS redirect**: Force secure connections
- **Gzip compression**: Reduced file sizes
- **Browser caching**: Faster subsequent visits
- **Optimized assets**: Minified CSS and JS
- **Mobile-first**: Responsive design approach

## 🔧 Setup & Installation

1. **Clone repository**
   ```bash
   git clone [repository-url]
   cd pakHikmat
   ```

2. **Setup database**
   - Import database structure
   - Update `config.php` dengan kredensial database

3. **Upload ke server**
   - Upload semua file ke web server
   - Pastikan PHP dan MySQL terinstall

4. **Konfigurasi**
   - Update informasi sekolah di file PHP
   - Ganti logo di `assets/images/logo.png`

## 🎨 Customization

### Mengubah Warna
Edit file `assets/css/style.css`:
```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --text-primary: #1a1a1a;
  --text-secondary: #666;
}
```

### Mengubah Font
Update Google Fonts link di header:
```html
<link href="https://fonts.googleapis.com/css2?family=YourFont:wght@400;500;600;700&display=swap" rel="stylesheet">
```

## 📚 Documentation

- [CHANGELOG.md](CHANGELOG.md) - History perubahan project
- [CONTRIBUTING.md](CONTRIBUTING.md) - Panduan kontribusi
- [SECURITY.md](SECURITY.md) - Kebijakan keamanan
- [LICENSE](LICENSE) - MIT License

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/smkn64jakarta/website.git
cd website

# Setup local server
php -S localhost:8000

# Open browser
open http://localhost:8000
```

## 📞 Support

Untuk pertanyaan atau bantuan teknis, silakan hubungi:
- Email: info@smkn64jkt.sch.id
- Telepon: (021) 809-1234
- GitHub Issues: [Buat Issue](https://github.com/smkn64jakarta/website/issues)

## 🤝 Contributing

Kami menyambut kontribusi dari siapa saja! Silakan baca [CONTRIBUTING.md](CONTRIBUTING.md) untuk panduan lengkap.

## 📄 License

© 2024 SMK Negeri 64 Jakarta. All rights reserved.

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Dibuat dengan ❤️ untuk SMK Negeri 64 Jakarta** 