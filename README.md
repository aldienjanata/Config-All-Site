# Config All Site — Wifian Solution Cabang Banyumas

OLT ZTE C300 Bulk Config Generator untuk provisioning GPON ONT.

## Fitur
- Generate script config OLT ZTE C300 secara massal
- Support 5 site: Cilacap, Karangputat, Banyumas, Rowokele, Kebumen
- VLAN & Profile otomatis per site/pelanggan
- Perpindahan PON (auto-delete old PON)
- Pilihan tipe ONT: ZTE / All ONT per pelanggan
- Mode gelap & terang
- Responsive mobile (card layout)
- PWA — bisa diinstall sebagai aplikasi di HP

## Deploy ke Vercel

1. Push repo ini ke GitHub
2. Buka [vercel.com](https://vercel.com) → Import Git Repository
3. Pilih repo ini → Deploy
4. Selesai! Buka URL Vercel di HP → "Add to Home Screen"

## Struktur File
```
├── index.html       # Aplikasi utama
├── manifest.json    # PWA manifest
├── sw.js            # Service Worker (offline support)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
├── vercel.json      # Konfigurasi Vercel
└── README.md
```

## Cara Pakai
1. Pilih site (tab atas)
2. Isi data pelanggan (bisa banyak sekaligus)
3. Pilih tipe ONT: **ZTE** atau **All ONT**
4. Klik **Generate Script**
5. Copy script yang dihasilkan ke terminal OLT / MikroTik

---
© Wifian Solution Cabang Banyumas
