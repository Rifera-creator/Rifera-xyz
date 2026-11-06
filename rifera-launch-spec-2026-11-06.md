# Rifera — Launch Spec (keputusan per 2026-11-06, 12:11 WIB)

Satu halaman ringkas dari semua keputusan yang sudah disetujui user hari ini,
supaya tidak hilang saat kontrak asli dibangun. Ini BUKAN kontrak — harga dan
aturan di bawah ini baru hidup di situs contoh (`rifera-nft`); kontrak asli
belum dibuat dan alamat kontrak baru belum ditetapkan.

## Koleksi
- Nama: Rifera First Take — 7,620 takes, bernomor #1–#7,620, nomor tidak pernah berubah.
- Pixel art: kursor panah (arrow pointer) yang bersih, beda tiap take.
- Domain final BEDA dari rifera.org (belum ditentukan — jangan hardcode rifera.org).

## Mint (Fase 1)
- Post dulu, baru mint (post-first wajib — jalur mint langsung tanpa post sudah dihapus atas keputusan user).
- Binance Agent ID wajib untuk mint.
- Mint pertama per wallet: FREE (gas only).
- Extra mint: **0,002 BNB** per NFT, tanpa max (disetujui user 2026-11-06 11:20 WIB; sebelumnya 0,0002 BNB).
- Mint di situs utama (repo `Rifera-creator/Rifera`, main) masih NONAKTIF sampai alamat kontrak baru dipasang.

## Upgrade (Fase 2 — dibuka setelah mint jalan)
- Max **Level 5**. Naik 1 level = 0,002 BNB. Total dari Lv 1: Lv 2 = 0,002 · Lv 3 = 0,004 · Lv 4 = 0,006 · Lv 5 = 0,008 BNB.
- Yang berubah hanya visual (Lv 2 Glow, Lv 3 REC Live, Lv 4 Prism, Lv 5 Genesis Max). Nomor take, pemilik, bentuk panah, dan supply 7,620 tidak berubah.

## Token (nanti, setelah mint)
- Pembagian pool per level: Lv 1 = 5% · Lv 2 = 10% · Lv 3 = 20% · Lv 4 = 30% · Lv 5 = 35%. Berbayar total 95%.
- **NO SNAPSHOT — direct claim.** Kepemilikan & level dibaca live saat claim.
- Claim fee: **0,00021 BNB** per take + gas, dibayar sekali per take yang diclaim.
- Upgrade dulu sebelum claim: begitu satu take sudah claim, claim-nya selesai.
- BELUM diputuskan: nama token, total supply token, tanggal launching/claim.

## Belum diputuskan / hanya saran
- Royalty secondary 5% — disarankan asisten, user belum menyetujui.
- Token sendiri + listing (model Agent Arena) — dibahas, belum diputuskan; risikonya lebih besar dari fee mint.

## Referensi Agent Arena (dicek 2026-11-06)
- Mint SEAT gratis, claim 250.000 ARENA/seat, fee claim 0,00023166 BNB.
- Listing ARENA di PancakeSwap: Sabtu 7 Nov 2026, 00:00 UTC (07:00 WIB). Saat dicek belum ada link PancakeSwap di agentarena.id.
- Kontrak ARENA resmi: `0xfb83Bc181eE3356B403d09540b501bdc3C42c211` — hati-hati token ARENA palsu.

## Status situs contoh
- Semua angka di atas sudah diterapkan di artifact `rifera-nft` (terakhir diubah 2026-11-06 12:01 WIB: background, tombol, dan copy pendek gaya Rifera sendiri).
- Verifikasi file 2026-11-06 12:11 WIB: tidak ada lagi "0,0002 BNB" di `index.html`; 0,002 BNB ×24, 0,00021 BNB ×14, Level 5 ×27.
