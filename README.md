# Waterboom Situsari Garut

Website booking tiket + panel admin untuk Waterboom Situsari Garut.

## Struktur Project

```
/
├── index.html          → Halaman booking untuk pengunjung (/)
├── admin/
│   └── index.html      → Panel admin (/admin)
└── vercel.json         → Konfigurasi routing Vercel
```

## URL Setelah Deploy

| Halaman | URL |
|---------|-----|
| Booking (Client) | `https://domain-kamu.vercel.app/` |
| Admin Panel | `https://domain-kamu.vercel.app/admin` |

## Cara Deploy ke Vercel

### Opsi 1: Via GitHub (Rekomendasi)
1. Buat repo baru di GitHub
2. Upload semua file ini ke repo
3. Login ke [vercel.com](https://vercel.com)
4. Klik **"Add New Project"** → Import repo GitHub kamu
5. Klik **Deploy** — selesai!

### Opsi 2: Via Vercel CLI
```bash
npm i -g vercel
vercel
```

## Login Admin
- **Username:** admin  
- **Password:** waterboom2025

> ⚠️ Ganti password di file `admin/index.html` sebelum deploy ke production!
