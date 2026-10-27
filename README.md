# RIZZ BYPASS — Website prototype

Website responsif dengan tema neon biru-hitam dan logo anime RIZZ BYPASS.

## Uji di HP
Buka `index.html` dari browser atau gunakan hosting statis HTTPS. Untuk fitur PWA/service worker, hosting HTTPS disarankan.

## Deploy online
Unggah isi folder ini ke layanan static hosting seperti GitHub Pages, Netlify, atau Cloudflare Pages. Pastikan `index.html`, `manifest.webmanifest`, `sw.js`, dan folder `assets/` berada di root situs.

## Batas fitur saat ini
- Validasi format tautan HTTP/HTTPS.
- Membuka tautan asli di browser.
- Riwayat lokal dan kuota demo tersimpan di perangkat.
- Tidak ada server backend untuk akun owner atau kuota global.
- Tidak otomatis melewati tugas, login, CAPTCHA, paywall, atau pembatasan akses. Browser biasa juga tidak bisa membaca semua redirect lintas-domain.

Sebelum dipublikasikan sebagai layanan sungguhan, tambahkan backend dan autentikasi server untuk fitur akun/kuota. Jangan gunakan kode owner demo sebagai keamanan produksi.
