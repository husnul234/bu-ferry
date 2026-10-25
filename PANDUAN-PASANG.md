# PANDUAN PEMASANGAN TEMPLATE TAMPILAN BARU
## Google Sites Portofolio Guru — Ferry Indra Arsanti, S.Pd

Panduan ini berisi petunjuk teknis langkah demi langkah untuk memasang blok kode sematan (*embed code*) HTML/CSS baru ke halaman Google Sites portofolio guru Ibu **Ferry Indra Arsanti, S.Pd** (`https://sites.google.com/guru.paud.belajar.id/ferryindraarsanti`).

Semua file template tersimpan di dalam folder:
`d:\1. MIZTERGOOD\04 - Keuangan dan Bisnis\JASA\12. BU FERRRY\ferry-site-template\`

---

## 1. Struktur Folder Template

```text
ferry-site-template/
├── blok/                      <- 19 file blok sematan HTML siap tempel (satu blok = satu file)
│   ├── 01-halaman-muka-blok1-hero.html
│   ├── 01-halaman-muka-blok2-menu.html
│   ├── 01-halaman-muka-blok3-quote.html
│   ├── 02-profil-guru-blok1.html
│   ├── 03-portofolio-guru-blok1.html
│   ├── 04-pengembangan-diri-blok1.html
│   ├── 04-pengembangan-diri-blok2.html
│   ├── 04-pengembangan-diri-blok3.html
│   ├── 05-pendampingan-blok1.html
│   ├── 05-pendampingan-blok2.html
│   ├── 06-organisasi-profesi-blok1.html
│   ├── 06-organisasi-profesi-blok2.html
│   ├── 07-karya-inovasi-blok1.html
│   ├── 07-karya-inovasi-blok2.html
│   ├── 08-prestasi-penghargaan-blok1.html
│   ├── 09-komunitas-intrasekolah-blok1.html
│   ├── 10-komunitas-antarsekolah-blok1.html
│   ├── 11-bukti-implementasi-blok1.html
│   └── 11-bukti-implementasi-blok2.html
├── pratinjau/                 <- 11 file HTML pratinjau penuh per halaman (bisa dibuka langsung di browser)
│   ├── 01-pratinjau-halaman-muka.html
│   ├── 02-pratinjau-profil-guru.html
│   ├── 03-pratinjau-portofolio-guru.html
│   ├── 04-pratinjau-kegiatan-pengembangan-diri.html
│   ├── 05-pratinjau-pendampingan-rekan-sejawat.html
│   ├── 06-pratinjau-pengalaman-organisasi-profesi.html
│   ├── 07-pratinjau-karya-inovasi.html
│   ├── 08-pratinjau-prestasipenghargaan.html
│   ├── 09-pratinjau-partisipasi-komunitas-intrasekolah.html
│   ├── 10-pratinjau-partisipasi-komunitas-antarsekolah.html
│   └── 11-pratinjau-bukti-implementasi-karya-inovasi.html
├── screenshot/                <- 22 tangkapan layar verifikasi Playwright (Desktop 1280px & Mobile 390px)
└── PANDUAN-PASANG.md          <- Dokumen panduan ini
```

---

## 2. Cara Memasang Blok ke Google Sites

Ikuti langkah-langkah berikut untuk setiap blok:

1. **Buka Editor Google Sites:**
   Kunjungi tautan editor Google Sites portofolio Bu Ferry dengan akun belajar.id yang berwenang.
2. **Buka Halaman Target:**
   Pada panel kanan editor, klik tab **Halaman** (*Pages*), lalu pilih halaman yang ingin diubah (misalnya `Profil Guru`).
3. **Bersihkan Blok Lama yang Digantikan:**
   Hapus tata letak kotak teks atau gambar lama yang ingin digantikan dengan desain baru (jangan hapus navigasi atas dan footer situs).
4. **Buka Menu Sematkan:**
   Pada panel kanan, klik tab **Sisipkan** (*Insert*) > pilih alat **Sematkan** (*Embed* / ikon `< >`).
5. **Pilih Tab Kode Sematan:**
   Pada jendela pop-up yang muncul, pilih tab **Kode sematan** (*Embed code*).
6. **Salin Kode Blok:**
   Buka file `.html` blok yang bersangkutan di folder `ferry-site-template/blok/` menggunakan editor teks (Notepad, VS Code, atau browser), tekan `Ctrl + A` lalu `Ctrl + C`.
7. **Tempel dan Simpan:**
   Tempel kode (`Ctrl + V`) ke kotak kode sematan Google Sites, lalu klik **Berikutnya** (*Next*) > klik **Sisipkan** (*Insert*).
8. **Atur Lebar & Tinggi Sematan:**
   - **Lebar:** Tarik handle kotak sematan ke kiri dan ke kanan hingga memenuhi grid lebar maksimum halaman (12 kolom penuh).
   - **Tinggi:** Tarik handle bagian bawah kotak sematan ke bawah sesuai tabel rekomendasi tinggi piksel di bawah ini agar tidak muncul bilah gulir vertikal ganda di dalam kotak sematan.
9. **Ulangi untuk Blok Berikutnya:**
   Jika suatu halaman memiliki lebih dari 1 blok, sisipkan blok berikutnya tepat di bawah blok sebelumnya secara berurutan.
10. **Publikasikan:**
    Klik tombol **Publikasikan** (*Publish*) di pojok kanan atas editor.

---

## 3. Daftar Halaman, Urutan Blok & Rekomendasi Tinggi Embed

> **Catatan Teknis Google Sites Embed:**
> Google Sites menampilkan sematan dalam elemen `<iframe>`. Tinggi embed diatur secara manual dengan menarik handle bawah di canvas editor Sites. Nilai piksel di bawah ini adalah hasil pengukuran aktual Playwright ditambah toleransi ruang aman +30px.

| No | Halaman Sites | File Blok (Urutan Pasang) | Rekomendasi Tinggi Desktop | Rekomendasi Tinggi HP/Mobile | Keterangan Isi Blok |
|:---|:---|:---|:---:|:---:|:---|
| **01** | **Halaman Muka** | `01-halaman-muka-blok1-hero.html`<br>`01-halaman-muka-blok2-menu.html`<br>`01-halaman-muka-blok3-quote.html` | ~930 px<br>~1.030 px<br>~350 px | ~1.150 px<br>~2.160 px<br>~420 px | **Blok 1:** Banner Hero, potret guru, sambutan & tombol CTA.<br>**Blok 2:** Grid 10 menu navigasi portofolio.<br>**Blok 3:** Kartu filosofi langkah & ikhtiar. |
| **02** | **Profil Guru** | `02-profil-guru-blok1.html` | ~2.880 px | ~3.060 px | Foto resmi guru, identitas pendidik, filosofi mengajar, narasi lengkap rekam jejak, garis waktu pendidikan formal (SD–S1 PAUD), 4 tombol media sosial, dan sematan peta lokasi Google Maps. |
| **03** | **Portofolio Guru (Induk)** | `03-portofolio-guru-blok1.html` | ~1.450 px | ~2.160 px | Etalase landing portal: 3 kartu utama atas (Pengembangan Diri, Pendampingan, Organisasi Profesi), 2 kartu utama bawah (Karya Inovasi, Prestasi), plus strip Komunitas Belajar & Implementasi. |
| **04** | **Kegiatan Pengembangan Diri** | `04-pengembangan-diri-blok1.html`<br>`04-pengembangan-diri-blok2.html`<br>`04-pengembangan-diri-blok3.html` | ~1.390 px<br>~2.050 px<br>~2.460 px | ~2.160 px<br>~2.160 px<br>~2.560 px | **Blok 1 (Kegiatan 1–4):** Deep Learning, Inspirative Teacher, Simposium Jatim 2024, Perlindungan Profesi Guru.<br>**Blok 2 (Kegiatan 5–9):** Guru Cerdas Finansial, Prasiaga, PembaTIK, Bimtek Anak Kesulitan Belajar (galeri 4 thumbnail), PESILAT BBGP Jatim.<br>**Blok 3 (Kegiatan 10–14):** PENDEKAR BBGP Jatim, 8 Standar Nasional, Guru Penggerak Angkatan 7, Workshop P5, PembaTIK 2023 (galeri 6 thumbnail). |
| **05** | **Pendampingan Rekan Sejawat** | `05-pendampingan-blok1.html`<br>`05-pendampingan-blok2.html` | ~1.420 px<br>~1.810 px | ~2.160 px<br>~2.160 px | **Blok 1 (Kegiatan 1–4):** Pengimbasan Modul Ajar Canva, Bimtek Digitalisasi Chromebook, Sosialisasi Sulingjar, Penguatan Wawasan Kebangsaan.<br>**Blok 2 (Kegiatan 5–8):** Diseminasi PembaTIK Level 2, Pembuatan KOSP Kurikulum Merdeka, Diseminasi Praktik Baik Modul 1.4 PGP, Kolaborasi Media Ajar Digital PAUD. |
| **06** | **Pengalaman Organisasi Profesi** | `06-organisasi-profesi-blok1.html`<br>`06-organisasi-profesi-blok2.html` | ~4.350 px<br>~3.530 px | ~4.030 px<br>~3.500 px | **Blok 1 (Organisasi 1–5):** IGTKI PGRI Semanding (SK 1–3), PGRI Ranting X (SK 4–6), PKG PAUD Dandang Wacana (SK 7–9), Gugus PAUD Adenium (SK 10–12), TPPK Semanding (SK 13–15).<br>**Blok 2 (Organisasi 6–9):** Kombel SEMARAK (SK 16–18), Kombel TK PGRI (SK 19–21), Anggota PGRI Tuban (SK 22–24), Pokja Kurikulum (SK 25–27). Dilengkapi thumbnail pindaian SK resmi yang dapat diklik buka gambar penuh di tab baru. |
| **07** | **Karya Inovasi** | `07-karya-inovasi-blok1.html`<br>`07-karya-inovasi-blok2.html` | ~1.980 px<br>~1.510 px | ~2.160 px<br>~2.160 px | **Blok 1 (Inovasi Digital):** 1) Game Interaktif "Petualangan Cilik Penyelamat Hutan" (lengkap 5 alur misi interaktif, latar belakang, inovasi, dampak, dan tombol Canva); 2) "GERALING MEDIVA" (Gerakan Anti Bullying Canva interaktif).<br>**Blok 2 (Inovasi Kontekstual):** 3) "PEMANDU" (Permainan Anak Jaman Dulu); 4) "GEBYAR BUNDA" (Business Day Interpreneur Cilik); 5) "COOKING CLASS" (Tahu Crispy). |
| **08** | **Prestasi/Penghargaan** | `08-prestasi-penghargaan-blok1.html` | ~930 px | ~2.160 px | 3 Prestasi Resmi: Juara 2 Guru Prima Kab. Tuban 2024, Juara 1 Lomba Cerdas Cermat Guru IGTKI, Juara 3 Lomba Micro Teaching PAUD. Dilengkapi thumbnail piagam dan tombol buka piagam penuh. |
| **09** | **Partisipasi Komunitas IntraSekolah** | `09-komunitas-intrasekolah-blok1.html` | ~930 px | ~2.160 px | Kerangka siap isi (*ready-to-fill*) dengan format penanda `[ISI ...]` yang terstruktur rapi untuk kegiatan Komunitas Belajar (Kombel) di internal TK PGRI Prunggahan Kulon. |
| **10** | **Partisipasi Komunitas AntarSekolah** | `10-komunitas-antarsekolah-blok1.html` | ~970 px | ~2.160 px | Kerangka siap isi (*ready-to-fill*) dengan format penanda `[ISI ...]` yang terstruktur rapi untuk kolaborasi bersama Gugus PAUD Adenium dan PKG PAUD Kecamatan Semanding. |
| **11** | **Bukti Implementasi Karya Inovasi** | `11-bukti-implementasi-blok1.html`<br>`11-bukti-implementasi-blok2.html` | ~1.440 px<br>~2.370 px | ~2.160 px<br>~2.400 px | **Blok 1 (Implementasi Digital):** 5 langkah implementasi game Pahlawan Cilik, tombol akses langsung Video Praktik Baik YouTube, Canva MPI, dan Game Wordwall.<br>**Blok 2 (Implementasi Kontekstual):** Tahapan jadwal dan dokumentasi nyata Geraling Mediva, PEMANDU (Hari 1–3), Gebyar Bunda, dan Cooking Class Tahu Crispy. |

---

## 4. Catatan Aset Gambar & Media

1. **URL Gambar CDN Asli Google Sites:**
   Seluruh 89 gambar sertifikat, dokumentasi kegiatan, dan foto potret telah dipetakan ke alamat URL resmi Google Sites (`https://sites.google.com/sitesv-images-rt/AMxu72...=w1280`). Dengan demikian, saat kode disematkan ke Google Sites, semua gambar akan **langsung tampil** tanpa harus diunggah ulang ke Drive.
