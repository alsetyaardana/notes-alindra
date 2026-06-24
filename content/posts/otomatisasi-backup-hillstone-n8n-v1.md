---
title: "Otomatisasi Backup Konfigurasi Firewall Hillstone Menggunakan n8n"
date: 2026-06-25T00:00:00+07:00
draft: false
categories: ["Network Security"]
tags: ["hillstone, n8n, automation, firewall, backup"]
slug: "otomatisasi-backup-hillstone-n8n-v1"
---

Menjaga ketersediaan *backup* konfigurasi *firewall* adalah hal yang sangat krusial. Alih-alih melakukan *backup* manual setiap akhir pekan, kita bisa memanfaatkan **n8n** untuk menarik konfigurasi dari perangkat Hillstone secara otomatis dan terstruktur.

![otomatisasi-backup-hillstone-n8n-v1-1.png](https://notes.alindra.my.id/images/posts/otomatisasi-backup-hillstone-n8n-v1-1.png)

Pada *workflow* di atas, n8n akan mengirimkan *request* API ke Hillstone NGFW setiap jam 12 malam. Sistem kemudian mengunduh file *running-config* dan menyimpannya langsung ke repositori cadangan.

### Mengapa Pendekatan Ini Efektif?
1. **Visual & Fleksibel:** Sangat mudah melacak *node* mana yang gagal saat *hit* API.
2. **Notifikasi Real-time:** Bisa langsung disambungkan dengan *bot* Telegram (seperti AI-LIN) untuk memberikan laporan sukses atau gagal.

![otomatisasi-backup-hillstone-n8n-v1-2.png](https://notes.alindra.my.id/images/posts/otomatisasi-backup-hillstone-n8n-v1-2.png)

Praktik terbaiknya: pastikan *API Key* disimpan sebagai kredensial aman di dalam *Vault* n8n, bukan di-*hardcode* secara mentah di dalam *node* HTTP Request demi keamanan jaringan.