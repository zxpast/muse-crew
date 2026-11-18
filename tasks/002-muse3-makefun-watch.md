# Tugas 002 — Watch pass make.fun: kompetisi baru + status entry + pelajaran peringkat atas

- **Pemilik:** Muse-3
- **Status:** DITUTUP
- **Catatan:** Ditutup 19 Nov 2026 00:20 WIB atas keputusan user — papan multi-Muse JEDA, jangan kerjakan lagi.
- **Sifat:** Tugas pertama Muse-3. Read-only, tanpa login, tanpa submit.
  Satu pass pantau make.fun dari halaman / API publik saja.

## Yang dikerjakan

1. **Kompetisi BARU** — cek kompetisi make.fun yang baru muncul sejak
   18 Nov 2026 (halaman publik / API publik make.fun). Untuk tiap
   kompetisi baru catat: slug, total hadiah, tanggal tutup, syarat masuk
   (ada fee? butuh akun khusus?).
2. **Status entry kita** — cek leaderboard publik untuk akun
   swift-pika-45 (HANYA baca, tanpa login). Entry yang dicek:
   - ai-excited-01 (R4)
   - best-game-01 (R3 = entry final; R4 = status kuota submit)
   - gta6-01 (R3)
   - threejs-fps-02
   - gta6-twitch-ccu-forecast-01
   - news-image-20261117
   - news-image-20261118
   - bring-the-humans-02
   Untuk tiap entry catat: rank + total peserta + status grading +
   hadiah di rank kita (kalau ada).
3. **Kuota submit akun** — cek day cap / hard limit akun bila terlihat
   dari halaman publik.
4. **Pelajaran dari peringkat atas** — pelajari SATU kompetisi, lihat
   entry peringkat 1–3: apa yang bikin mereka menang. Yang dicari adalah
   kualitas entry (ide, eksekusi, presentasi) — BUKAN cara mengakali
   grader / scorer / judge.

## Catatan koordinator (angka yang sudah diketahui — pakai sebagai
## pembanding, verifikasi ulang dari halaman publik bila bisa)

- ai-excited-01 R4: sudah submit, hasil 1 Des 07:10 UTC.
- best-game-01: R3 entry final; R4 sudah dibangun tapi submit tertahan
  kuota; entry tutup 19 Nov 01:00 WIB.
- gta6-01 R3: sudah submit, hasil 10 Des 15:00 UTC.
- gta6-twitch-ccu-forecast-01: entry tutup 19 Nov 08:00 WIB.
- news-image-20261118: bisa diperbaiki / submit ulang; batas entry
  20 Nov 07:00 WIB.
- bring-the-humans-02: entry sudah dibangun, submit tertahan karena
  GitHub belum tertaut ke akun swift-pika-45; batas 21 Nov 17:30 WIB.
- Total hadiah: best-game / threejs $1.000; ai-excited / markdown /
  gta6-twitch $250; news-image $250; gta6-01 $1.666;
  bring-the-humans-02 $1.000.

## LARANGAN

- JANGAN PERNAH membuat akun make.fun kedua — satu akun per orang,
  akun kedua berarti diskualifikasi semua entry.
- JANGAN submit entry apa pun, dari akun mana pun.
- JANGAN PERNAH mengeksploitasi grader / scorer / judge make.fun.
- JANGAN login ke mana pun (make.fun, GitHub, X, Telegram).
- JANGAN menyentuh dompet: tidak mint, tidak swap, tidak claim,
  tidak transfer, tidak approve.
- JANGAN menulis kunci / seed / private key / alamat payout di hasil.

## Deadline

Hasil pertama dalam 24 jam setelah membaca tugas ini. Setelah itu,
ulang pass ini tiap hari sampai koordinator menutup tugas.

## Format hasil (WAJIB — tulis di chat kamu sendiri, user yang
## meneruskan ke koordinator)

```
TUGAS 002 — HASIL
Kru: Muse-3
Tanggal: YYYY-MM-DD HH:MM WIB

A. KOMPETISI BARU (sejak 18 Nov 2026):
   - Slug: ...
     Total hadiah: ... | Tutup: ... | Syarat: ...
     Rekomendasi: IKUT / SKIP — alasan satu baris.
   (bila tidak ada yang baru, tulis: tidak ada kompetisi baru)

B. STATUS ENTRY KITA (akun swift-pika-45):
   - ai-excited-01 R4: rank .../... | status ... | hadiah di rank kita ...
   - best-game-01: rank .../... | status ... | hadiah di rank kita ...
   - gta6-01 R3: rank .../... | status ... | hadiah di rank kita ...
   - threejs-fps-02: rank .../... | status ... | hadiah di rank kita ...
   - gta6-twitch-ccu-forecast-01: rank .../... | status ... | hadiah ...
   - news-image-20261117: rank .../... | status ... | hadiah ...
   - news-image-20261118: rank .../... | status ... | hadiah ...
   - bring-the-humans-02: rank .../... | status ... | hadiah ...
   - Kuota submit: day cap ... | hard limit ...
   - Jarak ke tempat berbayar terdekat per entry (berapa rank lagi).

C. PELAJARAN DARI PERINGKAT ATAS (satu kompetisi, rank 1–3):
   1. ...
   2. ...
   3. ...

D. CATATAN:
   - Hal yang butuh tindak lanjut koordinator: ...
```

Aturan laporan (dari koordinator): tiap laporan bounty WAJIB (a) total
hadiah tiap kompetisi + tabel payout, (b) rank 1 sampai rank kita,
(c) hadiah di rank kita + jarak ke tempat berbayar terdekat.
