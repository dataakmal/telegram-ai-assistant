# Telegram AI Assistant (No-Code)

Panduan membangun **AI Assistant berbasis Telegram** menggunakan pendekatan no-code dengan mengintegrasikan Telegram Bot, Google Gemini AI, dan n8n sebagai automation engine.

## 📌 Overview

Project ini mendokumentasikan alur pembuatan AI Assistant yang mampu menerima pesan dari pengguna Telegram, memproses pertanyaan menggunakan AI, dan mengirimkan balasan secara otomatis melalui workflow n8n.

### Tech Stack

- **Telegram Bot** — antarmuka komunikasi dengan pengguna.
- **Google AI Studio (Gemini)** — model AI untuk memproses dan menghasilkan jawaban.
- **n8n** — platform otomatisasi untuk menghubungkan Telegram dan AI.

## 🔄 Workflow Architecture

Alur kerja sistem:

1. **Incoming Message:** pengguna mengirim pesan ke Telegram Bot.
2. **Telegram Trigger:** n8n menerima pesan yang masuk.
3. **AI Processing:** pesan diteruskan ke model Gemini untuk diproses berdasarkan system instruction.
4. **Send Response:** hasil keluaran AI dikirim kembali ke pengguna melalui Telegram.
5. **Workflow Activation:** workflow diaktifkan agar bot dapat merespons pesan secara otomatis.

## 📚 Documentation

Repository ini berisi dokumentasi berikut:

| File | Deskripsi |
|---|---|
| `Panduan Alur Pembuatan Telegram AI Assistant (No-Code).pdf` | Panduan teknis langkah demi langkah untuk membuat bot, mengatur Gemini, membangun workflow n8n, dan mengaktifkan bot. |
| `Sesi 3 - Workshop AI Assistant (Materi).pdf` | Materi workshop mengenai konsep AI automation, setup Telegram Bot, integrasi Gemini, workflow automation, testing, dan troubleshooting. |

## 🚀 Prerequisites

Sebelum memulai, siapkan:

- Akun Telegram.
- Telegram Bot API Token dari [@BotFather](https://t.me/BotFather).
- Akun Google AI Studio untuk memperoleh Gemini API Key.
- Akun atau instance n8n.

## 🛠️ Getting Started

1. Baca dokumen panduan teknis untuk memahami proses setup dari awal.
2. Buat Telegram Bot melalui BotFather dan simpan token dengan aman.
3. Siapkan Gemini API Key melalui Google AI Studio.
4. Buat workflow di n8n menggunakan Telegram Trigger, node AI, dan Telegram Send Message.
5. Uji alur komunikasi antara Telegram, Gemini, dan n8n.
6. Aktifkan workflow setelah pengujian berhasil.

## 🔐 Security

- Jangan mengunggah Telegram Bot API Token atau Gemini API Key ke repository.
- Simpan credentials melalui mekanisme credential management n8n.
- Jangan membagikan token, API key, atau informasi sensitif lainnya secara publik.

## 👨‍💻 Author

**Akmal Fauzan**

Project ini dibuat sebagai dokumentasi pembelajaran dan implementasi AI automation menggunakan pendekatan no-code.
