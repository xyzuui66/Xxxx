# 🛡️ Web Guard Ultra-Security Gateway v5.0

Sistem pertahanan eksternal berbasis web untuk melindungi infrastruktur dari serangan siber (DDoS, Bot, & Unauthorized Access). Dilengkapi dengan fitur **Attacker Tracker** untuk melacak identitas teknis penyerang secara real-time.

## ⚠️ Disclaimer (PENTING)
Proyek ini dibuat untuk tujuan **Edukasi dan Riset Keamanan Siber**. Penulis tidak bertanggung jawab atas penyalahgunaan alat ini. Melakukan pengujian tanpa izin pada infrastruktur pihak ketiga adalah tindakan ilegal.

---

## 🚀 Fitur Unggulan
* **High-Security Gateway:** Bertindak sebagai lapisan pertama (First Layer) sebelum trafik menyentuh server asli.
* **Anti-DDoS Challenge:** Memaksa browser melewati proses verifikasi integritas sebelum akses diberikan.
* **Attacker Tracker:** Melacak alamat IP, lokasi geografis (Kota/Negara), dan ISP penyerang secara otomatis.
* **Threat Monitor:** Dashboard visual untuk memantau jumlah ancaman yang berhasil diblokir.
* **Encrypted Path:** Menyembunyikan URL asli website utama dari publik melalui teknik *iframe masking*.

---

## 🛠️ Instalasi & Penggunaan
1.  Buat repository publik di GitHub.
2.  Upload file `index.html` (kode Web Guard) ke repository tersebut.
3.  Aktifkan **GitHub Pages** di menu *Settings > Pages*.
4.  Gunakan link GitHub Pages tersebut sebagai "Link Pintu Masuk" resmi website Anda.

---

## 📊 Cara Kerja Pelacakan (Tracker)
Sistem ini menggunakan API intelijen IP untuk mengidentifikasi setiap koneksi yang masuk. Jika terdeteksi aktivitas mencurigakan atau volume trafik tinggi (DDoS), sistem akan:
1.  Mencatat IP publik penyerang.
2.  Mengidentifikasi penyedia internet (ISP) yang digunakan.
3.  Menampilkan data tersebut di panel keamanan untuk tindakan blokir lebih lanjut.

---

## 📝 Lisensi
Proyek ini dilisensikan di bawah **MIT License**. Lihat file `LICENSE` untuk informasi lebih lanjut.

