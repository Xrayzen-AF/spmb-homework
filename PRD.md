# Product Requirement Document (PRD)

## 1. Ringkasan Produk

Sebuah landing page statis untuk Sistem Penerimaan Murid Baru (SPMB) SMK Budi Bakti Ciwidey tahun ajaran 2026/2027. Tujuannya adalah memberikan informasi program keahlian, menonjolkan fasilitas unggulan, dan memudahkan calon peserta didik melakukan pendaftaran.

## 2. Tujuan Produk

- Meningkatkan kesadaran siswa dan orang tua tentang pendaftaran SPMB 2026/2027.
- Menampilkan tiga program keahlian utama: PPLG, DKV, BRP.
- Menunjukkan fasilitas sekolah yang relevan dengan setiap kompetensi.
- Mengarahkan pengguna untuk mendaftar melalui tautan formulir online.

## 3. Sasaran Pengguna

- Calon peserta didik kelas 10 SMK.
- Orang tua atau wali yang mencari sekolah menengah kejuruan.
- Pengunjung yang ingin mengetahui keunggulan SMK Budi Bakti Ciwidey.

## 4. Lingkup Fungsional

### 4.1. Navigasi
- Header tetap di atas layar.
- Tautan ke bagian Beranda, Program Keahlian, Kontak, dan tombol Daftar.
- Menu mobile dengan opsi yang sama untuk tampilan kecil.

### 4.2. Hero Section
- Judul utama yang jelas dan menarik.
- Pesan nilai singkat.
- Tombol CTA `Daftar Sekarang` yang mengarahkan ke formulir pendaftaran.
- Statistik ringkas (jumlah program, alumni, tingkat serapan industri).

### 4.3. Program Keahlian
- Tiga kartu program keahlian dengan gambar, nama singkat, dan deskripsi.
- Tombol `selengkapnya...` membuka modal yang menjelaskan setiap jurusan.

### 4.4. Modal Jurusan
- Menampilkan informasi jurusan secara detail.
- Menyediakan tag, judul, subtitle, deskripsi, dan daftar skill utama.
- Dapat ditutup dengan tombol atau klik di luar modal.

### 4.5. Fasilitas
- Carousel atau slider untuk tiga fasilitas unggulan.
- Kontrol navigasi slide dan indikator dot.
- Ringkasan fitur fasilitas per jurusan.

### 4.6. Bagian Pendaftaran
- Pesan urgensi kuota terbatas.
- Tombol Daftar dan tautan kontak sosial.
- Tautan ke WhatsApp, Instagram, dan TikTok.

### 4.7. Footer
- Copyright.
- Kredit pengembangan.

## 5. Kebutuhan Non-Fungsional

- Desain responsif untuk desktop dan mobile.
- Waktu muat cepat dengan Tailwind CSS CDN.
- Navigasi dan interaksi sederhana.
- Kompatibilitas pada browser modern.

## 6. Konten dan Desain

- Palet warna utama: biru, putih, krem, dan aksen kuning.
- Tipografi modern dan mudah dibaca.
- Visual yang bersih dan profesional.
- Gambar latar dan ikon mendukung pesan sekolah.

## 7. Persyaratan Teknis

- Struktur: `index.html` sebagai halaman utama.
- Aset gambar di `assets/img/`.
- Tailwind CSS dimuat melalui CDN.
- JavaScript vanilla untuk interaksi modal, menu mobile, dan carousel.

## 8. Sukses / Indikator Keberhasilan

- Pengunjung mengklik tombol Daftar.
- Informasi jurusan lebih mudah dipahami.
- Kesan profesional dan kredibel bagi sekolah.
- Tampilan berfungsi baik di desktop dan mobile.

## 9. Batasan

- Halaman ini hanya front-end statis, tidak menyimpan data pendaftaran.
- Formulir pendaftaran dialihkan ke layanan eksternal.
- Tidak ada integrasi backend atau database.
