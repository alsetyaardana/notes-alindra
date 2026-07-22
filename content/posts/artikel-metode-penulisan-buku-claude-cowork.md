---
title: "Metode Penulisan Buku Memanfaatkan Claude Cowork"
date: 2026-07-23
categories: ["Insight & Journal"]
description: "Metode menulis buku nonfiksi pakai Claude Cowork - dari aturan main lewat CLAUDE.md, data pendukung tervalidasi, sampai produksi docx otomatis. Ditulis Alindra berdasarkan pengalaman langsung."
keywords: ["menulis buku dengan AI", "claude cowork", "metode penulisan buku", "onno purbo", "ai writing workflow", "alindra", "notes alindra"]
tags: ["ai", "menulis", "claude cowork", "produktivitas", "teknologi"]
---
# Metode Penulisan Buku Memanfaatkan Claude Cowork
*Catatan proses oleh Alindra Setya Ardana tentang metode yang dipakai untuk menulis buku "Bukan Cuma Berani, Tapi Siap" menggunakan Claude Cowork.*

Waktu mutusin nulis buku ini, saya nggak mulai dari ngetik bab 1. Saya mulai dari nyusun aturan main dulu, di file namanya CLAUDE.md, dan itu yang paling nentuin hasil akhirnya rasanya kayak saya beneran nulis, bukan kayak baca output AI.

## 1. Bikin Aturan Main Dulu, Baru Minta Ditulisin

Sebelum minta Claude nulis satu kalimat pun, saya taruh semua batasan di satu file: siapa penulisnya, argumen inti yang harus konsisten dari bab 1 sampai akhir, gaya bahasa yang saya mau, dan larangan keras.

### Isi Aturan Utama:
- **Argumen inti**: harus konsisten di semua bab, nggak boleh digeser tengah jalan
- **Gaya bahasa**: campuran Indonesia-Inggris santai, storytelling personal, bukan gaya buku teori
- **Larangan keras**: nggak boleh generalisasi berlebihan, nggak boleh ada statistik tanpa sumber jelas, nggak boleh kedengeran kayak chatbot

Tanpa ini, hasilnya bakal generic. AI defaultnya nulis rapi tapi hambar. File aturan ini yang bikin outputnya kedengeran kayak saya, bukan kayak jawaban asisten.

## 2. Data Pendukung Dipisah, Biar Nggak Ada yang Dikarang

Saya bikin file terpisah isinya cuma data dan statistik yang udah saya validasi sendiri (linknya, tahunnya, konteksnya).

### Aturannya:
- Claude cuma boleh pakai data dari file itu, bukan dari ingatan bebasnya sendiri
- Kalau butuh data baru, harus cari dulu dan saya konfirmasi
- Kalau belum ada sumbernya, ditandai sebagai belum terverifikasi, bukan ditulis seolah pasti benar

Ini yang paling nyelametin dari salah satu risiko terbesar nulis buku pakai AI: halusinasi kutipan atau statistik yang kedengeran meyakinkan tapi sebenernya nggak ada sumbernya.

## 3. Satu Bab per Sesi, Bukan Sekaligus Satu Buku

Saya nggak pernah minta "tulisin buku saya dari awal sampai akhir." Tiap sesi, saya minta satu bab, kasih outline-nya, dan kalau Claude butuh detail pengalaman pribadi yang belum ada di draf, dia nanya dulu ke saya. Nggak boleh ngarang pengalaman yang nggak pernah saya ceritain.

Prosesnya jadi lebih kayak diskusi bolak-balik daripada generate sekali jadi. Beberapa bab bahkan direvisi ulang setelah saya baca dan bilang "ini bukan gitu kejadiannya," terus diperbaiki sesuai fakta yang bener.

## 4. Unsur Pelengkap yang Sering Kelewat

Buku bukan cuma bab isi. Ada bagian-bagian yang gampang kelewat kalau fokusnya cuma ngejar bab selesai:

- **Pengantar** dan **Executive Summary**: kenapa buku ini ditulis, buat siapa
- **Glossary**: istilah yang beneran muncul di naskah, bukan yang dipaksain biar kelihatan lengkap
- **Lampiran**: checklist praktis yang bisa langsung dipakai pembaca
- **Daftar Referensi**: sumber yang dipakai, nomornya dilacak balik ke kutipan di badan bab

Saya susun bagian-bagian ini belakangan, setelah semua bab kelar.

## 5. Minta Dikritik, Bukan Cuma Minta Ditulisin

Bagian yang paling kepake: setelah draf selesai, saya minta Claude jadi editor kritis, bukan cuma asisten yang manut. Saya kasih daftar kritik yang saya sendiri ragu, dan minta dievaluasi independen, bukan langsung disetujui.

### Contoh yang Ketahuan Lewat Proses Ini:
- Ada istilah di glossary yang ternyata nggak pernah dibahas di badan naskah
- Ada klaim yang kedengeran terlalu absolut dibanding bab lain yang sebenernya udah punya jawabannya
- Ada anekdot personal yang secara etika perlu dikasih catatan tambahan, bukan dihapus atau dibiarkan tanpa konteks

## 6. Produksi Akhir: Bukan Cuma Nulis, Tapi Juga Nge-Format

Setelah naskah fix, saya generate langsung ke format docx yang siap dicek menyeluruh: cover custom, ilustrasi tiap bab yang relevan, daftar isi otomatis dengan nomor halaman yang bener, tabel glossary, sampai footer konsisten di tiap halaman.

Semua dari script, bukan ditata manual satu-satu, biar kalau ada revisi kecil (typo, kalimat kepotong antarhalaman, footer yang salah tempat di cover), bisa di-generate ulang dari awal tanpa harus rapiin ulang dari nol.

Core Logic:
AI itu akselerator proses, bukan pengganti tanggung jawab penulis atas apa yang ditulis. Rujukan metodologi utama di proses ini adalah *Menulis Cepat Buku dibantu Prompt* karya Onno W. Purbo, terutama soal proses per-bab dan unsur pelengkap, yang saya sederhanakan lewat CLAUDE.md dan pola kerja Cowork biar cocok sama alur kerja saya sendiri. Buku ini tetap 100% pengalaman dan suara saya sendiri, cuma prosesnya jadi jauh lebih cepat dan lebih rapi buat dicek ulang.
