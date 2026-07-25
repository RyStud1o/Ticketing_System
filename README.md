# MANCUP Ticket Tracker 🎟️

Sistem pelacakan dan validasi tiket lokal berbasis web untuk event **MANCUP**, diselenggarakan oleh OSIM MAN Kapuas. Sistem ini dirancang untuk memproses pendataan penonton secara cepat, ringan, dan murni berjalan di sisi klien (*Client-Side*).

## ✨ Fitur Utama
- **Aktivasi Tiket:** Validasi manual dengan sistem pencegahan duplikasi di hari yang sama.
- **Generator Tiket:** Pembuatan ID tiket berurutan secara otomatis (FT0001, dst) beserta dukungan import massal ratusan tiket sekaligus melalui file CSV.
- **Dashboard Analitik:** Pantauan statistik *real-time*, tren grafik mingguan, dan manajemen database lokal dengan filter status tiket (Belum Dipakai, Sedang Aktif, Habis, Dinonaktifkan).
- **Export Data:** Unduh laporan harian, seluruh riwayat aktivasi, dan database tiket ke dalam format CSV untuk keperluan arsip.
- **Local Storage Database:** Data tersimpan murni dan aman di dalam perangkat yang digunakan tanpa memerlukan server atau database eksternal.

## 🚀 Teknologi yang Digunakan
- **HTML5 & CSS3**
- **Vanilla JavaScript (ES6)**
- **Tailwind CSS** (via CDN untuk antarmuka *clean* dan minimalis)

## 🛠️ Cara Penggunaan
1. Unduh atau *clone* repositori ini ke penyimpanan lokal.
2. Buka file `index.html` menggunakan peramban (browser) modern apa pun.
3. Sistem akan memuat basis data lokal dan langsung siap digunakan.

## ⚠️ Catatan Pemeliharaan
Sistem ini menggunakan *Local Storage* peramban. Menghapus *cache* atau data situs web pada peramban akan mengakibatkan hilangnya data tiket. Pastikan untuk secara rutin melakukan **Export Database** melalui halaman Dashboard sebagai cadangan.

## 👨‍💻 Pengembang
- **Lead Developer:** Jepry ([@vryy7_](https://instagram.com/vryy7_))
- **Organisasi:** OSIM MAN Kapuas ([@osimmankapuas](https://instagram.com/osimmankapuas))
- **Powered by:** [@ryystud10](https://instagram.com/ryystud10)

---
*Dikembangkan khusus untuk mendukung kelancaran administrasi dan keamanan event di lingkungan sekolah.*