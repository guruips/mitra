# Panduan Kontribusi

Terima kasih telah tertarik untuk berkontribusi pada proyek **Mitra & Kerjasama**! Dokumen ini menjelaskan cara Anda dapat berpartisipasi dalam proyek kami.

## 📋 Daftar Isi

1. [Kode Etik](#kode-etik)
2. [Mulai Berkontribusi](#mulai-berkontribusi)
3. [Proses Kontribusi](#proses-kontribusi)
4. [Standar Kualitas](#standar-kualitas)
5. [Pertanyaan atau Saran](#pertanyaan-atau-saran)

## 🤝 Kode Etik

Proyek kami menerapkan Contributor Covenant Code of Conduct. Dengan berpartisipasi, Anda diharapkan untuk mematuhi kode ini.

### Perilaku yang Diharapkan

- Gunakan bahasa yang sopan dan inklusif
- Hormati pandangan dan pengalaman yang berbeda
- Terima kritik konstruktif dengan baik
- Fokus pada apa yang terbaik untuk komunitas
- Tunjukkan empati terhadap anggota komunitas lain

### Perilaku yang Tidak Dapat Diterima

- Pelecehan atau diskriminasi berdasarkan ras, jenis kelamin, orientasi seksual, dll.
- Serangan pribadi atau komentar merendahkan
- Spam atau konten yang tidak relevan
- Penggunaan bahasa yang tidak pantas atau ofensif
- Segala bentuk bullying atau intimidasi

## 🚀 Mulai Berkontribusi

### 1. Setup Awal

```bash
# Fork repositori di GitHub
# Clone fork Anda ke komputer lokal
git clone https://github.com/USERNAME/mitra.git
cd mitra

# Tambahkan upstream remote
git remote add upstream https://github.com/guruips/mitra.git

# Verifikasi remote
git remote -v
```

### 2. Buat Branch Baru

Buat branch dengan nama yang deskriptif:

```bash
# Update main branch terlebih dahulu
git checkout main
git pull upstream main

# Buat branch baru
git checkout -b feature/nama-fitur
# atau
git checkout -b bugfix/nama-bug
# atau
git checkout -b docs/nama-dokumentasi
```

**Konvensi Nama Branch:**
- `feature/nama-fitur` - untuk fitur baru
- `bugfix/nama-bug` - untuk perbaikan bug
- `docs/nama-docs` - untuk dokumentasi
- `refactor/nama-refactor` - untuk refactoring

## 📝 Proses Kontribusi

### 1. Buat Perubahan

```bash
# Buat perubahan Anda
# Edit atau tambah file sesuai kebutuhan

# Periksa status
git status

# Stage perubahan
git add .
# atau staging file tertentu
git add path/to/file
```

### 2. Commit Perubahan

Follow konvensi commit message kami:

```bash
# Format: [TYPE]: Deskripsi ringkas
git commit -m "feat: Add new learning material for IPS chapter 3"
git commit -m "fix: Resolve typo in documentation"
git commit -m "docs: Update installation guide"
git commit -m "refactor: Improve code structure"
```

**Tipe Commit:**
- `feat:` - Fitur baru
- `fix:` - Perbaikan bug
- `docs:` - Perubahan dokumentasi
- `style:` - Perubahan format (spacing, semicolons, dll)
- `refactor:` - Refactoring code
- `perf:` - Peningkatan performa
- `test:` - Menambah atau update test
- `chore:` - Perubahan build process, dependencies, dll

### 3. Push dan Buat Pull Request

```bash
# Push branch Anda
git push origin feature/nama-fitur

# Buka browser dan buat Pull Request
# dari fork Anda ke main repository
```

**Template Pull Request:**

```markdown
## Deskripsi Perubahan

Jelaskan apa yang Anda ubah dan mengapa.

## Tipe Perubahan

- [ ] Bug fix (non-breaking change yang memperbaiki bug)
- [ ] Fitur baru (non-breaking change yang menambah fitur)
- [ ] Breaking change (perubahan yang membuat functionality sebelumnya tidak kompatibel)
- [ ] Dokumentasi update

## Bagaimana Ini Sudah Ditest?

Deskripsikan test yang telah Anda jalankan:

- [ ] Test A
- [ ] Test B

## Checklist

- [ ] Kode saya mengikuti style guide proyek ini
- [ ] Saya telah melakukan self-review pada kode saya
- [ ] Saya telah menambah komentar pada kode yang kompleks
- [ ] Dokumentasi sudah diupdate sesuai perubahan
- [ ] Perubahan saya tidak membuat warning baru
- [ ] Saya telah menambah test yang membuktikan fix/fitur bekerja

## Screenshot atau Demo (jika ada)

Tambahkan screenshot atau demo video jika relevan.
```

### 4. Review dan Merge

Tim kami akan:
1. Melakukan review pada kode Anda
2. Memberikan feedback jika diperlukan
3. Memerge PR setelah disetujui

## ✅ Standar Kualitas

### Untuk Konten Materi

- ✅ Akurat dan factually correct
- ✅ Relevan dengan kurikulum IPS
- ✅ Bahasanya jelas dan mudah dipahami
- ✅ Disertai referensi dan sumber
- ✅ Sesuai dengan format standar

### Untuk Kode

- ✅ Mengikuti coding standard proyek
- ✅ DRY (Don't Repeat Yourself)
- ✅ SOLID principles
- ✅ Well-commented dan readable
- ✅ Memiliki test coverage minimal 80%

### Untuk Dokumentasi

- ✅ Jelas dan comprehensive
- ✅ Update dengan perubahan terkini
- ✅ Menggunakan examples yang relevan
- ✅ Mudah dicari dan di-navigate
- ✅ Consistent dengan style guide

## ❓ Pertanyaan atau Saran

Jika Anda memiliki pertanyaan atau saran:

1. **GitHub Issues** - Buka issue untuk diskusi
2. **Discussions** - Gunakan GitHub Discussions
3. **Email** - Hubungi kami di contact@catatangurulps.com
4. **Discord** - Bergabung dengan komunitas kami

## 🙏 Terima Kasih!

Terima kasih telah berkontribusi pada proyek kami. Kontribusi Anda sangat berarti untuk kami!

---

Happy Contributing! 🚀
