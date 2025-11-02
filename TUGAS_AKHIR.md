# TUGAS AKHIR - GIT WORKFLOW PORTFOLIO WEBSITE

**Nama:** Riski Jaya Putra  
**Tanggal:** 3 November 2024

## 📋 RINGKASAN TUGAS

Tugas ini mendemonstrasikan workflow Git yang lengkap untuk project portfolio website, termasuk:
- Inisialisasi Git repository
- Commit bertahap untuk setiap section
- Branching untuk eksperimen styling
- Merging branch
- Push ke GitHub dengan README yang informatif

---

## ✅ CHECKLIST PENYELESAIAN

### 1. ✓ Inisialisasi Git untuk Project Portfolio
```bash
git init
```
Repository berhasil diinisialisasi di folder `1.2`

### 2. ✓ Commit Bertahap untuk Setiap Section

**Commit 1:** Add HTML structure and navigation
- File: `index.html`
- Commit Hash: `5f05cf0`

**Commit 2:** Add hero section with profile image
- File: `assets/Profile.png`
- Commit Hash: `191e84a`

**Commit 3:** Add certificate section with images
- File: `assets/*.jpg` (5 gambar sertifikat)
- Commit Hash: `f4ed648`

**Commit 4:** Add base styling and layout
- File: `style.css`
- Commit Hash: `1d56bd4`

### 3. ✓ Buat Branch untuk Eksperimen Styling Baru

```bash
git checkout -b experimental-styling
```

**Perubahan yang dilakukan:**
- Menambahkan animated gradient pada section title
- Mengubah background body dengan gradient dinamis
- Meningkatkan styling navigation dengan glassmorphism effect
- Menambahkan hover animation pada navigation links

**Commit:** Experiment: Add animated gradients and enhanced navigation styling
- Commit Hash: `5946181`

### 4. ✓ Merge Branch Setelah Styling Selesai

```bash
git checkout main
git merge experimental-styling
```

Branch `experimental-styling` berhasil di-merge ke `main` dengan fast-forward merge.

### 5. ✓ Push ke GitHub dan Buat README.md

**README.md dibuat dengan konten:**
- Deskripsi proyek lengkap
- Fitur-fitur website
- Langkah instalasi dan penggunaan
- Struktur folder
- Teknologi yang digunakan
- Informasi author dan contact

**Push ke GitHub:**
```bash
git remote add origin https://github.com/RiskiJayaPutra/Praktikum-Pemrograman-Web.git
git push -u origin main
```

---

## 📊 GIT LOG GRAPH

```
*   a086c79 (HEAD -> main, origin/main) Merge with remote, keep local README
|\
| *   d36a8d9 Merge branch 'main' of https://github.com/RiskiJayaPutra/Praktikum-Pemrograman-Web
| |\
| | * cf811ad TA Judul 1
| | * da0e0a2 TA judul 1
| | * 289c3ea first commit
| * 5abb8b8 Add TP files
| * c2ecfa5 Judul 2
* 90fd432 Add comprehensive README documentation
* 5946181 (experimental-styling) Experiment: Add animated gradients and enhanced navigation styling
* 1d56bd4 Add base styling and layout
* f4ed648 Add certificate section with images
* 191e84a Add hero section with profile image
* 5f05cf0 Add HTML structure and navigation
```

---

## 🔗 LINK REPOSITORY GITHUB

**Repository URL:** https://github.com/RiskiJayaPutra/Praktikum-Pemrograman-Web

**Status:** ✓ Public Repository

---

## 📁 FILE YANG DIKUMPULKAN

1. ✓ **Tautan repository GitHub** (public) - https://github.com/RiskiJayaPutra/Praktikum-Pemrograman-Web
2. ✓ **Screenshot hasil perintah `git log --graph --oneline`** - Tersedia di atas
3. ✓ **File README.md** - Tersedia di repository dengan dokumentasi lengkap

---

## 🎯 HASIL PEMBELAJARAN

Melalui tugas ini, saya telah mempelajari dan mempraktikkan:

1. **Git Basics**
   - Inisialisasi repository
   - Staging dan commit changes
   - Melihat history dengan git log

2. **Git Branching**
   - Membuat branch baru untuk development
   - Bekerja pada branch terpisah
   - Merge branch ke main branch

3. **Remote Repository**
   - Menambahkan remote repository
   - Push changes ke GitHub
   - Menangani merge conflicts

4. **Best Practices**
   - Commit messages yang deskriptif
   - Commit bertahap untuk setiap fitur
   - Branching untuk eksperimen
   - Dokumentasi yang baik dengan README

5. **Workflow Development**
   - Feature branch workflow
   - Testing pada branch terpisah
   - Merge setelah testing berhasil

---

## 💡 KESIMPULAN

Workflow Git yang diterapkan pada project portfolio ini menunjukkan praktik development yang baik dengan:
- Commits yang terorganisir dan bermakna
- Branching untuk eksperimen yang aman
- Dokumentasi yang comprehensive
- Version control yang proper

Project ini siap untuk dikembangkan lebih lanjut dengan workflow yang sama.

---

**© 2024 Riski Jaya Putra - Praktikum Pemrograman Web**
