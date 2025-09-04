# AlphaStar • Cek Tagihan (Static Site)

Situs ultra-ringan untuk mengecek tagihan berdasarkan nama, terhubung ke backend Google Apps Script.

## Konfigurasi
1. Deploy Apps Script sebagai Web App (akses: Anyone with the link).
2. Edit `index.html`, ganti:
   - `CONFIG.SCRIPT_URL` → URL Web App Anda.
   - Meta `canonical`, `og:image`, dan `robots.txt`/`sitemap.xml` → domain final Anda.
3. (Opsional) Tambah `CNAME` untuk domain kustom di GitHub Pages.

## Build & Deploy (GitHub Pages)
- Taruh file di repositori, aktifkan GitHub Pages (branch `main`, folder `/`).
- Pastikan gambar berada di `assets/`.

## Catatan
- Tidak ada library eksternal; performa tetap tinggi (TTFB tergantung hosting).
- SEO: sudah ada meta tag, Open Graph, JSON-LD, `robots.txt`, dan `sitemap.xml`.
