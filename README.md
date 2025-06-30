# Crack-IG Script - Alat Otomatisasi dan Brute Force Akun Instagram

⚠️ **Peringatan:**  
Proyek ini dibuat hanya untuk keperluan edukasi dan penelitian keamanan etis (ethical hacking). Segala bentuk penyalahgunaan, termasuk mengakses akun orang lain tanpa izin, adalah tindakan ilegal dan bertentangan dengan kebijakan GitHub. Penulis tidak bertanggung jawab atas penyalahgunaan alat ini.

## 📌 Tentang

Crack-IG adalah script otomatisasi yang meniru perilaku aplikasi resmi Instagram untuk mengakses dan mengekstrak data menggunakan API dan GraphQL Instagram. Script ini mendukung login menggunakan **cookie** maupun **username dan password**.

Setelah berhasil login, script dapat melakukan scraping data publik seperti:

- Daftar pengikut (followers)
- Komentar pada postingan
- Daftar penyuka (likers)

## 🔐 Fitur Utama

### ✅ Metode Login
- Login dengan cookie
- Login menggunakan username dan password

### 🔍 Scraping Data
- Mengambil data followers, following, komentar, dan likers melalui API GraphQL Instagram

### 💥 Mesin Brute-force
- Melakukan brute-force akun Instagram secara massal dengan teknik multithreading
- Mendukung penggunaan daftar password kustom dan target username
- Hasil login dikategorikan:
  - ✅ Berhasil
  - 🔐 Meminta 2FA
  - ⚠️ Checkpoint (verifikasi tambahan)

### 🛡️ Teknik Menghindari Deteksi
- Memalsukan User-Agent secara acak agar menyerupai aplikasi resmi Instagram
- Menggunakan header khusus yang menyerupai aplikasi mobile
- Mendukung rotasi proxy (HTTP/SOCKS)
- Menyarankan pengguna mengaktifkan mode pesawat jika IP diblokir sementara

### 📦 Tindakan Setelah Akun Berhasil Diretas
- Mengubah email dan nomor HP akun target
- Mengaktifkan Two-Factor Authentication (2FA)
- Menyimpan detail akun hasil login (opsional)

## ⚙️ Persyaratan
- Python 3.7 ke atas
- Library Python standar: `requests`, `threading`, `json`, `random`, dll
- (Opsional) Daftar proxy untuk meningkatkan anonimitas

## ⚠️ Catatan Hukum
Script ini hanya boleh digunakan untuk:
- Penetration testing terhadap akun milik sendiri
- Edukasi seputar keamanan siber dan ethical hacking
- Riset tentang cara kerja sistem autentikasi

**Dilarang keras** menggunakan alat ini untuk mengakses akun orang lain tanpa izin.


