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
| Turntable / rak piringan / crate | Pengunjung memilih musik sendiri: ambil album dari crate atau paste link Spotify apa saja (lagu, album, playlist) → diputar lewat Spotify embed |
| Lava lamp | Mode malam |
| Poster & stiker band (Headphone Fest, Arctic Monkeys, Deftones, stiker di ranjang/nakas/skateboard/dinding/kabinet) | Memutar album band itu di turntable |

Satu file `index.html` (HTML/CSS/JS + SVG), tanpa framework dan tanpa build step. Tidak butuh API key: musik diputar lewat Spotify embed, sedangkan judul dan cover untuk link yang di-paste diambil dari Spotify oEmbed.

## Edit
- **Album di crate:** array `ALBUMS` di `<script>` (album ID + hash gambar cover Spotify).
- **Isi modal:** objek `P` di `<script>`.
- **Link kontak:** objek `LINKS`.
