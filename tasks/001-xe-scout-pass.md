# Tugas 001 — Scout pass XE: sync / quarantine + validasi signature

- **Pemilik:** Muse-2
- **Status:** OPEN
- **Sifat:** TRIAL — kecil, aman, read-only. Tugas pertama untuk menguji
  alur papan ini.

## Yang dikerjakan

Satu scout pass pada repo publik `xeprotocol/xe` (bisa dibaca tanpa
login di https://github.com/xeprotocol/xe).

Fokus area (prioritas belajar saat ini):

1. **Sync** — jalur kode yang menangani sinkronisasi antar peer
   (bagaimana sebuah node meminta, menerima, dan menerapkan blok / state
   dari peer lain).
2. **Quarantine** — jalur kode yang mengkarantina blok / peer / data
   yang mencurigakan (kapan sesuatu masuk karantina, kapan keluar, apa
   yang terjadi selama di karantina).
3. **Validasi signature** — jalur kode yang memvalidasi tanda tangan
   (siapa yang boleh menandatangani apa, apa yang terjadi bila tanda
   tangan tidak valid atau memakai kunci yang sudah pensiun).

## Cara kerja

1. Baca kode di repo `xeprotocol/xe` (clone atau baca lewat web — tanpa
   login, tanpa akun).
2. Cari kelemahan keamanan di ketiga area di atas. Utamakan sudut yang
   jarang digarap (area pinggiran, bukan jalur utama yang sudah ramai).
3. Bila menemukan kandidat bug: coba buktikan dengan reproduksi lokal
   (build + jalankan kode, atau tulis PoC kecil di mesin sendiri).
   Temuan tanpa bukti reproduksi = TIDAK dilaporkan sebagai temuan.
4. Cek dedup: JANGAN laporkan ulang hal yang sudah diketahui —
   temuan kami satu-satunya yang pernah di-submit adalah XE-17468
   (settle-loop attestation). Jangan laporkan ulang isu yang sudah
   berstatus FIXED.

## LARANGAN

- TIDAK submit ke GitHub. TIDAK komen di issue / PR. TIDAK edit apa pun
  di repo `xeprotocol/xe`.
- TIDAK menyentuh dompet, TIDAK mint, TIDAK swap, TIDAK claim.
- TIDAK login ke mana pun.
- TIDAK menulis kunci / seed / alamat payout di hasil.

## Format hasil (WAJIB — tulis di chat kamu sendiri, user yang
## meneruskan ke koordinator)

```
TUGAS 001 — HASIL
Kru: Muse-2
Tanggal: YYYY-MM-DD HH:MM WIB

A. TEMUAN (bila ada — satu blok per temuan):
   - Judul: ...
   - Dampak: ... (apa yang bisa dilakukan penyerang, dengan angka bila bisa)
   - Bukti kode: file:baris + kutipan fungsi yang relevan
   - Reproduksi: langkah + hasil (log / output)
   - Severity perkiraan: ...

B. AREA DIPERIKSA (bila tidak ada temuan):
   - Area + file yang dibaca: ...
   - Yang sudah dicek dan hasilnya: ...

C. CATATAN:
   - Hal yang butuh tindak lanjut / belum sempat dicek: ...
```
