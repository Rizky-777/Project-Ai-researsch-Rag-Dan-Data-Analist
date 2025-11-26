# N8N-Project-AI

## Apa itu n8n?

**n8n** (dibaca: "n-eight-n") adalah platform otomatisasi workflow yang bersifat **open-source** dan dapat di-host sendiri (self-hosted). n8n memungkinkan Anda untuk menghubungkan berbagai aplikasi dan layanan menjadi workflow otomatis tanpa perlu menulis banyak kode.

## Fitur Utama

- 🔗 **200+ Integrasi** - Terhubung dengan berbagai layanan seperti Google Sheets, Slack, GitHub, database, dan lainnya
- 🎨 **Visual Workflow Builder** - Buat workflow dengan drag-and-drop yang mudah digunakan
- 🔧 **Kode Kustom** - Dukungan JavaScript dan Python untuk logika kompleks
- 🔔 **Webhook Support** - Trigger workflow secara otomatis dari event eksternal
- ⏰ **Scheduling** - Jalankan workflow secara terjadwal (cron jobs)
- 🏠 **Self-Hosted** - Data Anda tetap berada di server Anda sendiri
- 🤖 **AI Integration** - Integrasi dengan OpenAI, LangChain, dan model AI lainnya

## Kegunaan

n8n dapat digunakan untuk berbagai keperluan otomatisasi, seperti:

1. **Automasi Tugas Repetitif** - Mengurangi pekerjaan manual yang berulang
2. **Integrasi Antar Aplikasi** - Menghubungkan berbagai aplikasi yang tidak memiliki integrasi native
3. **ETL (Extract, Transform, Load)** - Memproses dan memindahkan data antar sistem
4. **Notifikasi & Alerting** - Mengirim notifikasi otomatis berdasarkan kondisi tertentu
5. **Pemrosesan Data dengan AI** - Mengintegrasikan kemampuan AI ke dalam workflow

## Tentang Proyek Ini

Proyek **N8N-Project-AI** ini merupakan implementasi workflow n8n yang fokus pada integrasi dengan teknologi AI (Artificial Intelligence). Proyek ini dapat mencakup:

- Workflow untuk pemrosesan data dengan AI
- Integrasi dengan Large Language Models (LLM) seperti OpenAI GPT
- Automasi tugas berbasis machine learning
- Chatbot dan asisten virtual

## Cara Memulai

### Prasyarat
- Docker (direkomendasikan)
- Node.js v18.17.0 atau lebih tinggi (untuk instalasi npm) - cek [dokumentasi resmi](https://docs.n8n.io/hosting/installation/npm/) untuk versi terbaru

### Instalasi dengan Docker

```bash
docker run -it --rm \
  --name n8n \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  n8nio/n8n
```

### Instalasi dengan npm

```bash
npm install n8n -g
n8n start
```

Setelah instalasi, buka browser dan akses `http://localhost:5678`

## Dokumentasi

- [Dokumentasi Resmi n8n](https://docs.n8n.io/)
- [n8n Community Forum](https://community.n8n.io/)
- [GitHub n8n](https://github.com/n8n-io/n8n)

## Lisensi

n8n menggunakan [Sustainable Use License](https://github.com/n8n-io/n8n/blob/main/LICENSE.md)
