# Coombo Cheker 

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Python](https://img.shields.io/badge/python-3.x-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS%20%7C%20Termux-lightgrey)
![Stars](https://img.shields.io/github/stars/LikeEx01/ComboChecker?style=social)
![Issues](https://img.shields.io/github/issues/LikeEx01/ComboChecker)
![Last Update](https://img.shields.io/github/last-commit/LikeEx01/ComboChecker)

---

![Preview](https://e.top4top.io/p_3480rzkn83.jpg)

---

## Deskripsi
**Combo Checker WHM / cPanel / Webmail** adalah alat Python multithread untuk memeriksa kombinasi login `url|user|pass` ke berbagai panel hosting seperti:
- WHM
- cPanel
- Webmail

Tool ini secara otomatis mendeteksi port umum dan path login yang digunakan panel hosting seperti `/cpanel`, `/whm`, `/webmail` serta port `2082`, `2083`, `2086`, `2087`, `2095`, dan `2096`.

---

## Fitur Utama
- 🔎 Auto Detect Panel dari Port dan Path
- 🚀 Multithread untuk kecepatan maksimum
- ✅ Menyimpan hasil login sukses ke file
- 🔐 Deteksi 2FA (Two Factor Authentication)
- ❌ Tidak menampilkan error terminal

---

## Output

| File                 | Fungsi                                          |
|----------------------|--------------------------------------------------|
| `SucescPanel.txt`    | Login sukses ke cPanel                           |
| `SucesWhm.txt`       | Login sukses ke WHM                              |
| `SucesWebmail.txt`   | Login sukses ke Webmail                          |
| `WhmA2F.txt`         | Login memerlukan autentikasi dua langkah (2FA)   |
| `AllSuccess.txt`     | Gabungan semua login sukses                      |
| `Unknown.txt`        | Login sukses ke panel tak teridentifikasi        |

---

## Instalasi

### 📱 Termux (Android)
```bash
pkg update -y
pkg upgrade -y
pkg install python git -y
pip install requests urllib3 colorama
git clone https://github.com/LikeEx01/CoomboCheker.git
cd ComboChecker
python ComboChecker.py
```

---

### 🐧 Linux (Debian / Ubuntu)
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install git python3 python3-pip -y
pip3 install requests urllib3 colorama
git clone https://github.com/LikeEx01/CoomboCheker.git
cd ComboChecker
python3 ComboChecker.py
```

---

### 💻 Windows (CMD / PowerShell)
1. Download & install Python dari https://www.python.org
2. Buka **CMD** atau **PowerShell**, lalu jalankan:
```bash
pip install requests urllib3 colorama
git clone https://github.com/LikeEx01/CoomboCheker.git
cd ComboChecker
python ComboChecker.py
```

---

## Penggunaan

1. Siapkan file combo dengan format:
```
https://example.com:2083|admin|admin123
https://example.com/webmail|user|pass123
https://example.com/whm|root|toor
```

2. Jalankan script:
```bash
python ComboChecker.py
```

3. Masukkan nama file dan jumlah thread saat diminta:
```
ENTER YOUR LIST: combo.txt
ENTER YOUR THREAD: 10
```

---

## Contoh Output Terminal

```bash
[GOOD] https://example.com:2083
[A2F]  https://secure.domain.com
[BAD]  https://unknown.com
```

---

## Lisensi
Proyek ini menggunakan [MIT License](https://opensource.org/licenses/MIT)

---

## Penafian
> ⚠️ **PERINGATAN:** Tool ini hanya untuk tujuan edukasi dan pengujian sistem yang Anda miliki atau memiliki izin. Penggunaan tanpa izin dapat melanggar hukum. Penulis tidak bertanggung jawab atas penyalahgunaan.

---

## Kontak

- GitHub: [LikeEx01](https://github.com/LikeEx01)
- Telegram: [LikeEx01](https://t.me/usernamee13371)

---

## 🔔 Bergabung di Saluran WhatsApp

Untuk update, pengumuman, dan informasi lainnya, silakan bergabung di saluran WhatsApp resmi kami:

👉 [𝐍𝐨𝐜𝐭𝐮𝐫𝐧𝐚𝐥𝐁𝐲𝐭𝐞𝐬](https://whatsapp.com/channel/0029VaudLHc7YSd9S9c9800c)

---
