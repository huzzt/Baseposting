# 🔵 Baseposting AI Agent

AI Agent bertema Biru & Putih — gratis untuk semua orang.

---

## 🚀 Cara Deploy ke Vercel

### Langkah 1 — Upload project
1. Buka [vercel.com](https://vercel.com) dan login / daftar gratis
2. Klik **"Add New Project"**
3. Pilih **"Upload"** (drag & drop folder ini)

### Langkah 2 — Set Environment Variable (API Key)
Di halaman deploy Vercel, sebelum klik Deploy:
1. Scroll ke bagian **"Environment Variables"**
2. Tambahkan:
   - **Name**: `ANTHROPIC_API_KEY`
   - **Value**: `sk-ant-xxxxxxx` ← masukkan API Key barumu
3. Klik **Add**

### Langkah 3 — Deploy!
Klik tombol **Deploy** — tunggu ~1 menit.

Vercel akan memberikan link publik seperti:
```
https://baseposting-agent.vercel.app
```

Share link itu ke siapa saja! 🎉

---

## 📁 Struktur File

```
baseposting-vercel/
├── vercel.json          ← konfigurasi Vercel
├── api/
│   └── chat.js          ← backend (API Key aman di sini)
├── public/
│   └── index.html       ← frontend agent
└── README.md
```

---

## 🔑 Keamanan

- API Key **tidak pernah** terekspos ke pengguna
- Semua request chat melewati backend `/api/chat`
- Aman digunakan publik

---

## ✅ Fitur

- 💬 Chat AI (powered by Claude Sonnet 4)
- 🎨 Generative Blue & White Art (6 style)
- 📱 Responsive — mobile & desktop
- 🆓 Gratis untuk semua pengguna
