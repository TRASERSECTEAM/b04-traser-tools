<h1 align="center">
  ⚡ META-OSINT B04 v4 ⚡
</h1>

<p align="center">
  <b>Advanced Reconnaissance CLI Tool</b><br>
  <i>Tools investigasi digital dengan tampilan dan performa profesional.</i>
</p>

<p align="center">
  <img src="https://files.catbox.moe/benwpf.png" width="140" alt="TraserSec Logo">
</p>

---

## 🧠 FITUR UNGGULAN

- ✅ Tampilan hacker-style terminal
- ✅ Efek loading real-time
- ✅ doxing profesional (masukkan nomor target)
- ✅ Informasi publikasi IP korban secara otomatis
- ✅ Redirect ke website setelah proses selesai
- ✅ Dirancang full otomatis untuk Termux

---

## 🌐 WEBSITE RESMI

> 🔗 https://trasersecteam.my.id

---

## 🛠️ CARA INSTALLASI

Jalankan langsung di Termux:

```bash
pkg install git -y
git clone https://github.com/TRASERSECTEAM/b04-traser-tools.git
cd b04-traser-tools
pkg update -y
pkg upgrade -y
pkg install -y nodejs termux-api
termux-setup-storage
npm init -y >/dev/null 2>&1
npm install axios chalk form-data
node B04.js
