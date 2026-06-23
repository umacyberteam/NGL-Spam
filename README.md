# 🔥 NGL-SPAM

**Tools untuk mengirim spam pesan anonim ke NGL.link**  
*Hanya untuk edukasi dan pembelajaran. Dilarang digunakan untuk serangan atau merugikan orang lain.*

---

## 📌 Fitur

- ✅ Spam pesan anonim ke NGL
- ✅ Input username & pesan custom
- ✅ Atur jumlah spam & delay
- ✅ Auto retry jika gagal
- ✅ Tampilan terminal yang rapih
---

## 📦 Instalasi di Termux / Linux

Ikuti langkah-langkah di bawah ini untuk menginstall dan menjalankan tools:

```bash
# 1. Update & Upgrade Termux
pkg update && pkg upgrade -y

# 2. Install Python & Git
pkg install python git -y

# 3. Install modul requests (wajib!)
pip install requests

# 4. Clone repository ini
git clone https://github.com/umacyberteam/NGL-Spam.git

# 5. Masuk ke folder NGL-Spam
cd NGL-Spam

# 6. Jalankan tools
python nglmain.py
