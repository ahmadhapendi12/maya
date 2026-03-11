# Portfolio Hafidz Quran - Panduan Lengkap

## 📌 Deskripsi Website

Website portfolio ini dirancang untuk seorang mahasantri yang sedang menghafal 30 juz Al-Quran di pondok pesatren. Desain tema hitam biru yang premium dengan animasi hidup, dilengkapi bacaan Arabic, asbabun nuzul, dan detail lainnya.

## 🎨 Fitur Website

1. **Hero Section** - Foto profil dengan badge hafidzah, progress menghafal 30 juz, dan achievement badges
2. **Kata-Kita Motivasi** - Kutipan dari Al-Quran dengan:
   - Bacaan Arabic asli
   - Arti Indonesia
   - Asbabun Nuzul (sejarah turunnya ayat)
   - Kandungan ayat
3. **Galeri Foto** - 3 momen spesial dengan efek hover
4. **Target Hafalan** - 6 bagian juz dengan tracker visual (bisa diklik untuk toggle status)
5. **Aktivitas Harian** - Jadwal harian santr
6. **Tentang Saya** - Perkenalan diri dengan 3 kartu
7. **Kontak** - Link sosial media (Instagram, TikTok, YouTube, WhatsApp)
8. **Footer** - Doa Arabic dan kutipan Al-Quran

---

## ✏️ Cara Mengedit Konten

### 1. Mengganti Nama
Buka `index.html` dan cari:
```html
<h1 class="name">Nama Anda</h1>
```
Ganti "Nama Anda" dengan nama Anda.

### 2. Mengganti Foto
Siapkan 3 foto:
- Format: JPG/PNG
- Rekomendasi: Foto vertikal atau square, background bersih
- Nama file: `foto1.jpg`, `foto2.jpg`, `foto3.jpg`

Simpan di folder yang sama dengan `index.html`.

### 3. Mengedit Progress Hafalan (bagian atas)
```html
<p class="progress-text"><span id="progress-percent">0</span>% Selesai</p>
```
Ubah nilai `targetPercent` di bagian JavaScript (baris ~320):
```javascript
const targetPercent = 0; // Ubah ke 10, 20, 30, dll
```

### 4. Klik Status Juz untuk Mengupdate
Klik tombol "Dalam Proses" pada setiap kartu juz untuk mengubah menjadi "✓ Selesai". Progress circle akan otomatis terupdate.

### 5. Mengedit Link Sosial
```html
<a href="https://instagram.com/username" class="social-btn instagram">
```
Ganti `#` dengan link asli.

### 6. Mengedit About & Kontak
Sesuaikan deskripsi di section "Tentang Saya" dan informasi kontak.

---

## 🚀 Cara Deploy ke Vercel

### Cara 1: Lewat GitHub (Recommended)

1. **Buat GitHub Repository:**
   - Buka [GitHub.com](https://github.com)
   - Klik "New Repository"
   - Beri nama: `portfolio-hafidz`
   - Klik "Create Repository"

2. **Upload File:**
   - Klik "uploading an existing file"
   - Upload: `index.html`, `style.css`, `foto1.jpg`, `foto2.jpg`, `foto3.jpg`
   - Klik "Commit changes"

3. **Deploy ke Vercel:**
   - Buka [Vercel.com](https://vercel.com)
   - Login dengan GitHub
   - Klik "Add New Project"
   - Pilih repository Anda
   - Klik "Deploy"

4. **Selesai!** Dapat link seperti: `portfolio-hafidz.vercel.app`

### Cara 2: Lewat Vercel Drop

1. Buka [Vercel Drop](https://vercel.com/drop)
2. Drag folder yang berisi semua file
3. Tunggu hingga selesai
4. Dapat link langsung!

### Cara 3: Lewat Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Login
vercel login

# Deploy
vercel
```

---

## 📁 Struktur File

```
portfolio-hafidz/
├── index.html      (file utama dengan konten + JavaScript)
├── style.css       (desain/tema + animasi)
├── foto1.jpg       (foto profil & galeri 1)
├── foto2.jpg       (galeri 2)
└── foto3.jpg       (galeri 3)
```

---

## 💡 Tips

- Gunakan foto dengan kualitas baik tapi tidak lebih dari 5MB
- Untuk hasil optimal, gunakan foto dengan background bersih
- Progress Juz bisa diklik untuk menandai selesai

---

## 🤲 Doa

<div align="center">

**رَبَّنَا تَقَبَّلْ مِنَّا إِنَّكَ أَنتَ السَّمِيعُ العَلِيمُ**

*"Ya Tuhan kami, terimalah dari kami. Sesungguhkan Engkau adalah Yang Maha Mendengar lagi Maha Mengetahui."*

(QS. Al-Baqarah: 127)

---

**جَعَلَنِي اللَّهُ مِنَ الْحَافِظِينَ**

*"Semoga Allah menjadikanku termasuk para penghafal"*

</div>

---

## 📞 Bantuan

Jika ada pertanyaan, silakan bertanya!


