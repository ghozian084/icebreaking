# Pecah Es — ice breaking kelas

Kumpulan ice breaking interaktif untuk siswa SMP dan SMA. Bisa langsung ditampilkan lewat proyektor.

| Permainan | Jenjang | Butuh |
|---|---|---|
| [Tangkap Suku](games/tangkap-suku.html) | SMP | Webcam + internet (atau mouse) |
| [Ini atau Itu?](games/ini-atau-itu.html) | SMP & SMA | Tidak ada, siswa pindah sisi kelas |
| [Roda Kenalan](games/roda-kenalan.html) | SMP & SMA | Tidak ada |

## Cara membuka

- **Tanpa kamera:** cukup klik dua kali `index.html`.
- **Dengan kamera (Tangkap Suku):** browser hanya memberi izin kamera lewat `https` atau `localhost`.
  Jalankan `python3 -m http.server` di folder ini lalu buka `http://localhost:8000`,
  atau aktifkan GitHub Pages untuk repositori ini.

## Menambah ice breaking baru

1. Simpan file HTML di folder `games/`. Pakai `../assets/base.css` agar tampilannya seragam,
   dan tambahkan tautan `<a class="back" href="../index.html">← Menu</a>`.
2. Salin salah satu `<a class="game">` di `index.html`, lalu ubah judul, deskripsi,
   label, dan `data-tags` (`smp`, `sma`, `gerak`, `ngobrol`, `pelajaran`) untuk filter.
