<div align="center">
  <img src="https://raw.githubusercontent.com/Babinsa05/LILIGUNDI/main/android-chrome-512x512.png" width="120" alt="Logo DUKOPS">
  <h1>📱 DUKOPS BABINSA LILIGUNDI</h1>
  <p><strong>Aplikasi Pendukung Data dan Operasional Babinsa</strong></p>
  <p>Koramil 1609-01/Buleleng - Kodim 1609/Buleleng</p>
  <p>Kelurahan Liligundi, Kecamatan Buleleng, Kabupaten Buleleng - Bali</p>
  
  [![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://babinsa05.github.io/LILIGUNDI/)
  [![Supabase](https://img.shields.io/badge/Supabase-Realtime-blue)](https://supabase.com)
  [![Version](https://img.shields.io/badge/Version-2.0-orange)](https://github.com/Babinsa05/LILIGUNDI)
</div>

## 📋 Tentang Aplikasi

**DUKOPS BABINSA LILIGUNDI** merupakan sebuah sistem informasi berbasis web yang dirancang untuk mendukung kelancaran tugas pokok Bintara Pembina Desa (Babinsa) dalam melaksanakan dokumentasi dan pelaporan kegiatan operasional.

Aplikasi ini dikembangkan sebagai wujud sinergi antar satuan jajaran Kodim 1609/Buleleng, dengan tujuan mempermudah proses pelaporan DUKOPS (Dukung Operasi) Babinsa di wilayah Kelurahan Liligundi.

### Tujuan Pengembangan

| Tujuan | Deskripsi |
|--------|-----------|
| 📸 **Dokumentasi Digital** | Memudahkan dokumentasi kegiatan Babinsa dalam bentuk digital |
| 📝 **Pelaporan Terstruktur** | Menyediakan format pelaporan yang sistematis dan seragam |
| 💬 **Komunikasi Real-time** | Memfasilitasi komunikasi antar pengguna secara langsung |
| 📦 **Arsip Digital** | Menyimpan arsip laporan dalam format yang rapi dan mudah diakses |

---

## ✨ Fitur Unggulan

| No | Fitur | Keterangan |
|----|-------|-------------|
| 1 | 🔐 **Sistem Autentikasi** | Login dengan nama pengguna sebagai identitas |
| 2 | 📸 **Unggah Foto** | Pengambilan foto kegiatan dari galeri atau kamera |
| 3 | 🖼️ **Pratinjau Kanvas** | Tampilan foto dengan overlay informasi kegiatan |
| 4 | 🎨 **Pengaturan Tipografi** | Penyesuaian ukuran huruf pada kanvas secara fleksibel |
| 5 | 📅 **Format Tanggal Indonesia** | Menggunakan format "01 Januari 2026, 13:23:34" |
| 6 | 📝 **Template Narasi** | Tersedia 5 kategori template narasi kegiatan Babinsa |
| 7 | 💾 **Unduh PNG & TXT** | Ekspor dokumentasi sebagai file gambar dan teks |
| 8 | 📦 **Arsip ZIP** | Pengemasan laporan dalam satu file terkompresi |
| 9 | 📜 **Riwayat Laporan** | Pencatatan seluruh laporan yang telah dihasilkan |
| 10 | 💬 **Percakapan Langsung** | Fitur chat real-time antar pengguna yang sedang aktif |
| 11 | 👥 **Pemantauan Pengguna Aktif** | Menampilkan jumlah pengguna yang sedang mengakses aplikasi |
| 12 | 📱 **PWA Ready** | Dapat dipasang pada layar utama perangkat mobile |

---

## 🚀 Cara Mengakses Aplikasi

### 🌐 Melalui GitHub Pages (Daring)
```

https://babinsa05.github.io/LILIGUNDI/

```
> **Catatan**: Ganti `babinsa05` dengan nama akun GitHub Anda, dan `LILIGUNDI` dengan nama repositori yang digunakan.

### 💻 Menjalankan Secara Lokal (Pengembangan)
```bash
# Klon repositori
git clone https://github.com/username/LILIGUNDI.git

# Buka berkas index.html menggunakan peramban web
# Direkomendasikan menggunakan live server untuk pengembangan
npx live-server
```

---

📱 Cara Pemasangan Aplikasi di Perangkat Mobile (PWA)

Android (Peramban Chrome)

1. Buka aplikasi melalui peramban Chrome
2. Ketuk ikon titik tiga (⋮) di sudut kanan atas
3. Pilih opsi "Install App" atau "Tambahkan ke Layar Utama"
4. Konfirmasi dengan menekan Install

iOS (Peramban Safari)

1. Buka aplikasi melalui peramban Safari
2. Ketuk ikon Bagikan (persegi dengan panah ke atas)
3. Gulir ke bawah dan pilih "Tambahkan ke Layar Utama"
4. Ketuk Tambah pada pojok kanan atas

---

🛠️ Teknologi yang Digunakan

Teknologi Fungsi
HTML5 Kerangka dasar aplikasi
CSS3 Tata letak dan animasi antarmuka
JavaScript Logika pemrograman sisi klien
Supabase Layanan backend real-time (pesan & kehadiran)
JSZip Pembuatan berkas arsip ZIP
Font Awesome Koleksi ikon
GitHub Pages Hosting statis gratis

---

📂 Struktur Berkas

```
LILIGUNDI/
├── index.html                  # Aplikasi utama
├── README.md                   # Dokumentasi aplikasi
├── sw.js                       # Service Worker (dukungan PWA)
├── site.webmanifest            # Manifest PWA
├── android-chrome-512x512.png  # Ikon ukuran 512px
├── android-chrome-192x192.png  # Ikon ukuran 192px
├── profile liligundi.png       # Logo pada header aplikasi
└── template-narasi.json        # Berkas template narasi (opsional)
```

---

🔧 Konfigurasi Supabase (Untuk Fitur Percakapan Langsung)

Fitur Live Chat pada aplikasi ini memanfaatkan layanan Supabase Realtime.

Langkah-langkah Konfigurasi Mandiri:

1. Registrasi di supabase.com
2. Buat proyek baru (disarankan memilih region Singapura untuk latensi optimal)
3. Ambil kredensial melalui menu Settings → API:
   · Project URL
   · anon public key
4. Sesuaikan pada berkas index.html:

```javascript
const SUPABASE_URL = 'https://id-proyek-anda.supabase.co';
const SUPABASE_ANON_KEY = 'kunci-anon-anda';
```

Informasi: Jika tidak menggunakan konfigurasi sendiri, fitur percakapan tetap dapat berjalan dengan akun demo yang tersedia.

---

📸 Panduan Penggunaan Aplikasi

1. Tahap Masuk (Login)

· Masukkan nama pengguna pada kolom yang tersedia
· Nama akan digunakan sebagai identitas dalam fitur percakapan

2. Tahap Pembuatan Laporan

· Isi Judul Kegiatan
· Unggah Foto Kegiatan dari perangkat
· Pilih Tanggal & Waktu pelaksanaan kegiatan
· Tuliskan Narasi kegiatan
· Klik tombol SIMPAN ZIP atau PNG+TXT

3. Pengaturan Ukuran Huruf pada Kanvas

· Klik tombol 🔤 Aa pada sudut kiri bawah
· Geser pengatur (slider) untuk mengubah ukuran huruf
· Klik Simpan untuk menyimpan pengaturan

4. Penggunaan Fitur Percakapan Langsung

· Klik ikon 💬 pada sudut kanan bawah
· Ketik pesan pada kolom yang tersedia
· Tekan Kirim atau tombol Enter
· Pantau jumlah pengguna aktif yang tertera pada header percakapan

5. Penggunaan Template Narasi

· Klik tombol ✨ (Sihir) pada sudut kanan area teks narasi
· Pilih kategori template yang diinginkan
· Klik salah satu template untuk mengisi narasi secara otomatis

---

❓ Pertanyaan yang Sering Diajukan (FAQ)

Q: Aplikasi tidak dapat mengunggah foto?

A: Pastikan berkas foto berukuran tidak melebihi 5MB dan dalam format yang didukung (JPG, JPEG, PNG).

Q: Fitur percakapan tidak berfungsi?

A: Periksa koneksi internet. Jika masih mengalami kendala, pastikan konfigurasi Supabase telah diset dengan benar.

Q: Hasil unduhan ZIP tidak dapat dibuka?

A: Gunakan aplikasi pengekstrak ZIP seperti WinRAR, 7-Zip, atau ekstraktor bawaan sistem operasi.

Q: Apakah aplikasi mendukung banyak pengguna secara bersamaan?

A: Ya, aplikasi dirancang untuk melayani banyak pengguna secara real-time melalui infrastruktur Supabase.

Q: Di mana data laporan disimpan?

A: Data laporan tersimpan pada penyimpanan lokal (localStorage) masing-masing peramban. Untuk penyimpanan terpusat diperlukan pengembangan backend tambahan.

---

🐛 Pelaporan Masalah

Apabila menemukan kendala teknis atau bug pada aplikasi, dapat dilaporkan melalui:

1. GitHub Issues pada repositori ini
2. Deskripsikan masalah secara rinci
3. Sertakan tangkapan layar jika diperlukan
4. Sebutkan jenis peramban dan perangkat yang digunakan

---

👨‍💻 Profil Pengembang

<div align="center">
  <table border="0">
    <tr>
      <td align="center">
        <img src="https://raw.githubusercontent.com/Babinsa05/LILIGUNDI/main/android-chrome-512x512.png" width="80" style="border-radius: 50%;">
        <br>
        <strong>Serka I Nyoman Arta</strong>
        <br>
        <sub>Koramil 1609-05/Sukasada</sub>
        <br>
        <sub>Kodim 1609/Buleleng</sub>
      </td>
    </tr>
  </table>
</div>

Serka I Nyoman Arta bertugas sebagai pengembang aplikasi yang turut mendukung Koramil 1609-01/Buleleng dalam upaya modernisasi dan digitalisasi pelaporan DUKOPS Babinsa. Aplikasi ini merupakan wujud nyata sinergi antar satuan jajaran Kodim 1609/Buleleng untuk meningkatkan efektivitas dan efisiensi pelaksanaan tugas Babinsa di wilayah.

https://img.shields.io/badge/GitHub-Babinsa05-181717?logo=github

---

🙏 Ucapan Terima Kasih

Kami menyampaikan penghargaan dan terima kasih yang sebesar-besarnya kepada:

· Komando Distrik Militer 1609/Buleleng atas dukungan kebijakan
· Koramil 1609-01/Buleleng atas kepercayaan dan kerja sama
· Masyarakat Kelurahan Liligundi atas partisipasi dan dukungan
· Serka I Nyoman Arta (Koramil 1609-05/Sukasada) sebagai pengembang aplikasi
· Supabase atas penyediaan layanan backend real-time
· Font Awesome atas koleksi ikon yang digunakan

---

📄 Lisensi

```
Copyright © 2024 - TNI AD, Kodim 1609/Buleleng

Aplikasi ini dikembangkan untuk kepentingan operasional satuan jajaran Kodim 1609/Buleleng.
Dilarang memperbanyak, mendistribusikan, atau menggunakan tanpa izin dari pihak berwenang.
```

---

<div align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Babinsa05/LILIGUNDI/main/android-chrome-512x512.png" width="60">
  <br>
  <h3>DUKOPS BABINSA LILIGUNDI</h3>
  <p><i>"Bersama Rakyat, TNI Kuat"</i></p>
  <br>
  <table width="100%">
    <tr>
      <td align="center">
        <sub>Dikembangkan oleh:</sub><br>
        <strong>Serka I Nyoman Arta</strong><br>
        <sub>Koramil 1609-05/Sukasada</sub>
        </td>
      <td align="center">
        <sub>Didistribusikan untuk:</sub><br>
        <strong>Koramil 1609-01/Buleleng</strong><br>
        <sub>Kelurahan Liligundi</sub>
        </td>
    </tr>
  </table>
  <br>
  <sub>© 2024 - Kodim 1609/Buleleng, TNI AD</sub>
  <br>
  <sub>Aplikasi Pendukung Data dan Operasional Babinsa</sub>
</div>
```

---

📝 Cara Copy & Paste:

1. Klik dan seret dari baris pertama (<div align="center">) sampai baris terakhir (</div>)
2. Tekan Ctrl+C (Windows) atau Cmd+C (Mac)
3. Buka repository GitHub Anda
4. Buat file baru dengan nama README.md atau edit yang sudah ada
5. Paste (Ctrl+V / Cmd+V)
6. Klik "Commit changes"

Selesai!. 🚀