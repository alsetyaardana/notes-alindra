---
title: "Metode Penulisan Buku Memanfaatkan Claude Cowork"
date: 2026-07-22T00:00:00+07:00
draft: false
categories: []
tags: ["Claude Cowork", "menulis buku", "AI writing", "Onno Purbo", "docx automation", "editorial review AI"]
slug: "metode-penulisan-buku-claude-cowork"
---
Waktu mutusin nulis buku "Bukan Cuma Berani, Tapi Siap", saya nggak mulai dari ngetik bab 1. Saya mulai dari nyusun aturan main dulu, di file namanya CLAUDE.md, dan itu yang paling nentuin hasil akhirnya rasanya kayak saya beneran nulis, bukan kayak baca output AI.

Ini rangkuman metodenya, buat kamu yang mau nyoba nulis buku sendiri pakai Claude Cowork.

1. Bikin aturan main dulu, baru minta ditulisin

Sebelum minta Claude nulis satu kalimat pun, saya taruh semua batasan di satu file: siapa penulisnya, argumen inti yang harus konsisten dari bab 1 sampai akhir, gaya bahasa yang saya mau, dan larangan keras (nggak boleh generalisasi berlebihan, nggak boleh ada statistik yang sumbernya nggak jelas, nggak boleh kedengeran kayak chatbot).

Tanpa ini, hasilnya bakal generic. AI defaultnya nulis rapi tapi hambar. File aturan ini yang bikin outputnya kedengeran kayak saya, bukan kayak jawaban asisten.

2. Data pendukung dipisah, biar nggak ada yang dikarang

Saya bikin file terpisah isinya cuma data dan statistik yang udah saya validasi sendiri (linknya, tahunnya, konteksnya). Aturannya simpel: Claude cuma boleh pakai data dari file itu. Kalau butuh data baru, harus cari dulu dan saya konfirmasi, bukan langsung ditulis seolah pasti benar.

Ini yang paling nyelametin dari salah satu risiko terbesar nulis buku pakai AI: halusinasi kutipan atau statistik yang kedengeran meyakinkan tapi sebenernya nggak ada sumbernya.

3. Satu bab per sesi, bukan sekaligus satu buku

Saya nggak pernah minta "tulisin buku saya dari awal sampai akhir." Tiap sesi, saya minta satu bab, kasih outline-nya, dan kalau Claude butuh detail pengalaman pribadi yang belum ada di draft, dia nanya dulu ke saya. Nggak boleh ngarang pengalaman yang nggak pernah saya certain.

Prosesnya jadi lebih kayak diskusi bolak-balik daripada generate sekali jadi. Beberapa bab bahkan direvisi ulang setelah saya baca dan bilang "ini bukan gitu kejadiannya", terus diperbaiki sesuai fakta yang bener.

4. Unsur pelengkap yang sering kelewat

Buku bukan cuma bab isi. Ada pengantar, executive summary, glossary, lampiran, dan daftar referensi yang gampang kelewat kalau fokusnya cuma ngejar bab selesai. Saya susun bagian-bagian ini belakangan, setelah semua bab kelar, dan Claude bantu susun glossary dari istilah yang beneran muncul di naskah (bukan istilah yang dipaksain biar kelihatan lengkap).

5. Minta dikritik, bukan cuma minta ditulisin

Bagian yang paling kepake: setelah draf selesai, saya minta Claude jadi editor kritis, bukan cuma asisten yang manut. Saya kasih daftar kritik yang saya sendiri ragu (misalnya "apa dua pilar buku ini kelihatan terlalu menyederhanakan komunikasi?"), dan minta dievaluasi independen, bukan langsung disetujui.

Hasilnya kelihatan mana kritik yang valid, mana yang kebanyakan, dan masalah lain yang belum saya sadar sendiri (contohnya: ada istilah di glossary yang ternyata nggak pernah dibahas di badan naskah, atau klaim yang kedengeran terlalu absolut dibanding bab lain yang sebenernya udah punya jawabannya).

6. Produksi akhir: bukan cuma nulis, tapi juga nge-format

Setelah naskah fix, saya generate langsung ke format docx yang siap dicek menyeluruh: cover custom, ilustrasi tiap bab yang relevan, daftar isi otomatis dengan nomor halaman yang bener, tabel glossary, sampai footer konsisten di tiap halaman. Semua dari script, bukan ditata manual satu-satu, biar kalau ada revisi kecil (typo, kalimat kepotong antarhalaman, footer yang salah tempat di cover), bisa di-generate ulang dari awal tanpa harus rapiin ulang dari nol.

Kenapa metode ini penting

AI bisa bantu nulis cepat, tapi kecepatan tanpa pagar itu berbahaya buat buku nonfiksi, apalagi yang isinya klaim, data, dan pengalaman pribadi. Menulis Cepat Buku dibantu Prompt karya Onno W. Purbo jadi salah satu rujukan metodologi saya di sini, terutama soal proses per-bab dan unsur pelengkap, walaupun saya sederhanakan lewat CLAUDE.md dan pola kerja Cowork yang lebih cocok sama alur kerja saya.

Intinya: AI itu akselerator proses, bukan pengganti tanggung jawab penulis atas apa yang ditulis. Buku ini tetap 100% pengalaman dan suara saya sendiri, cuma prosesnya jadi jauh lebih cepat dan lebih rapi buat dicek ulang.