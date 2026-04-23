# 🤖 Sosmed Tools Pro - AI Album Maker Ultimate 🚀

![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)
![PySide6](https://img.shields.io/badge/GUI-PySide6-green)
![FFmpeg](https://img.shields.io/badge/Render-FFmpeg-red)
![OpenAI](https://img.shields.io/badge/AI-OpenAI-lightgrey)

# Sosmed Tools Pro - Broadcast Dashboard 🤖🎥

**Sosmed Tools Pro** adalah solusi automasi berbasis Python yang dirancang untuk membantu kreator konten membangun video kompilasi musik berkualitas tinggi secara instan. Alat ini menggabungkan kekuatan AI (GPT-3.5 & DALL-E 3) dengan mesin render FFmpeg yang dioptimalkan untuk performa tinggi.

## ✨ Fitur Utama

* **Asisten Kreatif AI Terintegrasi**: Menggunakan OpenAI GPT-3.5 untuk merancang judul album yang puitis dan ikonik, serta DALL-E 3 untuk men-generate cover art berkualitas tinggi (rasio 16:9 atau 9:16) secara otomatis.
* **Efek Visual Sinematik**: Mendukung berbagai mode animasi cover termasuk *Slow Zoom*, *Denyut Cahaya*, *Berputar*, dan *Blur Background* untuk estetika video yang modern.
* **Sistem Lirik/Karaoke Otomatis**: Menampilkan daftar putar di layar dengan efek highlight "Karaoke" yang sinkron dengan lagu yang sedang berjalan.
* **Generasi YouTube Chapters**: Otomatis menciptakan file `.txt` berisi timestamp lagu yang siap digunakan untuk fitur Chapters di deskripsi YouTube.
* **Optimasi Audio & Hardware**:
    * **Normalisasi Volume**: Memastikan audio konsisten pada standar digital (-14 LUFS).
    * **Akselerasi GPU**: Dukungan penuh untuk *NVIDIA NVENC* guna proses rendering yang jauh lebih cepat.
    * **Manajemen CPU**: Opsi kontrol penggunaan core CPU untuk menjaga suhu perangkat saat rendering.

## 🛠️ Persyaratan Sistem

Sebelum menjalankan aplikasi, pastikan sistem Anda memiliki komponen berikut:

1.  **Python 3.8+**
2.  **FFmpeg & FFprobe**: Wajib terinstal di sistem dan terdaftar dalam Environment Path (PATH).
3.  **OpenAI API Key**: Dibutuhkan jika Anda ingin menggunakan fitur otomatisasi judul dan gambar.

## 🚀 Instalasi

1.  Clone atau unduh repository ini.
2.  Buka terminal atau command prompt di direktori proyek.
3.  Instal pustaka yang dibutuhkan:
    ```bash
    pip install -r requirements.txt
    ```

## 📖 Cara Penggunaan

1.  Jalankan aplikasi dengan perintah:
    ```bash
    python v1.py
    ```
2.  **Input API Key**: Masukkan OpenAI API Key Anda di kolom yang tersedia (tersimpan secara otomatis).
3.  **Tambahkan Lagu**: Gunakan tombol **+ File MP3** atau **Folder** untuk menyusun playlist. Anda dapat mengatur urutan lagu dengan fitur *drag & drop*.
4.  **Konfigurasi Visual**:
    * Klik **Auto Generate** untuk membiarkan AI menentukan judul dan cover.
    * Atur font, mode animasi, dan format layar (16:9 untuk YouTube atau 9:16 untuk Reels/TikTok).
5.  **Render**: Pilih lokasi output dan klik **MULAI RENDER & EXPORT**.

## 📝 Lisensi
Proyek ini dikembangkan untuk penggunaan profesional dalam automasi konten media sosial.
