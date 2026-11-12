# Rekap Absensi Perangkat Desa

Aplikasi web single-file untuk mengolah dan menampilkan rekap absensi perangkat Desa Wonokerto dari file Excel.

## Description

Aplikasi dashboard absensi perangkat desa berbasis HTML yang membaca beberapa file Excel, menggabungkan data kehadiran, lalu menampilkan matriks kalender harian, skor kedisiplinan, persentase kehadiran, serta rincian log absensi dengan filter dan fitur cetak responsif.

## Fitur

- Memuat satu atau beberapa file Excel absensi.
- Menggabungkan data absensi dari beberapa periode.
- Menampilkan matriks kalender absensi harian.
- Menampilkan skor kedisiplinan dan persentase kehadiran.
- Menampilkan rincian waktu masuk, waktu keluar, dan durasi kerja.
- Menyediakan filter berdasarkan aparatur.
- Menyediakan pencetakan tiap tabel.
- Mendukung tampilan desktop, tablet, dan mobile.
- Menyimpan state aplikasi di `localStorage` browser.

## Menjalankan Aplikasi

1. Buka `index.html` menggunakan browser modern.
2. Unggah satu atau beberapa file `.xlsx` melalui kontrol unggah.
3. Periksa hasil rekap pada tabel dan kalender yang tersedia.

Aplikasi tidak memerlukan server atau proses instalasi. Koneksi internet diperlukan saat pertama kali memuat CDN Tailwind CSS, Chart.js, SheetJS, dan Font Awesome.

## Format Data Excel

Data Excel sebaiknya memiliki kolom berikut:

- `Nama`
- `Jabatan`
- `Tanggal`
- `Jam Masuk`
- `Jam Keluar`

Nama kolom tidak harus sama persis pada variasi huruf besar-kecil yang didukung aplikasi. Pastikan setiap workbook menggunakan struktur data yang konsisten.

## Teknologi

- HTML, CSS, dan JavaScript
- Tailwind CSS CDN
- SheetJS `xlsx@0.18.5`
- Chart.js
- Font Awesome 6.5.1

## Berkas Utama

- `index.html` — aplikasi utama.
- `Rekap Absensi.html` — berkas sumber/versi awal.
- `kehadiran_*.xlsx` — contoh workbook absensi.

## Lisensi

Proyek ini dirilis di bawah [MIT License](LICENSE).
