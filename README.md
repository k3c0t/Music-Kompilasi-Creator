# 🎬 Sosmed Tools Pro: Broadcast Dashboard

[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)
[![PySide6](https://img.shields.io/badge/PySide6-GUI-green.svg)](https://wiki.qt.io/Qt_for_Python)
[![FFmpeg](https://img.shields.io/badge/FFmpeg-Engine-orange.svg)](https://ffmpeg.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-DALL--E%203%20%7C%20GPT--3.5-black.svg)](https://openai.com/)

**Sosmed Tools Pro** adalah antarmuka *dashboard* produksi video dan audio kelas agensi yang dirancang untuk automasi konten media sosial. Aplikasi ini menggabungkan eksekusi *rendering* lokal berkinerja tinggi melalui kontrol murni FFmpeg dengan kemampuan *Generative AI* untuk asisten kreatif, meminimalisir *clutter* dan *logging* pihak ketiga yang tidak perlu.

Aplikasi ini dioptimalkan untuk memproduksi kompilasi musik, *podcast*, atau *faceless video* untuk didistribusikan ke **YouTube (16:9)** maupun platform vertikal seperti **TikTok dan Instagram Reels (9:16)**.

---

## ✨ Sorotan Fitur (Feature Highlights)

### 🧠 Otomatisasi AI Terintegrasi
* **Smart Titling:** Menggunakan GPT-3.5 untuk menganalisis nama artis dan menghasilkan *copywriting* judul album/video yang puitis dan ikonik (tanpa kata klise seperti "Kompilasi").
* **Vector & Pop-Art Cover Generation:** Memanfaatkan DALL-E 3 untuk membuat *cover art* dengan *prompting* otomatis yang berfokus pada ilustrasi vektor atau karikatur resolusi tinggi (16:9 atau 9:16).

### ⚙️ Mesin Render Independen & Bersih
* **Direct FFmpeg Subprocess:** Pemrosesan media dilakukan langsung ke mesin FFmpeg tanpa *wrapper* pihak ketiga, menjaga *pipeline* tetap transparan, mencegah *memory leak*, dan menghilangkan *log* internal yang berantakan.
* **Hardware Acceleration (NVENC):** Dukungan *bypass* langsung ke GPU NVIDIA untuk mempercepat proses *encoding* video secara eksponensial.
* **CPU Core Management:** Kontrol manual untuk alokasi *thread* CPU (*1 Core, 2 Core, 4 Core, Max*). Sangat krusial jika aplikasi di-*deploy* ke VPS atau *environment* dengan kapabilitas termal terbatas.

### 🎛️ Studio Visual & Audio Mastering
* **Dynamic Visual FX:** 7 mode manipulasi latar belakang termasuk *Slow Zoom*, *Breathing Vignette* (Denyut), Putaran Piringan Hitam, dan *Smart Blur*.
* **Karaoke Highlight Engine:** Overlay teks cerdas yang secara otomatis memberikan efek *highlight* menyala pada judul lagu sesuai *timestamp* pemutaran.
* **Auto-Mastering LUFS:** Normalisasi audio otomatis ke standar penyiaran digital murni (`-14 LUFS, True Peak -1.5dB`).
* **YouTube Chapters Exporter:** Otomatis mengekstrak metadata durasi file dan menyusunnya menjadi file teks *timestamp* yang siap disalin.

---
