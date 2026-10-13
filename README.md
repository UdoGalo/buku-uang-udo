# Buku Uang Udo (PWA)

File aplikasi web untuk dipublikasikan sebagai GitHub Pages.

## File yang diperlukan
- `index.html` — aplikasi pembukuan
- `manifest.json` — metadata instalasi PWA
- `sw.js` — service worker/cache offline
- `icon.svg` — ikon aplikasi

## Catatan
Aplikasi menyimpan transaksi pada penyimpanan lokal browser (`localStorage`). Data tidak otomatis tersinkronisasi antarperangkat. Ekspor cadangan secara berkala. Jangan memasukkan PIN/password bank.
