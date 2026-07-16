# Pinjaman BPKB Cepat — Landing Page

Landing page bisnis pinjaman dana jaminan BPKB motor & mobil. Dibangun dengan [Astro](https://astro.build).

## Struktur Project

```
├── public/
│   ├── robots.txt
│   └── sitemap.xml
├── src/
│   └── pages/
│       └── index.astro    ← halaman utama
├── astro.config.mjs
├── package.json
├── tsconfig.json
├── vercel.json
└── .gitignore
```

## Menjalankan di Lokal

```bash
npm install
npm run dev
```

Buka `http://localhost:4321`.

## Build Production

```bash
npm run build
npm run preview
```

## Upload ke GitHub

```bash
git init
git add .
git commit -m "Initial commit - landing page pinjaman BPKB"
git branch -M main
git remote add origin https://github.com/USERNAME/NAMA-REPO.git
git push -u origin main
```

Ganti `USERNAME` dan `NAMA-REPO` sesuai repo GitHub kamu.

## Deploy ke Vercel

1. Buka [vercel.com](https://vercel.com) → **Add New Project**
2. Import repo GitHub yang baru dibuat
3. Vercel otomatis mendeteksi framework **Astro** (berkat `vercel.json`)
4. Klik **Deploy** — selesai dalam 1-2 menit

## Catatan Konfigurasi

- Ganti domain di `astro.config.mjs` (`site:`) dan `public/sitemap.xml` dengan domain asli setelah punya domain custom.
- Ganti nomor WhatsApp di `src/pages/index.astro` (variabel `waNumber`) jika diperlukan.
- Untuk favicon/logo, tambahkan file `favicon.svg` atau `favicon.ico` ke folder `public/`.
- Untuk gambar Open Graph (`og-image.jpg`), tambahkan file gambar ke folder `public/` dengan nama yang sama.
