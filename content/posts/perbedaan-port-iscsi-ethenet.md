---
title: "Perbedaan Port iSCSI vs Ethernet di Server Storage"
date: 2026-04-16
categories: ["Insight & Journal"]
description: "Pahami perbedaan krusial port iSCSI dan Ethernet di server storage. iSCSI untuk block storage langsung, Ethernet untuk koneksi data via protokol."
keywords: ["port iSCSI","port Ethernet","server storage","block storage","perbedaan port server","koneksi storage","protokol jaringan storage","Alindra","Notes Alindra"]
tags: ["insight","analysis","tips","panduan"]
---

 Perbedaan port di server cukup krusial karena jika dilihat dari fisiknya sama, namun memiliki fungsi yang berbeda.

**Port iSCSI**
Merupakan port yang langsung menghubungkan dari Server Storage ke Server Virtualisasi/Server Lainnya dalam bentuk **Block**. Sederhananya, disini kita bisa anggap mirip fungsi kabel SATA yang langsung terhubung ke server (seperti menambah drive C/D langsung ke Server). Bedanya, disini storagenya berjalan sendiri menggunakan OS sendiri guna membantu mitigasi risiko apabila terjadi kendala pada server, data tetap berada di tempat yang aman dan berbeda.

Umumnya port iSCSI ini menggunakan **SFP+**, namun bisa juga menggunakan **RJ45 1G / RJ45 10G** ataupun **SFP**.

**Port Ethernet**
Merupakan port yang menghubungkan ke level data. Sederhananya, kita terkoneksi dari Server Storage menggunakan protokol **FTP/HTTPS/Protokol lainnya** dan **tidak langsung dimount ke drive** seperti iSCSI.

Port ini lebih umum dijumpai karena sebagian besar akan menggunakan ini kalau tidak terlibat dengan Storage Server. Port Ethernet variasinya lebih banyak: **RJ45, SFP, QSFP, dsb**.