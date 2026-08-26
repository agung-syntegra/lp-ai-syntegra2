# lp-ai-syntegra2

Landing page **Syntegra — Platform AI untuk Profesional & Business Owner** (*Ask. Do. Deliver.*).

Salinan tampilan dari [asisten.syntegra.co.id](https://www.asisten.syntegra.co.id/), dirakit menjadi satu file `index.html` self-contained (CSS & JS di-*inline*).

## Isi
- `index.html` — halaman utama (HTML + CSS + JS asli, inline).
- `img/` — semua aset (logo, favicon, badge, 8 foto) — lokal, self-contained.
- `package.json` — start command untuk deploy (serve statis di `$PORT`).

## Menjalankan lokal
```bash
npm install
npm start
# atau tanpa Node:
python -m http.server 8899
# buka http://localhost:8899/index.html
```

## Deploy (Railway)
Railway auto-deteksi Node → `npm install` → `npm start` (menyajikan file di `$PORT`).
Setelah deploy, buat domain publik di **Settings → Networking → Generate Domain**.

## Catatan
- Gambar **sudah lokal** di `img/` — halaman fully self-contained, tidak bergantung situs lain.
- `og:image` (meta share sosial) masih menunjuk `https://asisten.syntegra.co.id/img/og-image.jpg` (URL absolut wajib untuk crawler). Ganti ke domain final setelah deploy bila perlu.
- Tombol CTA mengarah ke halaman signup Syntegra (`https://syntegra.co.id/task/register`).
