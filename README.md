# Executive Summary — Survei Kepuasan & Employee Experience Pegawai LAZNAS IZI 2026

Dashboard analitik interaktif hasil survei kepuasan pegawai LAZNAS IZI 2026.

## 📊 Konten

- **9 Seksi Lengkap**: Profil Responden, EEI, Tren 2024–2026, Analisis Komparatif, Heatmap, Key Insights, Triangulasi, Matriks Prioritas, dan Rekomendasi Strategis
- **N = 205** responden valid (data survei Juli–Agustus 2026)
- **Employee Experience Index**: 2,93/4,00 = 73,25%
- **Skala pengukuran**: Likert 1–4

## 🚀 Deploy ke Vercel

1. Upload file ke repository GitHub
2. Hubungkan repo ke [vercel.com](https://vercel.com)
3. Vercel akan otomatis mendeteksi sebagai static site
4. Deploy — selesai!

## 📁 Struktur File

```
├── Executive_Summary_Survei_IZI_2026.html   # Dashboard utama (standalone)
├── vercel.json                               # Konfigurasi routing Vercel
└── README.md                                 # Dokumentasi ini
```

## ⚙️ Teknis

- **Pure HTML/CSS/JS** — tidak butuh server, framework, atau build step
- **Chart.js 4.4.1** via CDN (cdnjs.cloudflare.com)
- **Logo IZI** embed sebagai Base64 — tidak ada external image request
- **Fully responsive** — mobile (≤480px), tablet (≤768px, ≤1024px), desktop
- **No external dependencies** selain Chart.js CDN

## 🔒 Catatan

Laporan ini bersifat **konfidensial** — hanya untuk internal manajemen LAZNAS IZI.

---
©2026 Divisi SRD (System, Research & Development) LAZNAS IZI
