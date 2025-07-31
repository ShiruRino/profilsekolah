# Security Policy

## Supported Versions

Use this section to tell people about which versions of your project are currently being supported with security updates.

| Version | Supported          |
| ------- | ------------------ |
| 1.0.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

Kami sangat menghargai laporan kerentanan keamanan dari komunitas. Untuk melaporkan kerentanan keamanan:

### 🚨 Langkah-langkah Pelaporan

1. **JANGAN** buat issue publik untuk kerentanan keamanan
2. **JANGAN** diskusikan kerentanan di forum publik
3. **HUBUNGI** kami secara langsung melalui email

### 📧 Kontak Keamanan

**Email Keamanan**: security@smkn64jkt.sch.id

**Subject**: `[SECURITY] Vulnerability Report - [Nama Kerentanan]`

### 📋 Informasi yang Diperlukan

Saat melaporkan kerentanan, mohon sertakan:

1. **Deskripsi kerentanan** yang jelas dan detail
2. **Steps to reproduce** (langkah-langkah untuk mengulang)
3. **Impact assessment** (dampak kerentanan)
4. **Proof of concept** (jika memungkinkan)
5. **Suggested fix** (solusi yang disarankan)
6. **Contact information** (informasi kontak Anda)

### ⏱️ Timeline Response

- **24 jam**: Konfirmasi penerimaan laporan
- **72 jam**: Update status investigasi
- **7 hari**: Rilis patch (jika diperlukan)
- **30 hari**: Rilis publik (setelah patch)

### 🔒 Responsible Disclosure

Kami mengikuti prinsip **Responsible Disclosure**:

- Berikan waktu yang cukup untuk memperbaiki kerentanan
- Jangan eksploitasi kerentanan untuk keuntungan pribadi
- Jangan akses atau modifikasi data tanpa izin
- Jangan lakukan serangan DoS/DDoS

### 🛡️ Security Measures

Website ini telah dilengkapi dengan:

- **HTTPS enforcement** - Semua koneksi dienkripsi
- **Security headers** - XSS protection, content type options
- **Input validation** - Validasi semua input user
- **SQL injection protection** - Prepared statements
- **CSRF protection** - Token-based protection
- **File upload restrictions** - Validasi file uploads
- **Error handling** - Tidak menampilkan error sensitif

### 🔍 Security Audit

Kami secara berkala melakukan:

- **Code review** - Review kode untuk kerentanan
- **Dependency updates** - Update dependencies
- **Penetration testing** - Testing keamanan
- **Security monitoring** - Monitoring aktivitas mencurigakan

### 📚 Security Resources

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [PHP Security Guide](https://www.php.net/manual/en/security.php)
- [Web Security Best Practices](https://developer.mozilla.org/en-US/docs/Web/Security)

### 🙏 Acknowledgments

Kami akan mengakui kontributor keamanan di:

- [CHANGELOG.md](CHANGELOG.md)
- [README.md](README.md)
- Website resmi

---

**Note**: Kebijakan keamanan ini dapat diperbarui dari waktu ke waktu. Silakan periksa secara berkala. 