# Bengkel Spesialis Renault M&B — Website

Website profesional untuk Bengkel Spesialis Renault M&B, Jakarta Barat.

## Tech Stack
- **Vite** + **React 18** + **Tailwind CSS 3**
- **Lucide React** (icons)
- Deploy target: **Vercel**

## Quick Start (Local)

```bash
npm install
npm run dev
```

Buka `http://localhost:3000`

## Deploy ke Vercel via GitHub

1. **Push ke GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Bengkel Renault M&B website"
   git branch -M main
   git remote add origin https://github.com/USERNAME/renault-mb-website.git
   git push -u origin main
   ```

2. **Connect di Vercel:**
   - Buka [vercel.com](https://vercel.com) → New Project
   - Import repo GitHub yang baru di-push
   - Framework Preset: **Vite**
   - Build Command: `npm run build`
   - Output Directory: `dist`
   - Klik **Deploy**

3. **Custom Domain (opsional):**
   - Di Vercel dashboard → Settings → Domains
   - Tambahkan domain custom Anda

## Struktur File

```
├── index.html            # Entry point + SEO meta tags + JSON-LD
├── package.json          # Dependencies
├── vite.config.js        # Vite configuration
├── tailwind.config.js    # Tailwind configuration
├── postcss.config.js     # PostCSS configuration
├── public/
│   └── favicon.svg       # Favicon
└── src/
    ├── main.jsx          # React entry point
    ├── App.jsx           # Main website component
    └── index.css         # Global styles + Tailwind + responsive
```

## Kontak Bisnis
- **WhatsApp:** +6281315808614
- **Instagram:** [@mb_renaultspecialist](https://www.instagram.com/mb_renaultspecialist/)
- **Alamat:** Blok 140, Jl. Menara IV No.15, Meruya Sel., Kembangan, Jakarta Barat 11650
