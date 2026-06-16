# Monop v0.5 (beta)

by **reiz_riz** · [github.com/rixz-dev](https://github.com/rixz-dev)

> Taktik. Perdagangan. Dominasi. Permainan Monopoli berbasis browser dengan AI bot aktif, aturan resmi, dan desain pixel-dark minimalis.

## Stack
- HTML5, CSS3, Vanilla JavaScript
- Static hosting (Vercel compatible)
- No framework — banyak file, modular

## Fitur
- **3 Tingkat Kesulitan Bot**: Easy, Medium, Hard (agresif & optimal)
- **Aturan Resmi Monopoli**: Dadu kembar, penjara, lelang, monopoly, sewa, kartu Chance & Community Chest, bangkrut, dll.
- **Pengaturan Lengkap**: Bahasa (ID/EN), tema dark/light, kecepatan game, suara, animasi dadu, Free Parking jackpot, lelang on/off, uang awal.
- **Lobby**: New Game, Settings, Support Author (saweria.co/riznotdev)
- **Human Actions**: Beli, lelang, bangun rumah/hotel, gadai, tebus gadai, perdagangan antar pemain/bot.
- **Desain**: Pixel typography, dark mode default, animasi glitch & dice, 2 warna sync (amber + teal).

## Deploy ke Vercel
1. `git init && git add . && git commit -m "init"`
2. Push ke GitHub
3. Import repo ke Vercel → deploy sebagai **Static Site**

## Catatan
- Dioptimalkan untuk layar desktop (landscape).
- Tidak mendukung orientasi vertikal mobile.
- Semua state disimpan di `localStorage` untuk settings.
