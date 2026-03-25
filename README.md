# 📚 Perpustakaan Digital UIN Antasari Banjarbaru

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

&gt; Sistem Katalog Buku Digital berbasis web dengan fitur pencarian real-time dan manajemen koleksi untuk Perpustakaan UIN Antasari Banjarbaru.


---

## ✨ Fitur Utama

### 🔍 Pencarian & Filter
- **Pencarian Real-Time** - Filter buku berdasarkan judul, penulis, atau kategori secara instan
- **Filter Kategori** - Sortir buku berdasarkan kategori yang tersedia
- **Sorting** - Urutkan buku (A-Z, Z-A, tahun terbaru/terlama)

### ➕ Manajemen Koleksi
- **Tambah Buku** - Form modal untuk menambahkan buku baru
- **Edit Buku** - Koreksi data buku yang sudah ada
- **Hapus Buku** - Hapus buku dengan konfirmasi keamanan
- **Upload Cover** - Unggah gambar cover dari komputer (tidak hanya URL)

### 💾 Penyimpanan Data
- **LocalStorage** - Data tersimpan permanen di browser (tidak hilang saat refresh)
- **Export JSON** - Download data buku dalam format JSON untuk backup
- **Import JSON** - Upload file JSON untuk restore data

### 🎨 Tampilan & Aksesibilitas
- **Dark Mode / Light Mode** - Toggle tema gelap/terang untuk kenyamanan mata
- **Mode HP / Mode PC** - Switch tampilan mobile/desktop manual
- **Responsive Design** - Tampilan optimal di desktop, tablet, dan mobile
- **Pagination** - Navigasi halaman (5 buku per halaman)

### 📊 Dashboard
- **Statistik Real-Time** - Counter koleksi buku yang update otomatis
- **Toast Notification** - Notifikasi modern (sukses, error, info)

---

## 🚀 Teknologi

| Teknologi | Keterangan |
|-----------|-----------|
| HTML5 | Struktur halaman web |
| CSS3 | Styling, animasi, responsive design, dark mode |
| JavaScript (ES6+) | Logika aplikasi, manipulasi DOM, event handling |
| LocalStorage API | Penyimpanan data permanen di browser |
| FileReader API | Upload gambar & import file JSON |
| Google Fonts | Font typography modern (Plus Jakarta Sans, Outfit) |
| Font Awesome 6 | Icon library |

---

## 📋 Data Buku

| Field | Keterangan | Contoh |
|-------|-----------|--------|
| Judul | Nama lengkap buku | Atomic Habits |
| Penulis | Nama pengarang | James Clear |
| Tahun | Tahun terbit | 2018 |
| Kategori | Genre/klasifikasi | Self-Development |
| Cover | Gambar sampul (URL atau upload) | image.jpg / URL |

---

## 🎯 Cara Penggunaan

### Akses Web
1. Buka file `index.html` di browser (Chrome/Firefox/Edge)
2. Atau akses online melalui GitHub Pages (jika sudah di-deploy)

### Manajemen Buku
| Aksi | Cara |
|------|------|
| **Tambah Buku** | Klik tombol "Tambah Koleksi" → Isi form → Simpan |
| **Edit Buku** | Klik ikon pensil (✏️) di kolom Aksi → Edit → Update |
| **Hapus Buku** | Klik ikon trash (🗑️) → Konfirmasi → Hapus |
| **Cari Buku** | Ketik di kolom pencarian |
| **Filter Kategori** | Pilih kategori di dropdown |
| **Urutkan** | Pilih "Urutkan..." (A-Z, Z-A, Tahun) |

### Pengaturan Tampilan
| Fitur | Cara |
|-------|------|
| **Dark Mode** | Klik tombol "Dark Mode" di pojok kanan atas |
| **Mode HP** | Klik tombol "Mode HP" untuk tampilan mobile |
| **Mode PC** | Klik tombol "Mode PC" untuk tampilan desktop |

### Backup & Restore Data
| Aksi | Cara |
|------|------|
| **Export Data** | Klik ikon download (📥) → Simpan file JSON |
| **Import Data** | Klik ikon upload (📤) → Pilih file JSON → Import |

### Upload Gambar Cover
1. Saat tambah/edit buku, klik "Choose File" di bagian "Gambar Cover"
2. Pilih gambar dari komputer (JPG, PNG, GIF)
3. Preview akan muncul otomatis
4. Klik Simpan/Update

---

## 💡 Tips Penggunaan

- **Data Aman**: Semua data tersimpan di browser Anda (LocalStorage), tidak hilang saat refresh
- **Backup Rutin**: Export data secara berkala untuk backup
- **Gambar**: Ukuran gambar cover disarankan 200x300 pixel untuk hasil optimal
- **Mode HP**: Gunakan Mode HP saat membuka di smartphone untuk tampilan lebih nyaman
- **Dark Mode**: Aktifkan Dark Mode saat menggunakan di malam hari

---

## 🏛️ Tentang Proyek

Dikembangkan untuk keperluan akademik dan pengelolaan perpustakaan digital **UIN Antasari Banjarbaru**.

| | |
|---|---|
| **Developer** | [Rahmad](https://github.com/AhnRahmad) |
| **Institusi** | UIN Antasari Banjarbaru |
| **Tahun** | 2026 |
| **Versi** | Di Update ke Versi 2.0 (Lengkap dengan LocalStorage & Export/Import) daripada sebelumnya. |

---

## 🔄 Changelog

### v2.0 (Update Terbaru)
- ✅ Tambah fitur Edit & Hapus buku
- ✅ Tambah Dark Mode / Light Mode
- ✅ Tambah Mode HP / Mode PC toggle
- ✅ Tambah LocalStorage (data permanen)
- ✅ Tambah Export/Import JSON
- ✅ Tambah Sorting (A-Z, Z-A, Tahun)
- ✅ Tambah Pagination (5 buku/halaman)
- ✅ Tambah Upload Gambar Cover
- ✅ Toast Notification modern

### v1.0 (Rilis Awal)
- ✅ Fitur pencarian & filter
- ✅ Tambah koleksi buku
- ✅ Tampilan responsive
- ✅ Desain biru-kuning profesional

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

## 🙏 Kontribusi & Saran

Jika ada saran atau menemukan bug, silakan hubungi:
- GitHub: [@AhnRahmad](https://github.com/AhnRahmad)
- Email: [tambahkan email Anda]

---

**⭐ Jangan lupa star repository ini jika bermanfaat!**