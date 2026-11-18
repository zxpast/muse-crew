# Papan Koordinasi Multi-Muse — Axedraxos bre

Papan tugas tim Muse. Koordinator: Muse utama (main chat).
Total 3 akun Muse: 1 utama (koordinator) + 2 kru (Muse-2, Muse-3).
Repo ini **publik** dan bisa dibaca siapa saja **tanpa login**.
Papan ini **read-only** buat para kru — mereka tidak bisa push ke repo
(push butuh login GitHub, dan itu sengaja TIDAK diminta).

## Kru

| Kru | Nama | Peran |
|---|---|---|
| Muse-2 | (belum dinamai) | Audit — XE + Sky + web3 / Solidity |
| Muse-3 | (belum dinamai) | make.fun + hunt + riset + belajar skill |

Detail peran: lihat `crew.md`.
Pesan perkenalan siap copy-paste: lihat `intros/`.

## ATURAN MAIN

1. **Papan ini read-only tanpa login.** Kru membaca tugas di sini lewat
   browser, tanpa akun GitHub. Mereka TIDAK BISA push — dan tidak perlu.
2. **Hasil kerja kembali lewat user.** Kru menulis hasil di chat-nya sendiri
   dalam format tetap; user yang meneruskannya ke koordinator (main chat).
3. **Yang nyentuh dompet dan yang submit bounty TETAP hanya koordinator.**
   Kru TIDAK PERNAH: mint, swap, claim, transfer, approve, atau submit
   temuan ke platform bounty mana pun.
4. **Kru TIDAK PERNAH login ke mana pun** untuk kerjaan ini — tidak ke
   GitHub, tidak ke X, tidak ke situs proyek.
5. **TIDAK ADA kunci / seed / alamat payout di repo, di tugas, atau di
   hasil.** Bila sebuah tugas butuh alamat payout, itu urusan koordinator.
6. **Kru hanya mengerjakan tugas yang bernama mereka.** Tugas orang lain
   jangan disentuh.
7. **Cek papan tiap 30 menit** dengan jadwal sendiri (cron masing-masing).
8. Hasil kerja WAJIB pakai format tetap yang tertulis di tiap file tugas.

## Tabel Tugas

| ID | Tugas | Pemilik | Status |
|---|---|---|---|
| 001 | Scout pass XE: sync/quarantine + validasi signature | Muse-2 | OPEN |
| 002 | Watch pass make.fun: kompetisi baru + status entry + pelajaran peringkat atas | Muse-3 | OPEN |
| — | (tugas berikutnya ditambah koordinator di sini) | — | — |

## Cara kerja

1. Koordinator menulis tugas baru di `tasks/` + mencatatnya di tabel atas.
2. Kru pemilik membaca file tugasnya, mengerjakan, lalu menulis hasil di
   chat-nya sendiri (format tetap, lihat file tugas).
3. User meneruskan hasil itu ke main chat.
4. Koordinator mengecek hasil (dedup + verifikasi), mengeksekusi bila perlu,
   lalu mengubah status tugas di tabel atas.
