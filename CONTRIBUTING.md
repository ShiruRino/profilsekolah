# Contributing to SMK Negeri 64 Jakarta Website

Terima kasih atas minat Anda untuk berkontribusi pada website SMK Negeri 64 Jakarta! 

## 🚀 Cara Berkontribusi

### 1. Fork Repository
- Fork repository ini ke akun GitHub Anda
- Clone repository yang sudah di-fork ke komputer lokal

### 2. Setup Development Environment
```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/website.git
cd website

# Setup local server
php -S localhost:8000
```

### 3. Buat Branch Baru
```bash
git checkout -b feature/nama-fitur-baru
# atau
git checkout -b fix/nama-bug-fix
```

### 4. Lakukan Perubahan
- Buat perubahan sesuai dengan kebutuhan
- Pastikan kode mengikuti standar yang ada
- Test perubahan di browser

### 5. Commit Perubahan
```bash
git add .
git commit -m "feat: tambah fitur baru"
git push origin feature/nama-fitur-baru
```

### 6. Buat Pull Request
- Buka GitHub dan buat Pull Request
- Jelaskan perubahan yang dilakukan
- Tunggu review dari maintainer

## 📋 Standar Koding

### PHP
- Gunakan PSR-12 coding standards
- Tambahkan komentar untuk fungsi kompleks
- Gunakan nama variabel yang deskriptif

### CSS
- Gunakan BEM methodology untuk naming
- Organisir CSS dengan baik (layout, components, utilities)
- Gunakan CSS custom properties untuk warna dan spacing

### JavaScript
- Gunakan ES6+ features
- Tambahkan error handling
- Gunakan meaningful variable names

### HTML
- Gunakan semantic HTML elements
- Pastikan accessibility (ARIA labels, alt text)
- Validasi HTML

## 🎨 Design Guidelines

### Colors
- Primary: `#667eea` to `#764ba2` (Gradient)
- Text: `#1a1a1a` (Dark), `#666` (Gray)
- Background: `#ffffff` (White), `#f8f9fa` (Light Gray)

### Typography
- Font: Inter (Google Fonts)
- Weights: 400, 500, 600, 700
- Responsive sizing dengan rem units

### Components
- Cards: 16px border radius, subtle shadows
- Buttons: 8px border radius, smooth transitions
- Spacing: Consistent dengan 8px grid system

## 🧪 Testing

### Manual Testing
- Test di berbagai browser (Chrome, Firefox, Safari, Edge)
- Test responsive design di berbagai ukuran layar
- Test accessibility dengan screen reader

### Performance Testing
- Check PageSpeed Insights
- Optimize images dan assets
- Minimize HTTP requests

## 📝 Commit Message Format

Gunakan format berikut untuk commit messages:

```
type(scope): description

[optional body]

[optional footer]
```

### Types
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding tests
- `chore`: Maintenance tasks

### Examples
```
feat(navbar): add mobile menu functionality
fix(contact): resolve form validation issue
docs(readme): update installation instructions
style(css): improve button hover effects
```

## 🐛 Reporting Bugs

Saat melaporkan bug, mohon sertakan:

1. **Deskripsi bug** yang jelas
2. **Steps to reproduce** (langkah-langkah untuk mengulang)
3. **Expected behavior** (perilaku yang diharapkan)
4. **Actual behavior** (perilaku yang terjadi)
5. **Environment** (browser, OS, device)
6. **Screenshots** jika diperlukan

## 💡 Suggesting Features

Saat menyarankan fitur baru:

1. **Jelaskan masalah** yang ingin diselesaikan
2. **Deskripsi solusi** yang diusulkan
3. **Alternatives considered** (alternatif yang sudah dipertimbangkan)
4. **Additional context** (konteks tambahan)

## 📞 Getting Help

Jika Anda membutuhkan bantuan:

- Buka issue di GitHub
- Hubungi tim development
- Email: info@smkn64jkt.sch.id

## 🙏 Thank You

Terima kasih atas kontribusi Anda untuk website SMK Negeri 64 Jakarta!

---

**Note**: Semua kontributor akan dicantumkan di README.md dan CHANGELOG.md 