📝 Ardnotes - Digital Garden
Selamat datang di Ardnotes, sebuah repositori catatan teknis dan jurnal pribadi yang dikelola oleh Alindra Setya Ardana. Website ini dibangun dengan fokus pada kecepatan, keamanan, dan otomasi penuh dari penulisan hingga publikasi.

🌐 Live Site: notes.alindra.my.id

🚀 Tech Stack & Automation
Sistem ini menggunakan arsitektur Modern Web Pipeline untuk memastikan proses writing-to-live berjalan tanpa hambatan [cite: 12-01-2026]:

- Content Source: Notion (Database-driven writing).
- Static Site Generator: Hugo with PaperMod Theme.
- Orchestrator: n8n (Automated Content Pipeline).
- Hosting & CI/CD: GitHub Pages & GitHub Actions.

🛠️ How It Works (The Pipeline)
Sistem ini dirancang untuk berjalan secara otomatis tanpa perlu menyentuh terminal Git setiap hari:
1. Writing: Catatan dibuat di Notion dengan status Ready.
2. Syncing (n8n): n8n melakukan polling (setiap jam 10 malam) atau dipicu secara manual via Webhook.
3. Formatting: n8n mengubah konten Notion menjadi file Markdown dengan Frontmatter Hugo secara otomatis.
4. Pushing: n8n melakukan git push ke repositori ini pada branch main.
5. Deploying: GitHub Actions mendeteksi perubahan dan langsung melakukan rebuild serta deploy ke GitHub Pages.

📂 Folder Structure
Plaintext

.
├── .github/workflows/      # Konfigurasi CI/CD (GitHub Actions)
├── content/posts/          # Tempat artikel Markdown hasil sinkronisasi n8n
├── themes/PaperMod/        # Submodule tema blog
├── hugo.yaml               # Konfigurasi utama website
└── README.md               # Dokumentasi ini


👨‍💻 Maintainer
Alindra Setya Ardana Presales Engineer & Solution Architect Enthusiast