2. **Cadangan Gambar Lokal:**
   Seluruh file gambar asli juga telah diunduh dan tersimpan di folder `ferry-site-extract/assets/` sebagai arsip cadangan.
3. **Latar Belakang Cadangan (Fallback):**
   Setiap wadah foto telah dilengkapi dengan gaya CSS kelas `.foto` dengan latar gradasi lembut (*mint-pink* lembut `#BFE3E6` ke `#F7D6E4`), sehingga tampilan tetap cantik dan tidak bolong seandainya koneksi internet pengguna melambat saat memuat aset gambar.
4. **Logo & Ikon:**
   Ikon navigasi menu dan sosial media (YouTube, Instagram, WhatsApp, Facebook) menggunakan format SVG murni (*inline SVG*), sehingga tampil tajam di semua resolusi layar (*Retina-ready*) dan tidak memerlukan dependensi eksternal.
5. **Google Maps:**
   Peta lokasi sekolah disematkan menggunakan kode semat resmi Google Maps untuk titik koordinat *TK PGRI Prunggahan Kulon, Gang Salak, Kec. Semanding, Kab. Tuban*.

---

## 5. Catatan Ketidaksesuaian / Typo pada Teks Asli

Sesuai instruksi lomba dan integritas data, teks di dalam blok HTML **dipertahankan persis sesuai teks aslinya tanpa diubah**. Namun, berikut adalah daftar catatan salah ketik (*typo*) atau kejanggalan tanggal pada naskah asli situs yang disarankan untuk dikonfirmasi atau diperbaiki oleh Bu Ferry sebelum penilaian final lomba:

