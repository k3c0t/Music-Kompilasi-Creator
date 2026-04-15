# 🤖 Sosmed Tools Pro - AI Album Maker Ultimate 🚀

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![PySide6](https://img.shields.io/badge/GUI-PySide6-green)
![FFmpeg](https://img.shields.io/badge/Render-FFmpeg-red)
![OpenAI](https://img.shields.io/badge/AI-OpenAI-lightgrey)

**Sosmed Tools Pro** adalah aplikasi desktop *dashboard-style* profesional yang dirancang untuk konten kreator. Aplikasi ini mengotomatiskan pembuatan video kompilasi musik (Full Album) untuk YouTube (16:9) dan Reels/TikTok (9:16) lengkap dengan dukungan *Artificial Intelligence* (AI).

Hanya dengan beberapa klik, aplikasi ini dapat memikirkan judul puitis, menggambar *cover art* bergaya karikatur/vektor, merapikan urutan lagu, dan merendernya menjadi video MP4 dengan animasi ringan tanpa membebani komputer Anda.

---

## ✨ Fitur Utama

### 🧠 1. Asisten Kreatif AI (Terintegrasi OpenAI)
* **Auto-Title Generator:** Menggunakan GPT-3.5 untuk memikirkan judul kompilasi yang puitis, ikonik, dan menarik *views* (tanpa menggunakan kata klise seperti "Kompilasi").
* **Auto-Cover Art:** Menggunakan DALL-E 3 untuk menggambar *cover* album resolusi tinggi (16:9 Landscape) bergaya *vector art, pop-art*, atau karikatur yang aman dari pelanggaran *deepfake* publik figur.

### 🎵 2. Manajemen Playlist Cerdas
* **Drag & Drop:** Masukkan file MP3 atau seluruh folder dengan mudah. Geser untuk mengatur urutan.
* **Auto-Numbering & Auto-Clean:** Otomatis membersihkan nama file (menghapus *underscore*) dan memberikan nomor urut pada daftar.
* **Auto YouTube Chapters:** Otomatis membuat file teks (*timestamps*) berisi urutan menit dan detik lagu untuk di-*copy-paste* ke deskripsi YouTube.

### 🎬 3. Studio Visual & Efek Animasi
* **Teks Anti-Tenggelam:** Judul utama dilengkapi *outline* hitam tebal, dan daftar putar dilengkapi *background* kotak hitam transparan elegan bergaya Spotify.
* **Berbagai Pilihan Animasi Latar:**
  * ✨ **Animasi Slow Zoom:** Efek *Ken Burns* sinematik (Rekomendasi: ukuran file super kecil).
  * 🫁 **Animasi Denyut Cahaya:** Layar bernapas (*brightness* naik-turun perlahan).
  * 💿 **Animasi Berputar:** Gaya putaran piringan hitam (*vinyl*).
  * ↔️ **Stretch Layar:** Menarik *cover* AI secara *full* resolusi tanpa tepian hitam.
  * 🌫️ **Blur, Fit, & Fill** untuk *cover art* standar.

### ⚙️ 4. Mesin Render FFmpeg Tingkat Lanjut
* **Akselerasi GPU (NVIDIA NVENC):** Render kilat memotong waktu tunggu secara drastis (bagi pengguna kartu grafis NVIDIA).
* **Thermal Control (Kontrol Suhu CPU):** Pilihan penggunaan daya prosesor (1 Core, 2 Core, 4 Core, atau Max Core) agar laptop tidak *overheat* saat merender tanpa GPU.
* **Auto-Compression:** Otomatis membatasi *bitrate* video (`-crf 28` / `-cq 28`) agar hasil video berjam-jam tidak bengkak hingga bergiga-giga.
* **Audio Normalization:** Menyamakan volume seluruh lagu ke standar YouTube/Spotify (-14 LUFS).
* **Audio Spectrum:** Pilihan memunculkan gelombang suara bereaksi terhadap musik (opsional, menghasilkan ukuran file yang lebih besar).

---

## 🛠️ Persyaratan Sistem

Sebelum menjalankan aplikasi ini, pastikan komputer Anda telah memenuhi persyaratan berikut:

1. **Python 3.8** atau versi lebih baru.
2. **FFmpeg** terinstal dan telah ditambahkan ke sistem PATH komputer Anda. (Cari tutorial: *"How to install FFmpeg on Windows/Mac"*).
3. **Koneksi Internet** (Dibutuhkan jika ingin menggunakan fitur AI).
4. **OpenAI API Key** (Dibutuhkan untuk *auto-generate* judul dan *cover* gambar).

---
