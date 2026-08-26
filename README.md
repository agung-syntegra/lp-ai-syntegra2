# lp-ai-syntegra2

Landing page **Syntegra — Platform AI untuk Profesional & Business Owner** (*Ask. Do. Deliver.*).

Salinan tampilan dari [asisten.syntegra.co.id](https://www.asisten.syntegra.co.id/), dirakit menjadi satu file `index.html` self-contained (CSS & JS di-*inline*).

## Isi
- `index.html` — halaman utama (HTML + CSS + JS asli, inline).

## Menjalankan lokal
```bash
python -m http.server 8899
# buka http://localhost:8899/index.html
```

## Catatan
- Gambar (logo, foto, badge) di-*hotlink* dari `https://asisten.syntegra.co.id/img/`, jadi butuh koneksi internet untuk tampil. Untuk versi 100% offline, unduh aset ke folder `img/` lalu ubah path-nya menjadi relatif.
- Tombol CTA mengarah ke halaman signup Syntegra (`https://syntegra.co.id/task/register`).