| No | Halaman | Kutipan Teks Asli di Situs | Saran Perbaikan / Catatan |
|:---|:---|:---|:---|
| 1 | **02 Profil Guru** | `UNIVERSITAS TERBUKA JURUSAN PENDIDIDKAN ANAK USIA DINI (2015-2017)` | Typo kata `PENDIDIDKAN` (huruf 'DI' berlebih). Seharusnya: `PENDIDIKAN`. |
| 2 | **04 Pengembangan Diri** | `WORKSHOP PENGUATAN 8 STANDART NASIONAL PENDIDIKAN` | Ejaan `STANDART` tidak baku. Seharusnya baku: `STANDAR`. |
| 3 | **04 Pengembangan Diri** | `WEBINARPERLINDUNGAN PROFESI GURU` | Tertulis tanpa spasi antara kata Webinar dan Perlindungan. Seharusnya: `WEBINAR PERLINDUNGAN PROFESI GURU`. |
| 4 | **04 Pengembangan Diri** | `...dari 41 guru penggerak dari kabupeten/kota di Jawa Timur...` | Typo kata `kabupeten`. Seharusnya: `kabupaten`. |
| 5 | **04 Pengembangan Diri** | `PEMBELAJARAN BERBASIS TIK (PembaTIK) TAHUN` | Judul terpotong di kata "TAHUN" tanpa angka tahun. Berdasarkan sertifikat, ini adalah PembaTIK tahun 2024. |
| 6 | **05 Pendampingan** | `6–7 Maret 2026` pada Kegiatan 2 (Bimtek Digitalisasi) | Tertulis tahun `2026` padahal kegiatan telah terlaksana. Seharusnya tahun `2024` atau `2025`. |
| 7 | **06 Organisasi Profesi** | `TPPK Kecamatan Seemanding` | Typo huruf 'e' ganda pada kata `Seemanding`. Seharusnya: `Semanding`. |
| 8 | **07 Karya Inovasi** | `...bis akita dapatkan dengan mudah di lingkungan sekitar.` (Karya PEMANDU) | Typo pemisahan kata `bis akita`. Seharusnya: `bisa kita`. |
| 9 | **07 Karya Inovasi** | `...Geraling Mediva dapet memanfaatkannya...` (Karya Geraling Mediva) | Kata tidak baku `dapet`. Seharusnya ragam formal: `dapat`. |
| 10 | **07 Karya Inovasi** | `GEBYAR BUNDA (BUSINESS DAY) INTERPRENEUR CILIK` | Typo kata `INTERPRENEUR`. Seharusnya: `ENTREPRENEUR`. |
| 11 | **07 Karya Inovasi** | `COOCKING CLASS "TAHU CRISPY"` | Typo kata `COOCKING` (huruf 'c' ganda di awal). Seharusnya: `COOKING CLASS`. |
| 12 | **11 Bukti Implementasi**| `MEMPERLEH BINTANG DAN PIAGAM PENGHARGAAN` (Misi 5) | Typo kata `MEMPERLEH`. Seharusnya: `MEMPEROLEH`. |

