# 2048 — Gabungkan Blok Angka

Game puzzle sederhana berbasis HTML, CSS, dan JavaScript murni. Geser blok angka di papan 4×4, gabungkan angka yang sama, dan capai **2048**!

![Preview Game](screenshot.png)

## Fitur

- **Papan 4×4** dengan animasi geser dan merge yang halus.
- **Kontrol lengkap**:
  - Desktop: tombol panah `↑` `↓` `←` `→`
  - Mobile: swipe (geser) ke atas, bawah, kiri, kanan
  - Restart cepat: tekan tombol `R`
- **Skor & skor terbaik** — skor terbaik disimpan otomatis di `localStorage`.
- **Overlay Game Over** dengan tombol "Coba Lagi".
- **Overlay Menang** saat mencapai 2048, dengan opsi "Lanjutkan" untuk terus bermain.
- **Warna tile berubah** sesuai nilai: 2, 4, 8, 16, …, 8192.
- **Responsif** — tampil optimal di desktop maupun mobile.
- **Tanpa dependency eksternal** — cukup satu file HTML.

## Cara Menjalankan

1. Download atau salin file `2048.html` (atau nama lain yang Anda pilih).
2. Buka file tersebut di browser modern (Chrome, Firefox, Edge, Safari).
3. Langsung bisa dimainkan — tidak perlu server atau instalasi.

Atau, jika ingin menjalankan via server lokal:

```bash
# Python 3
python -m http.server 8000

# Node.js (dengan npx)
npx serve .

# PHP
php -S localhost:8000
