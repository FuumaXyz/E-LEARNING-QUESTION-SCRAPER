# E-LEARNING QUESTION SCRAPER 🚀

Skrip CLI PHP untuk men-scrape attempt quiz Moodle, mengekstrak soal/jawaban, men-download gambar, membuat gallery & laporan, dan (opsional) mengirim soal ke layanan generative API.

Repository: https://github.com/FuumaXyz/E-LEARNING-QUESTION-SCRAPER.git

✨ Fitur Utama

🔐 Autentikasi & Keamanan
- Login otomatis dengan validasi username
- Whitelist system untuk kontrol akses
- Session management dengan cookie handling
- Auto-deteksi user dari dashboard

📄 Ekstraksi Soal Lengkap
- ✅ Semua tipe soal: Pilihan ganda, benar/salah, matching, dropdown, esai
- ✅ Parsing HTML cerdas: Deteksi otomatis struktur pertanyaan
- ✅ Multi-halaman: Support soal dengan banyak halaman
- ✅ Metadata lengkap: Status, nilai, dan informasi tambahan

🖼️ Manajemen Media
- 📸 Download gambar otomatis dari soal
- 🗂️ Organisasi folder berdasarkan pertanyaan
- 🔍 Image mapping untuk referensi yang akurat
- 📦 Koleksi terpusat dengan gallery HTML

🤖 Integrasi AI (Gemini)
- 🔗 API Integration untuk analisis jawaban
- 📊 Multi-part processing untuk soal besar
- 🖼️ Image analysis dengan pengiriman gambar
- 📝 Format jawaban terstruktur

📁 Export & Output
- TXT: Ringkasan lengkap semua soal
- JSON: Data terstruktur untuk processing lanjut
- HTML: Gallery gambar dan preview
- ZIP: Arsip semua gambar
- Reports: Statistik dan laporan detail

---

🧰 Persyaratan singkat
- PHP CLI (disarankan PHP 8+)  
- Ekstensi cURL aktif  
- (Opsional) Ekstensi Zip untuk buat ZIP  
- Akses terminal/console

---

⚡ Quick start (3 langkah)
1. Clone repo:
```bash
pkg update -y && pkg upgrade -y
pkg install git -y
pkg install php -y
git clone https://github.com/FuumaXyz/E-LEARNING-QUESTION-SCRAPER.git
cd E-LEARNING-QUESTION-SCRAPER
php elearning.php
```

2. Siapkan credential lokal:
- Simpan cookie sesi Moodle ke file bernama `Cookie`  
- Simpan User-Agent string ke file `user-agent`  
- (Opsional) Simpan API key Generative API ke `DATABASE_api.txt` (jangan commit)

Ikuti menu interaktif → masukkan attempt ID, cmid, pilih opsi ekstraksi/download gambar/dll.

---

📄 LISENSI
Hak Cipta © 2025 Fuuma

Tools ini dirilis hanya untuk tujuan edukasi. Pengguna bertanggung jawab penuh atas segala penggunaan.

✅ DIPERBOLEHKAN:
- Edukasi dan pembelajaran
- Penelitian akademik yang sah
- Pengembangan keterampilan pemrograman

❌ TIDAK DIPERBOLEHKAN:
- Aktivitas ilegal atau melanggar hukum
- Pelanggaran hak cipta/kekayaan intelektual
- Penyalahgunaan sistem pendidikan tanpa izin
- Pencurian data atau akses tidak sah
- Distribusi komersial tanpa izin tertulis

---

⚠️ DISCLAIMER

PERINGATAN PENTING:
1. Tanggung Jawab Pengguna: Anda bertanggung jawab penuh atas semua konsekuensi penggunaan.
2. Tujuan Edukasi: Tools ini dibuat hanya untuk pembelajaran, BUKAN untuk kecurangan akademik.
3. Etika Akademik: Hormati kebijakan institusi pendidikan Anda.
4. Keamanan Data: Lindungi kredensial dan data sensitif Anda.
5. Kepatuhan Hukum: Patuhi hukum dan Terms of Service yang berlaku.

Dengan menggunakan tools ini, Anda menyetujui:
1. Menggunakan hanya untuk tujuan sah
2. Bertanggung jawab penuh atas semua konsekuensi
3. Tidak menyalahgunakan untuk kegiatan ilegal
---

📞 KONTAK
- Kontak: @Fuuma16 (Telegram)
- Telegram: https://t.me/Fuuma16
- Issues: GitHub Issues page

---

© 2025 Fuuma - Happy Learning! 🎓