---

## 6. Petunjuk untuk Halaman 09 dan Halaman 10 (Halaman Kosong)

Pada situs Google Sites yang sedang daring, halaman **09 Partisipasi Komunitas IntraSekolah** dan halaman **10 Partisipasi Komunitas AntarSekolah** masih kosong (belum diisi kegiatan). 

Dalam template baru ini, telah dibuatkan blok kartu terstruktur yang **siap diisi**:
- File blok: `09-komunitas-intrasekolah-blok1.html` dan `10-komunitas-antarsekolah-blok1.html`.
- Berisi 2 kartu contoh dengan penanda `[ISI NAMA KEGIATAN]`, `[TANGGAL]`, `[TEMPAT]`, `[URAIAN PRAKTIK BAIK]`, serta tombol `[Link Dokumentasi]` dan `[Link Sertifikat/Notula]`.
- Bu Ferry atau tim hanya perlu membuka file `.html` tersebut dengan Notepad, mengganti teks di dalam tanda kurung siku `[...]` sesuai kegiatan nyata yang pernah dilaksanakan di sekolah, lalu menempelkannya ke Google Sites.

---

## 7. Hasil Uji Responsif & Tampilan Browser

Seluruh 11 halaman pratinjau telah diuji menggunakan mesin peramban otomatis (Playwright Chromium) pada dua resolusi standar:
1. **Desktop (1280 × 900 px):**
   - Nilai horizontal overflow: `false` (0 piksel meluap).
   - Seluruh grid tertata rapi dalam 2 atau 3 kolom dengan proporsi seimbang.
2. **Mobile Smartphone (390 × 844 px):**
   - Nilai horizontal overflow: `false` (tidak ada geser/scroll mendatar).
   - Seluruh kolom otomatis bertumpuk vertikal (*single column stack*).
   - Ukuran font judul menggunakan teknik `clamp()` sehingga proporsional dan tidak terpotong.
   - Tombol-tombol CTA memiliki ruang ketuk (*touch target*) yang nyaman dan mudah ditekan di layar sentuh.

---

*Dokumen ini disusun secara otomatis oleh AI Assistant untuk mendampingi karya portofolio lomba Ibu Ferry Indra Arsanti, S.Pd.*
