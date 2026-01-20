# 🔐 VaultCLI — Secure Password Manager (CLI)

<img width="948" height="349" alt="Screenshot (1088)" src="https://github.com/user-attachments/assets/94228404-8c2b-402b-b947-d088c68d0931" />


VaultCLI adalah **aplikasi password manager berbasis Command Line Interface (CLI)** yang aman dan ringan, dibangun menggunakan **Python** dengan fokus pada **keamanan, enkripsi, dan usability**.  
---

## ✨ Fitur Utama

- 🔒 **Strong Encryption**
  - Enkripsi menggunakan **Fernet (AES-128)**
  - Key derivation dengan **PBKDF2-HMAC-SHA256**
  - 100.000 iterasi + salt unik per vault

- 🧠 **Password Strength Analyzer**
  - Analisis panjang, kompleksitas, dan pola umum
  - Skor dan feedback visual (WEAK / MODERATE / STRONG)

- 🔑 **Password Generator**
  - Generate password acak & kuat
  - Kombinasi huruf besar, kecil, angka, dan simbol

- 📋 **Auto-fill (Clipboard)**
  - Copy username / password ke clipboard secara aman
  - Menghindari penampilan plaintext yang tidak perlu

- 💾 **Encrypted Local Storage**
  - SQLite database
  - Data sensitif disimpan dalam bentuk terenkripsi

- 🖥️ **User-Friendly CLI**
  - Menu interaktif
  - Alur penggunaan jelas & feedback visual

---

## 🛠️ Tech Stack

| Komponen | Teknologi |
|--------|----------|
| Language | Python 3 |
| Cryptography | cryptography (Fernet, PBKDF2) |
| Database | SQLite |
| Clipboard | pyperclip |
| OS Support | Linux, macOS, Windows |

---

## 📦 Dependencies

```bash
pip install cryptography pyperclip
