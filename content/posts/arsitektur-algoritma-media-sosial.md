---
title: "Arsitektur Algoritma Media Sosial - Cara Kerja Ranking Feed"
date: 2026-01-22
categories: ["Insight & Journal"]
description: "Panduan lengkap arsitektur algoritma media sosial modern - dari candidate generation hingga feedback loop. Pelajari cara kerja ranking feed oleh Alindra."
keywords: ["algoritma media sosial", "cara kerja algoritma", "ranking social media", "candidate generation", "machine learning", "alindra", "notes alindra"]
tags: ["algoritma", "media sosial", "machine learning", "teknologi", "ranking"]
---

# Arsitektur Algoritma Media Sosial

*Catatan teknis oleh Alindra Setya Ardana tentang bagaimana algoritma media sosial modern bekerja dalam mengatur feed pengguna.*

## 1. Candidate Generation (Penyaringan Awal)

Tahap seleksi dari jutaan konten menjadi ~1.500 kandidat relevan.

### In-Network vs Out-of-Network:
- **In-Network**: Konten dari akun yang Anda ikuti (prioritas kedekatan)
- **Out-of-Network**: Konten luar berdasarkan:
  - Social Graph: Interaksi orang-orang di lingkaran Anda
  - Embedding Spaces: Kesamaan minat/topik (misal: komunitas IT)

## 2. Scoring / Ranking (Pemberian Skor)

Prediksi probabilitas interaksi menggunakan Machine Learning.

### Jenis Sinyal:
- **High-Value Signals**: Share, Save, & Detailed Reply
- **Low-Value Signals**: Like (bobotnya kini lebih rendah dibandingkan Share)
- **Prediction**: Model menghitung skor berdasarkan kemungkinan Anda akan menghabiskan waktu pada konten tersebut

## 3. Re-ranking & Filtering (Penyaringan Akhir)

Pembersihan daftar sebelum ditampilkan di layar.

### Filter yang Diterapkan:
- **Diversity**: Memastikan konten dari penulis yang sama tidak muncul berturut-turut
- **Integrity**: Filter otomatis terhadap spam, konten sensitif, atau informasi palsu
- **Fatigue Filter**: Menghapus konten yang sudah pernah Anda lihat agar feed tetap segar

## 4. Feedback Loop (Sinyal Perilaku)

Sistem pembelajaran terus-menerus berdasarkan respon real-time.

### Metrik Utama:
- **Dwell Time**: Durasi perhatian (berapa detik Anda berhenti men-scroll)
- **Negative Signals**: Mute, Not Interested, atau Fast Scrolling (melewati konten dengan cepat)

Core Logic:
Algoritma modern telah bergeser dari "Clicks" menuju "Attention". Fokus utama sistem adalah mempertahankan pengguna di dalam aplikasi selama mungkin melalui analisis Dwell Time dan Shareability.
