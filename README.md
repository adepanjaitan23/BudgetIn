🚀 BudgetIn: Modern Budgeting Web App (Powered by Google Sheets)

🚀 BudgetIn

Modern Personal Finance Dashboard Web Application




BudgetIn mentransformasikan Google Sheets biasa menjadi aplikasi web keuangan pribadi (Fintech-style dashboard) yang modern, interaktif, dan responsif. Aplikasi ini melacak pengeluaran, mengelola anggaran, dan memvisualisasikan data keuangan Anda secara real-time, sembari memastikan seluruh data keuangan tetap aman dan privat di dalam Google Drive Anda sendiri.

💡 Disclaimer: Aplikasi ini berjalan 100% di dalam ekosistem Google Anda pribadi tanpa server luar, sehingga keamanan dan privasi data keuangan Anda terjamin sepenuhnya.

🌟 Fitur Utama

🔄 Sinkronisasi Real-time: Setiap perubahan di web (seperti menambah alokasi, mencentang pembayaran, atau mengubah kategori) otomatis tersimpan ke Google Sheets tanpa reload.

📊 Visualisasi Interaktif: Dilengkapi Bar Chart (Pill-style) dan Doughnut Chart interaktif yang digerakkan oleh Chart.js.

📱 Sangat Responsif: Tampilan tabel desktop otomatis berubah menjadi tata letak kartu (Card layout) yang nyaman saat dibuka di ponsel (Mobile).

🏷️ Kustomisasi Dinamis: Tambahkan Akun/Wallet baru atau Kategori pengeluaran baru langsung melalui jendela Pop-up di dalam Web App tanpa perlu repot membuka spreadsheet.

💸 Fitur Cek Lunas & Progress Bar: Centang tagihan bulanan untuk melihat teks tercoret otomatis dan saksikan bar realisasi pengeluaran bertambah panjang.

👋 Auto-Greeting & Multi-Month: Menyapa pengguna secara otomatis sesuai akun Google yang masuk serta memfilter data rapi berdasarkan bulan dan tahun.

📸 Contoh Tampilan Antarmuka

Sistem menyajikan visualisasi data yang bersih dan dinamis berdasarkan alokasi anggaran bulanan Anda.

1. Tampilan Dashboard Utama


2. Fitur Kustomisasi Wallet & Kategori


🛠️ Teknologi yang Digunakan

Proyek ini dibangun menggunakan tumpukan teknologi modern tanpa memerlukan database eksternal berbayar:

Frontend: HTML5, Vanilla JavaScript, Tailwind CSS (via CDN)

Visualisasi Data: Chart.js

Ikon & Tipografi: FontAwesome 6 & Google Fonts (Inter)

Backend & API: Google Apps Script (GAS)

Database: Google Sheets

📂 Susunan Proyek

Struktur file dalam repositori ini:

budgetin/
├── Code.gs             # 🚀 Backend Google Apps Script (Database & Validation Handler)
└── Index.html          # 🎨 Single-file Frontend (UI Tailwind, Chart.js, & Client Logic)


🚀 Cara Instalasi & Penggunaan (Panduan Singkat)

Anda dapat membuat instance BudgetIn Anda sendiri dalam waktu kurang dari 5 menit:

Langkah 1: Salin Template Database

Pastikan Anda sudah login ke akun Google Anda.

Klik link berikut untuk menyalin template database:

👉 Salin Template BudgetIn

Klik tombol "Buat salinan" (Make a copy).

Langkah 2: Masukkan Kode

Di file Google Sheets Anda, pilih menu Ekstensi > Apps Script.

Hapus kode bawaan di Code.gs, lalu tempelkan (paste) seluruh isi dari file Code.gs repositori ini.

Buat file HTML baru dengan menekan ikon [+], beri nama Index (tanpa ekstensi .html), lalu tempelkan kode dari file Index.html repositori ini.

Klik ikon Simpan (💾).

Langkah 3: Deploy sebagai Aplikasi Web

Di pojok kanan atas editor Apps Script, klik Terapkan (Deploy) > Deployment baru.

Klik ikon roda gigi (⚙️) di sebelah "Pilih jenis", lalu pilih Aplikasi web.

Atur konfigurasi berikut:

Deskripsi: BudgetIn v1

Jalankan sebagai: Saya (Me)

Siapa yang memiliki akses: Siapa saja (Anyone)

Klik Terapkan. Berikan izin keamanan Google (Otorisasi akses > Lanjutan > Buka project tak aman > Izinkan).

Salin URL Aplikasi Web yang muncul!

💡 Tips Mobile: Buka URL tersebut di browser HP Anda (Safari/Chrome), lalu pilih menu "Add to Home Screen". BudgetIn akan berfungsi layaknya aplikasi native di ponsel Anda!

🤝 Kontribusi

Kontribusi, perbaikan bug, dan ide fitur baru selalu terbuka lebar!

Lakukan Fork pada repositori ini.

Buat branch fitur Anda (git checkout -b fitur-baru-anda).

Commit perubahan Anda (git commit -m 'Menambahkan fitur keren').

Push ke branch tersebut (git push origin fitur-baru-anda).

Kirimkan Pull Request.

📝 Lisensi

Proyek ini bersifat sumber terbuka (open-source) di bawah Lisensi MIT. Silakan gunakan, modifikasi, dan distribusikan sesuai kebutuhan Anda.

Dibangun dengan ❤️ menggunakan BudgetIn
