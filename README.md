# bedroom

Interactive bedroom portfolio of **Muhammad Indra Darmawan**, Fullstack Developer & AI Engineer (Surabaya). Gayanya kamar remaja Amerika era 2000-an, dan semua barang di kamar bisa diklik.

🔗 **Live:** https://indradarmawan2202.github.io/bedroom/

| Barang | Isi |
|---|---|
| Gig poster "SIGNAL / NOISE", diary di kasur | About me |
| Poster & flyer di dinding | Proyek (Question Generator, EAQE, Learning Report, Affiliate) |
| Rak buku | Skills |
| Konsol 8-bit + TV | Experience ("save files") |
| Flip phone di lantai | Kontak |
| Turntable | Lagu yang sedang kuputar di Spotify (live) |
| Rak piringan / crate | Pilih album → diputar di turntable (Spotify embed) |
| Lava lamp | Mode malam |

Satu file `index.html` (HTML/CSS/JS + SVG), tanpa framework dan tanpa build step. Turntable mengambil data dari Cloudflare Worker `spotify-now` yang sama dengan [situs utama](https://indradarmawan2202.github.io/).

## Edit
- **Album di crate:** array `ALBUMS` di `<script>` (album ID + hash gambar cover Spotify).
- **Isi modal:** objek `P` di `<script>`.
- **Link kontak:** objek `LINKS`.
