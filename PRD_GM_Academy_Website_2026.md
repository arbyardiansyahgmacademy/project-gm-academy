# PRODUCT REQUIREMENTS DOCUMENT (PRD)

# Website GM Academy --- Digital Marketer Agency & Program Magang

**Versi:** 1.0\
**Tanggal:** Oktober 2026\
**Bahasa website:** Bahasa Indonesia\
**Referensi visual:** [Strive ---
BootstrapMade](https://bootstrapmade.com/demo/Strive/)\
**Pendekatan:** Website perusahaan multi-page, bukan landing page satu
halaman.

------------------------------------------------------------------------

## 1. Ringkasan Proyek

GM Academy adalah perusahaan dengan dua fokus utama: layanan digital
marketing agency dan program magang untuk siswa SMK serta mahasiswa.
Website harus menjelaskan identitas perusahaan, layanan, program magang,
portfolio, artikel edukasi, FAQ, dan informasi kontak melalui
halaman-halaman terpisah.

Template Strive digunakan sebagai referensi visual untuk gaya corporate
modern, bersih, profesional, dan responsif. Implementasi harus tetap
mengikuti lisensi dan ketentuan penggunaan template BootstrapMade.

### Positioning

**GM Academy --- Digital Marketer Agency & Internship Center**

Pesan utama: **Mengembangkan Talenta Digital, Membangun Strategi
Digital.**

Deskripsi: GM Academy mengembangkan layanan digital dan pengalaman
belajar berbasis proyek untuk bisnis, siswa SMK, serta mahasiswa. Klaim
tentang hasil, klien, fasilitas, sertifikasi, atau keberhasilan tidak
boleh ditambahkan tanpa bukti yang sah.

## 2. Tujuan Website

1.  Membangun identitas perusahaan yang profesional.
2.  Menjelaskan layanan digital marketing.
3.  Menarik calon peserta program magang SMK dan mahasiswa.
4.  Menjelaskan bidang, kompetensi, dan alur pendaftaran.
5.  Menampilkan portfolio atau project yang benar-benar boleh
    dipublikasikan.
6.  Menghasilkan pertanyaan dan pendaftaran melalui formulir atau
    WhatsApp.
7.  Membangun aset konten organik melalui SEO, AEO, dan GEO.
8.  Menjaga aksesibilitas, keamanan, dan performa pada mobile maupun
    desktop.

## 3. Target Pengguna

### Peserta magang

-   Siswa SMK yang membutuhkan PKL/Prakerin/magang.
-   Mahasiswa yang membutuhkan pengalaman internship.
-   Peserta yang ingin mengembangkan skill digital dan portfolio.

### Jurusan atau program studi relevan

-   Informatika
-   Manajemen
-   Rekayasa Perangkat Lunak (RPL)
-   Ekonomi Bisnis
-   Sistem Informasi
-   TK (konfirmasi kepanjangan resmi sebelum publikasi)
-   Bisnis Digital
-   Multimedia
-   Digital
-   Desain Komunikasi Visual (DKV)
-   Marketing
-   Program studi lain yang relevan

### Calon klien

-   UMKM
-   Startup
-   Perusahaan
-   Pemilik brand
-   Institusi pendidikan
-   Organisasi yang membutuhkan layanan digital

## 4. Prinsip Produk

-   Setiap halaman utama mempunyai URL dan konten sendiri.
-   Navigasi berpindah ke halaman berbeda, bukan hanya menggulir ke
    bagian dalam homepage.
-   Bahasa antarmuka dan konten menggunakan Bahasa Indonesia.
-   Konten harus akurat, bermanfaat, mudah dipindai, dan tidak berisi
    klaim yang belum diverifikasi.
-   Mobile-first, aksesibel, aman, dan ringan.
-   SEO/AEO/GEO diterapkan melalui kualitas konten, struktur,
    aksesibilitas crawler, dan informasi entitas yang jelas; bukan
    dengan trik manipulatif.
-   Target PageSpeed di atas 90 adalah sasaran pengembangan dan harus
    diverifikasi melalui pengujian setelah deployment, bukan jaminan
    skor permanen.

## 5. Struktur Navigasi

``` text
Beranda
Tentang Kami
Layanan
  ├── Digital Marketing
  ├── SEO
  ├── Social Media Marketing
  ├── Website Development
  ├── Content Marketing
  └── Digital Advertising
Program Magang
  ├── Magang SMK
  ├── Internship Mahasiswa
  ├── Posisi Magang
  ├── Kompetensi yang Dipelajari
  └── Alur Pendaftaran
Portfolio
Artikel
FAQ
Karier
Kontak
[Daftar Magang]
```

## 6. Rekomendasi Struktur File dan URL

``` text
gm-academy/
├── index.html
├── tentang-kami/index.html
├── layanan/index.html
├── layanan/digital-marketing/index.html
├── layanan/seo/index.html
├── layanan/social-media/index.html
├── layanan/website-development/index.html
├── layanan/content-marketing/index.html
├── layanan/digital-advertising/index.html
├── program-magang/index.html
├── program-magang/smk/index.html
├── program-magang/mahasiswa/index.html
├── program-magang/posisi/index.html
├── program-magang/kompetensi/index.html
├── program-magang/alur-pendaftaran/index.html
├── portfolio/index.html
├── portfolio/[slug]/index.html
├── artikel/index.html
├── artikel/[slug]/index.html
├── faq/index.html
├── karier/index.html
├── kontak/index.html
├── assets/css/
├── assets/js/
├── assets/img/
├── assets/fonts/
├── robots.txt
├── sitemap.xml
├── 404.html
└── manifest.webmanifest (opsional)
```

Jika hosting tidak mendukung direktori URL bersih, konfigurasikan
routing/redirect dengan benar. Hindari URL parameter yang tidak perlu.
Gunakan domain production final yang sudah dikonfirmasi untuk canonical
dan sitemap.

------------------------------------------------------------------------

# 7. Spesifikasi Setiap Halaman

## 7.1 Beranda

**URL:** `/`\
**SEO title:**
`GM Academy | Digital Marketing Agency & Program Magang Malang`\
**Meta description:**
`Kenali GM Academy, digital marketer agency dengan program magang untuk siswa SMK dan mahasiswa di Malang serta layanan pengembangan digital.`\
**H1:** `Digital Marketing Agency & Program Magang di Malang`

### Isi dan urutan section

1.  **Hero**
    -   Eyebrow: GM ACADEMY
    -   Headline: "Mengembangkan Talenta Digital, Membangun Strategi
        Digital."
    -   Deskripsi singkat dua fokus: layanan digital dan pengalaman
        belajar berbasis proyek.
    -   CTA: "Lihat Layanan" dan "Program Magang".
2.  **Tentang GM Academy**
    -   Ringkasan perusahaan dan tautan ke halaman Tentang Kami.
3.  **Dua fokus utama**
    -   Digital Marketing Agency.
    -   Program Magang.
4.  **Ringkasan layanan**
    -   SEO, website, social media, content marketing, digital
        advertising.
5.  **Program magang**
    -   Ringkasan untuk siswa SMK dan mahasiswa.
6.  **Bidang magang**
    -   Digital marketing, SEO, content, social media, website, desain;
        tampilkan hanya bidang yang benar-benar tersedia.
7.  **Proses belajar berbasis proyek**
    -   Belajar → Praktik → Proyek → Evaluasi → Dokumentasi portfolio.
8.  **Portfolio pilihan**
    -   Hanya project yang benar-benar ada dan boleh dipublikasikan.
9.  **Artikel terbaru**
    -   Tampilkan 3--6 artikel.
10. **CTA akhir**
    -   Daftar Magang / Hubungi GM Academy.
11. **Footer global**.

Homepage berfungsi sebagai pintu masuk dan ringkasan. Isi detail setiap
topik berada di halaman terpisah.

## 7.2 Tentang Kami

**URL:** `/tentang-kami/`\
**Title:**
`Tentang GM Academy | Digital Marketing dan Pengembangan Talenta`\
**H1:** `Tentang GM Academy`

Isi: - Profil dan latar belakang perusahaan. - Dua fokus: layanan
digital dan pengembangan talenta. - Pendekatan kerja dan pembelajaran. -
Nilai kerja: pembelajaran, kreativitas, tanggung jawab, kolaborasi,
adaptasi, peningkatan berkelanjutan. - Foto atau dokumentasi asli bila
tersedia. - CTA menuju layanan dan program magang.

Jangan mengarang tahun berdiri, jumlah klien, jumlah peserta, alamat,
atau pencapaian.

## 7.3 Indeks Layanan

**URL:** `/layanan/`\
**Title:** `Layanan Digital Marketing GM Academy`\
**H1:** `Layanan Digital Marketing`

Isi: - Penjelasan umum layanan. - Kartu layanan yang mengarah ke halaman
detail. - Cara kerja umum: memahami kebutuhan → menyusun rencana →
implementasi → evaluasi. - CTA konsultasi.

## 7.4 Digital Marketing

**URL:** `/layanan/digital-marketing/`\
**Title:** `Layanan Digital Marketing | GM Academy`\
**H1:** `Layanan Digital Marketing`

Isi: - Jawaban langsung tentang digital marketing. - Kebutuhan bisnis
yang dapat dibantu. - Ruang lingkup strategi yang tersedia. - Proses
kerja dan output. - FAQ relevan. - CTA konsultasi.

Jawaban pembuka yang disarankan: "Digital marketing adalah pemasaran
melalui kanal digital untuk menjangkau dan berinteraksi dengan audiens.
Ruang lingkup strategi dapat mencakup website, SEO, konten, media
sosial, dan iklan digital sesuai kebutuhan serta tujuan bisnis."

## 7.5 SEO

**URL:** `/layanan/seo/`\
**Title:** `Layanan SEO untuk Website Bisnis | GM Academy`\
**H1:** `Layanan SEO`

Isi: - Pengertian SEO. - SEO teknis. - SEO on-page. - Riset kata kunci
dan search intent. - Strategi konten. - Internal linking. - SEO lokal
jika sesuai. - Pengukuran dan pelaporan. - FAQ: apa itu SEO, berapa lama
prosesnya, apa yang dianalisis, dan apakah SEO hanya soal kata kunci.

Hindari menjanjikan peringkat tertentu atau hasil instan.

## 7.6 Social Media Marketing

**URL:** `/layanan/social-media/`\
**Title:** `Layanan Social Media Marketing | GM Academy`\
**H1:** `Social Media Marketing`

Isi: - Perencanaan strategi. - Kalender konten. - Copywriting dan konsep
visual. - Publikasi dan distribusi. - Evaluasi metrik. - Alur kerja dan
FAQ. - CTA konsultasi.

## 7.7 Website Development

**URL:** `/layanan/website-development/`\
**Title:** `Layanan Website Development | GM Academy`\
**H1:** `Website Development`

Isi: - Company profile. - Website bisnis. - Landing page bila
dibutuhkan. - Responsive design. - Struktur konten dan navigasi. - Dasar
SEO teknis. - Optimasi performa. - Tahapan pengembangan dan FAQ.

Jelaskan bahwa website mencakup struktur, kegunaan, aksesibilitas,
keamanan, dan performa, bukan hanya tampilan.

## 7.8 Content Marketing

**URL:** `/layanan/content-marketing/`\
**Title:** `Layanan Content Marketing | GM Academy`\
**H1:** `Content Marketing`

Isi: - Strategi konten. - Riset audiens dan search intent. - Kalender
editorial. - Artikel edukasi dan komersial. - Distribusi konten. -
Evaluasi dan pembaruan konten.

## 7.9 Digital Advertising

**URL:** `/layanan/digital-advertising/`\
**Title:** `Layanan Digital Advertising | GM Academy`\
**H1:** `Digital Advertising`

Isi: - Perencanaan kampanye. - Riset audiens. - Perencanaan materi
iklan. - Landing page. - Pelacakan konversi. - Evaluasi kampanye. -
Penjelasan bahwa hasil bergantung pada banyak faktor.

## 7.10 Program Magang

**URL:** `/program-magang/`\
**Title:** `Program Magang SMK dan Mahasiswa di Malang | GM Academy`\
**H1:** `Program Magang SMK & Mahasiswa di Malang`

Hero: - Headline: "Bangun Pengalaman. Kembangkan Skill. Buat
Portfolio." - Deskripsi program secara faktual. - CTA: "Lihat Bidang
Magang" dan "Lihat Alur Pendaftaran".

Isi: - Gambaran program. - Untuk siapa program ditujukan. - Penempatan
internship di Kota Malang, sesuai ketersediaan dan ketentuan aktual. -
Bidang atau posisi yang benar-benar tersedia. - Kompetensi yang dapat
dipelajari. - Contoh aktivitas hanya jika memang dilakukan. - Alur
pendaftaran. - FAQ magang. - Formulir atau kontak resmi.

## 7.11 Magang SMK

**URL:** `/program-magang/smk/`\
**Title:** `Program Magang SMK di Malang | GM Academy`\
**H1:** `Program Magang SMK di Malang`

Isi: - Sasaran program. - Relevansi untuk PKL/Prakerin. - Bidang yang
sesuai. - Aktivitas, proyek, pendampingan, dan evaluasi sesuai
pelaksanaan nyata. - Dokumen atau persyaratan yang sudah dikonfirmasi. -
Alur pendaftaran dan FAQ.

## 7.12 Internship Mahasiswa

**URL:** `/program-magang/mahasiswa/`\
**Title:** `Internship Mahasiswa di Malang | GM Academy`\
**H1:** `Internship Mahasiswa di Malang`

Isi: - Sasaran peserta. - Relevansi dengan program studi. - Pengalaman
berbasis proyek. - Skill teknis dan profesional. - Portfolio dan
dokumentasi. - Periode, persyaratan, dan proses seleksi berdasarkan
kebijakan aktual.

## 7.13 Posisi Magang

**URL:** `/program-magang/posisi/`\
**Title:** `Posisi Magang di GM Academy | Bidang Digital`\
**H1:** `Posisi Magang di GM Academy`

Kartu posisi yang dapat dipublikasikan jika tersedia: - Digital
Marketing Intern. - SEO Intern. - Content Marketing Intern. - Social
Media Intern. - Web Development Intern. - Graphic Design Intern.

Setiap kartu memuat deskripsi, kompetensi terkait, tugas yang
benar-benar relevan, persyaratan, status ketersediaan, dan CTA. Jangan
menyebut posisi sebagai "dibuka" jika belum dikonfirmasi.

## 7.14 Kompetensi yang Dipelajari

**URL:** `/program-magang/kompetensi/`\
**Title:** `Kompetensi Program Magang Digital | GM Academy`\
**H1:** `Kompetensi yang Dipelajari Selama Magang`

Kelompok: - Digital: SEO, website, analitik, digital marketing. -
Kreatif: desain, konten, copywriting. - Bisnis: pemasaran, komunikasi,
pemahaman kebutuhan. - Profesional: kerja tim, manajemen waktu, tanggung
jawab, presentasi, pemecahan masalah.

Bedakan kompetensi yang tersedia dari materi yang masih direncanakan.

## 7.15 Alur Pendaftaran

**URL:** `/program-magang/alur-pendaftaran/`\
**Title:** `Alur Pendaftaran Magang | GM Academy`\
**H1:** `Alur Pendaftaran Program Magang`

Tahapan yang dapat disesuaikan: 1. Kenali program. 2. Pilih bidang yang
relevan. 3. Isi formulir atau hubungi kontak resmi. 4. Tunggu konfirmasi
dan proses seleksi bila berlaku. 5. Konfirmasi penempatan dan jadwal. 6.
Mulai program setelah persyaratan disepakati.

Cantumkan dokumen, tenggat, durasi, dan proses seleksi hanya setelah
dikonfirmasi perusahaan.

## 7.16 Portfolio

**URL:** `/portfolio/`\
**Title:** `Portfolio dan Project GM Academy`\
**H1:** `Portfolio & Project GM Academy`

Kategori: - Semua. - Website. - SEO. - Digital Marketing. - Social
Media. - Konten. - Project peserta.

Setiap kartu menuju halaman detail. Publikasikan hanya project yang
benar-benar ada dan memiliki izin untuk ditampilkan.

## 7.17 Detail Portfolio

**URL:** `/portfolio/[slug]/`\
**Title:** `[Nama Project] | Portfolio GM Academy`\
**H1:** Nama project.

Struktur: - Ringkasan. - Latar belakang. - Tujuan. - Tantangan. -
Strategi atau pendekatan. - Proses pengerjaan. - Output. - Visual. -
Pembelajaran atau insight. - Project terkait.

Jangan mengarang klien, metrik, hasil bisnis, atau testimonial.

## 7.18 Indeks Artikel

**URL:** `/artikel/`\
**Title:** `Artikel Digital Marketing, SEO, dan Magang | GM Academy`\
**H1:** `Artikel dan Wawasan Digital`

Kategori: - Digital Marketing. - SEO. - Website. - Social Media. -
Content Marketing. - Karier Digital. - Program Magang. - Bisnis
Digital. - Portfolio. - Tips Siswa SMK. - Tips Mahasiswa.

Fitur: - Kartu artikel. - Kategori. - Pencarian sederhana bila
diperlukan. - Pagination yang crawlable. - Tautan ke artikel terkait.

## 7.19 Detail Artikel

**URL:** `/artikel/[slug]/`\
**Title:** `[Judul Artikel] | GM Academy`\
**H1:** Judul artikel.

Struktur: - Breadcrumb. - Kategori. - Judul. - Penulis yang
terverifikasi. - Tanggal publikasi dan pembaruan yang akurat. - Jawaban
ringkas untuk pertanyaan utama. - Daftar isi untuk artikel panjang. -
Isi artikel dengan heading terstruktur. - Contoh atau pengalaman nyata
jika tersedia. - Referensi jika relevan. - Kesimpulan. - Artikel
terkait. - CTA kontekstual. - Profil penulis.

Konten harus orisinal, bermanfaat, akurat, dan dibuat untuk membantu
pembaca. Jangan menerbitkan banyak halaman tipis hanya untuk mengejar
kata kunci atau visibilitas AI.

## 7.20 FAQ

**URL:** `/faq/`\
**Title:** `FAQ GM Academy | Program Magang dan Layanan Digital`\
**H1:** `Pertanyaan yang Sering Ditanyakan`

Kategori: - Tentang GM Academy. - Program Magang. - Magang SMK. -
Internship Mahasiswa. - Bidang Magang. - Pendaftaran. - Layanan Digital
Marketing. - Website dan SEO.

Jawaban harus terlihat pada halaman dan menjawab pertanyaan secara
langsung. FAQ berguna untuk pengguna, tetapi FAQ structured data tidak
menjamin hasil kaya di Google.

## 7.21 Karier

**URL:** `/karier/`\
**Title:** `Karier di GM Academy`\
**H1:** `Karier di GM Academy`

Isi: - Profil lingkungan kerja berdasarkan fakta. - Daftar posisi yang
benar-benar tersedia. - Persyaratan. - Cara melamar. - Kontak.

Jika tidak ada lowongan aktif, tulis bahwa belum ada lowongan yang
dipublikasikan.

## 7.22 Kontak

**URL:** `/kontak/`\
**Title:** `Kontak GM Academy | Malang`\
**H1:** `Hubungi GM Academy`

Tampilkan hanya informasi resmi yang telah dikonfirmasi: - Nama
perusahaan. - Email. - WhatsApp. - Alamat. - Jam operasional bila
benar-benar tersedia. - Lokasi operasional.

Formulir: - Nama lengkap. - Email. - Nomor WhatsApp. - Kategori
pertanyaan. - Pesan. - Persetujuan privasi bila data pribadi
dikumpulkan.

Kategori: - Program Magang. - Kerja Sama Sekolah. - Internship
Mahasiswa. - Digital Marketing. - Website. - SEO. - Social Media. -
Lainnya.

Sediakan validasi, pesan sukses/gagal, perlindungan spam, dan penjelasan
penggunaan data.

## 7.23 Halaman 404

**URL:** `/404.html`\
**H1:** `Halaman Tidak Ditemukan`

Deskripsi singkat dan tautan ke Beranda, Program Magang, Layanan, dan
Kontak. Pastikan halaman yang benar-benar tidak ditemukan mengembalikan
status HTTP 404.

------------------------------------------------------------------------

# 8. Komponen Global dan Design System

## Komponen global

-   Navbar desktop dan mobile.
-   Dropdown navigasi.
-   Breadcrumb.
-   Footer.
-   Tombol utama dan sekunder.
-   Heading section.
-   Kartu layanan.
-   Kartu program magang.
-   Kartu portfolio.
-   Kartu artikel.
-   Accordion FAQ.
-   Formulir kontak dan pendaftaran.
-   CTA kontekstual.

## Arahan visual

-   Gaya corporate modern, bersih, profesional, dan mudah dibaca.
-   Gunakan white space yang cukup.
-   Hierarki heading jelas.
-   Kartu dengan jarak konsisten.
-   Animasi seperlunya dan tidak mengganggu aksesibilitas.
-   Warna akhir mengikuti identitas merek GM Academy.
-   Pastikan kontras teks dan latar memadai.
-   Jangan mengubah seluruh website menjadi satu halaman panjang.

## Navigasi

Setiap tautan navigasi harus menuju URL halaman yang sesuai. Anchor
seperti `#layanan` hanya boleh dipakai untuk navigasi dalam halaman yang
memang panjang, bukan menggantikan halaman utama yang terpisah.

------------------------------------------------------------------------

# 9. Strategi SEO 2026

## 9.1 SEO teknis

-   HTTPS.
-   URL bersih dan konsisten.
-   Canonical per halaman.
-   XML sitemap.
-   Robots.txt yang benar.
-   Internal linking berbasis konteks.
-   Breadcrumb.
-   HTML semantik.
-   Mobile responsive.
-   Halaman 404.
-   Redirect 301 untuk URL yang berubah.
-   Open Graph.
-   Metadata unik.
-   Gambar teroptimasi.
-   Pastikan konten penting tersedia dalam HTML yang dapat dirayapi.

## 9.2 On-page SEO

Setiap halaman indeks utama harus mempunyai: - Title unik. - Meta
description yang relevan. - Satu H1 utama yang jelas. - Heading H2/H3
terstruktur. - Search intent yang spesifik. - Konten unik dan
bermanfaat. - Internal link yang relevan. - Alt text deskriptif untuk
gambar informatif. - Canonical yang benar. - Breadcrumb. - Structured
data yang sesuai jika relevan.

Jangan menjejalkan kata kunci atau membuat halaman terpisah yang isinya
hampir sama hanya untuk variasi keyword.

## 9.3 AEO --- Answer Engine Optimization

-   Jawab pertanyaan utama secara langsung pada bagian awal halaman.
-   Gunakan definisi yang jelas dan bahasa Indonesia yang natural.
-   Gunakan heading berbentuk pertanyaan jika sesuai kebutuhan pengguna.
-   Tambahkan contoh, langkah, tabel, atau daftar jika membantu.
-   Pastikan jawaban lengkap dan tidak menyesatkan.
-   Pertahankan sumber, tanggal, dan atribusi jika informasi
    membutuhkannya.

Bagian "jawaban langsung" adalah pola editorial, bukan jaminan kutipan
oleh mesin jawaban.

## 9.4 GEO --- Generative Engine Optimization

-   Jelaskan entitas GM Academy dengan konsisten.
-   Gunakan nama, layanan, program, dan lokasi secara faktual.
-   Publikasikan dokumentasi dan pengalaman nyata jika tersedia.
-   Buat halaman layanan dan program yang jelas.
-   Pastikan konten dapat diakses crawler dan saling terhubung.
-   Hindari klaim yang tidak dapat diverifikasi.
-   Pantau kinerja organik dan perubahan pencarian melalui alat analitik
    yang tersedia.

Jangan menganggap file `llms.txt`, pengulangan kata kunci, atau schema
khusus sebagai syarat wajib agar tampil di fitur AI Search. SEO
fundamental dan konten berkualitas tetap menjadi dasar.

## 9.5 Local SEO

Topik yang dapat ditargetkan jika sesuai operasi nyata: - Program Magang
Malang. - Magang SMK Malang. - Internship Mahasiswa Malang. - Magang
Bisnis Digital Malang. - Digital Marketing Malang. - Digital Marketing
Agency Malang.

Jangan membuat halaman kota atau menyatakan alamat fisik yang tidak
benar. Konsistenkan informasi website dengan profil bisnis resmi bila
tersedia.

## 9.6 Struktur data terstruktur

Gunakan JSON-LD hanya ketika sesuai dengan isi yang terlihat: -
`Organization` untuk informasi organisasi. - `WebSite` untuk informasi
situs. - `WebPage` atau tipe halaman yang relevan. - `AboutPage` untuk
halaman tentang. - `ContactPage` untuk halaman kontak. -
`BreadcrumbList` untuk breadcrumb. - `Article` atau `BlogPosting` untuk
artikel. - `Service` untuk detail layanan jika sesuai.

Jangan menambahkan properti yang tidak benar. Structured data tidak
menjamin rich result. Jangan mengandalkan `FAQPage` untuk memperoleh FAQ
rich result.

## 9.7 E-E-A-T dan kepercayaan

-   Tampilkan profil perusahaan yang akurat.
-   Tampilkan penulis yang nyata dan kompeten jika memungkinkan.
-   Gunakan contoh kerja asli dengan izin.
-   Cantumkan tanggal pembaruan hanya saat konten benar-benar
    diperbarui.
-   Berikan sumber untuk klaim yang memerlukan bukti.
-   Jangan mengarang testimoni, klien, penghargaan, sertifikasi,
    statistik, atau hasil.

------------------------------------------------------------------------

# 10. Strategi Konten dan Internal Linking

## Cluster program magang

Pillar: Program Magang SMK dan Mahasiswa di Malang.

Artikel pendukung: - Cara mempersiapkan diri sebelum magang. - Cara
membuat CV untuk magang. - Cara membuat portfolio digital. - Skill yang
dibutuhkan untuk magang digital. - Perbedaan PKL dan internship. - Tips
beradaptasi dengan lingkungan kerja. - Cara memilih bidang magang.

## Cluster digital marketing

Pillar: Digital Marketing.

Artikel pendukung: - Apa itu digital marketing. - Strategi konten untuk
bisnis. - Social media marketing. - Dasar digital advertising. -
Analitik pemasaran digital.

## Cluster SEO

Pillar: SEO.

Artikel pendukung: - SEO on-page. - Riset kata kunci. - Search intent. -
Technical SEO. - Local SEO. - Internal linking. - Core Web Vitals.

## Cluster karier digital

Pillar: Karier di Dunia Digital.

Artikel pendukung: - Membuat CV digital. - Portfolio website. - Personal
branding. - Persiapan interview magang. - Skill komunikasi dan kerja
tim.

## Aturan internal link

-   Artikel mengarah ke halaman layanan/program yang relevan.
-   Halaman pillar mengarah ke artikel pendukung.
-   Detail portfolio mengarah ke project terkait.
-   Gunakan anchor text yang menjelaskan tujuan tautan.
-   Hindari tautan berlebihan yang tidak membantu pengguna.

------------------------------------------------------------------------

# 11. Performance dan PageSpeed

## Target proyek

-   PageSpeed Insights Mobile: skor target di atas 90.
-   PageSpeed Insights Desktop: skor target di atas 90.
-   Accessibility: target di atas 90.
-   Best Practices: target di atas 90.
-   SEO audit: target di atas 90.

Skor harus diuji pada halaman representatif setelah deployment. Skor
bukan jaminan permanen karena dipengaruhi kondisi pengujian, perangkat,
jaringan, server, dan resource pihak ketiga. Target skor tidak
menggantikan pengukuran pengalaman pengguna nyata.

## Core Web Vitals

Target "baik": - **LCP:** 2,5 detik atau kurang. - **INP:** 200
milidetik atau kurang. - **CLS:** 0,1 atau kurang.

Nilai tersebut dinilai pada persentil ke-75 pengalaman pengguna,
dipisahkan untuk mobile dan desktop bila data tersedia.

## HTML dan CSS

-   Gunakan HTML semantik.
-   Hindari DOM terlalu besar dan struktur bersarang yang tidak
    diperlukan.
-   Muat hanya CSS yang diperlukan.
-   Minifikasi file production.
-   Hindari framework tambahan yang tidak diperlukan.
-   Jangan menambahkan animasi berat sebagai dekorasi.

## JavaScript

-   Gunakan JavaScript seperlunya.
-   Gunakan `defer` untuk script non-kritis.
-   Hindari library besar jika fitur sederhana dapat dibuat dengan kode
    kecil.
-   Hindari script pihak ketiga yang tidak memberikan nilai nyata.
-   Pastikan menu, form, dan interaksi tetap berfungsi.

## Gambar

-   Gunakan WebP/AVIF bila sesuai.
-   Kompres gambar dan sediakan ukuran responsif.
-   Tentukan atribut `width` dan `height`.
-   Terapkan `loading="lazy"` pada gambar di luar viewport awal.
-   Jangan lazy-load gambar utama yang menjadi LCP.
-   Gunakan `fetchpriority="high"` hanya untuk gambar LCP yang
    benar-benar perlu diprioritaskan.
-   Sediakan alt text yang akurat; gambar dekoratif memakai alt kosong.

## Font

-   Batasi keluarga dan variasi font.
-   Gunakan subset font jika memungkinkan.
-   Pertimbangkan font lokal/self-hosted.
-   Gunakan `font-display: swap`.
-   Preload hanya font kritis.

## LCP

-   Hindari video latar yang berat.
-   Optimalkan gambar hero.
-   Kurangi resource render-blocking.
-   Optimalkan waktu respons server.
-   Preload resource hanya bila benar-benar kritis.

## INP

-   Kurangi JavaScript yang memblokir main thread.
-   Pecah tugas panjang.
-   Hindari manipulasi DOM besar saat interaksi.
-   Jaga event handler tetap ringan.

## CLS

-   Tetapkan dimensi gambar, video, iframe, dan embed.
-   Sisakan ruang untuk konten dinamis.
-   Hindari menyisipkan banner di atas konten setelah halaman dimuat.
-   Perhatikan pergantian font dan ukuran komponen.

## Pengujian

-   Jalankan PageSpeed Insights pada homepage dan template utama.
-   Uji halaman layanan, program magang, artikel, dan kontak.
-   Gunakan Lighthouse untuk audit lokal.
-   Periksa data lapangan Core Web Vitals jika tersedia.
-   Catat skor sebelum dan sesudah optimasi.
-   Perbaiki masalah terbesar terlebih dahulu.
-   Ulangi tes setelah perubahan dan setelah deployment production.

------------------------------------------------------------------------

# 12. Responsif dan Aksesibilitas

## Responsive

-   Mobile-first.
-   Uji ponsel kecil, ponsel besar, tablet, laptop, dan desktop.
-   Hindari horizontal overflow.
-   Pastikan menu mobile dapat digunakan dengan keyboard dan sentuhan.
-   Pastikan CTA mudah ditemukan.
-   Pastikan form nyaman diisi pada layar kecil.
-   Gunakan gambar responsif dan teks yang mudah dibaca.

## Accessibility

-   Heading hierarchy logis.
-   Label eksplisit pada form.
-   Navigasi keyboard.
-   Focus state yang terlihat.
-   Kontras warna memadai.
-   Alt text untuk gambar informatif.
-   Tombol dan tautan memiliki nama yang jelas.
-   Gunakan ARIA hanya ketika semantik HTML bawaan tidak cukup.
-   Hormati preferensi `prefers-reduced-motion`.

------------------------------------------------------------------------

# 13. Formulir dan Konversi

## Formulir magang

-   Nama lengkap.
-   Email.
-   Nomor WhatsApp.
-   Asal sekolah/kampus.
-   Jurusan/program studi.
-   Status: siswa SMK, mahasiswa, atau lainnya.
-   Bidang/posisi yang diminati.
-   Periode magang yang diinginkan.
-   Pesan tambahan.
-   Persetujuan pemrosesan data bila diperlukan.

## Alur magang

``` text
Pencarian / Artikel
  ↓
Halaman Program Magang
  ↓
Pilih SMK atau Mahasiswa
  ↓
Pilih Bidang
  ↓
Baca Alur Pendaftaran
  ↓
Formulir / WhatsApp
  ↓
Konfirmasi oleh GM Academy
```

## Alur calon klien

``` text
Pencarian / Artikel
  ↓
Halaman Layanan
  ↓
Detail Layanan
  ↓
Portfolio
  ↓
Kontak
  ↓
Formulir / WhatsApp
```

## Keamanan formulir

-   Validasi sisi klien dan server.
-   Sanitasi input.
-   Proteksi spam.
-   Jangan menaruh API key atau rahasia di frontend.
-   Terapkan perlindungan CSRF jika backend dan pola autentikasi
    memerlukannya.
-   Berikan status pengiriman berhasil/gagal.
-   Jelaskan tujuan pengumpulan data.

------------------------------------------------------------------------

# 14. Analitik

Jika analytics dipasang, pertimbangkan event: - `click_whatsapp` -
`click_apply_internship` - `submit_internship_form` -
`submit_contact_form` - `view_service` - `view_portfolio` -
`view_article`

Pasang analytics secara transparan dan sesuai ketentuan privasi yang
berlaku. Jangan mengumpulkan data pribadi yang tidak dibutuhkan.

------------------------------------------------------------------------

# 15. Keamanan dan SEO Pasca-Peluncuran

Checklist: - HTTPS aktif. - Tidak ada secret/API key di frontend. -
Header keamanan dikonfigurasi sesuai hosting. - Formulir terlindungi. -
Sitemap berisi URL canonical yang ingin diindeks. - Robots.txt tidak
memblokir halaman penting atau resource yang diperlukan. - Search
Console terverifikasi. - Sitemap dikirim ke Search Console. - Analytics
dikonfigurasi bila digunakan. - Periksa status HTTP, canonical,
redirect, dan error crawl. - Pantau indeks, performa, dan Core Web
Vitals secara berkala.

Contoh `robots.txt` setelah domain dikonfirmasi:

``` text
User-agent: *
Allow: /

Sitemap: https://DOMAIN-RESMI/sitemap.xml
```

Ganti `DOMAIN-RESMI` dengan domain production. Jangan deploy placeholder
tersebut.

------------------------------------------------------------------------

# 16. Kriteria Penerimaan (Acceptance Criteria)

## Struktur dan navigasi

-   [ ] Website terdiri dari halaman terpisah.
-   [ ] Setiap item menu mengarah ke halaman yang benar.
-   [ ] Halaman tidak hanya berupa anchor pada homepage.
-   [ ] Breadcrumb berfungsi.
-   [ ] URL konsisten dan tidak menghasilkan duplikat yang tidak perlu.
-   [ ] Halaman 404 mengembalikan status yang sesuai.

## Konten

-   [ ] Seluruh antarmuka menggunakan Bahasa Indonesia.
-   [ ] Setiap halaman memiliki tujuan yang jelas.
-   [ ] Tidak ada teks placeholder pada production.
-   [ ] Informasi kontak dan program telah diverifikasi.
-   [ ] Tidak ada testimoni, klien, statistik, atau pencapaian fiktif.
-   [ ] Formulir menjelaskan field wajib dan hasil pengiriman.

## SEO/AEO/GEO

-   [ ] Title dan meta description unik.
-   [ ] H1 dan heading tersusun dengan benar.
-   [ ] Canonical benar.
-   [ ] Internal link relevan.
-   [ ] Sitemap dan robots.txt valid.
-   [ ] Schema valid dan sesuai konten terlihat.
-   [ ] Konten menjawab kebutuhan pengguna secara langsung.
-   [ ] Entitas dan lokasi dijelaskan secara faktual.
-   [ ] Tidak ada keyword stuffing atau halaman tipis massal.
-   [ ] Search Console dapat digunakan untuk pemantauan.

## Performance

-   [ ] Target skor PageSpeed \>90 diuji pada mobile.
-   [ ] Target skor PageSpeed \>90 diuji pada desktop.
-   [ ] LCP, INP, dan CLS dioptimasi.
-   [ ] Gambar terkompresi dan berdimensi.
-   [ ] Resource render-blocking dikurangi.
-   [ ] JavaScript dan CSS yang tidak diperlukan dihapus.
-   [ ] Tidak ada layout shift yang mengganggu.
-   [ ] Pengujian dilakukan setelah deployment.

## Responsive dan aksesibilitas

-   [ ] Tidak ada horizontal overflow.
-   [ ] Navbar mobile berfungsi.
-   [ ] Semua kontrol dapat diakses dengan keyboard.
-   [ ] Form mempunyai label.
-   [ ] Kontras dan focus state memadai.
-   [ ] Gambar mempunyai alt yang sesuai.

## Keamanan

-   [ ] HTTPS aktif.
-   [ ] Formulir memiliki validasi dan perlindungan spam.
-   [ ] Tidak ada rahasia di frontend.
-   [ ] Data pengguna ditangani secara wajar dan aman.

------------------------------------------------------------------------

# 17. Tahapan Pengembangan

## Tahap 1 --- Fondasi

-   Setup proyek dan Bootstrap.
-   Design system.
-   Navbar dan footer.
-   Homepage.
-   Tentang Kami.
-   Kontak.
-   Responsive foundation.

## Tahap 2 --- Layanan

-   Indeks layanan.
-   Digital Marketing.
-   SEO.
-   Social Media Marketing.
-   Website Development.
-   Content Marketing.
-   Digital Advertising.

## Tahap 3 --- Program Magang

-   Indeks Program Magang.
-   Magang SMK.
-   Internship Mahasiswa.
-   Posisi Magang.
-   Kompetensi.
-   Alur Pendaftaran.
-   Formulir.

## Tahap 4 --- Konten dan reputasi

-   Portfolio dan detail project.
-   Artikel dan template detail.
-   FAQ.
-   Karier.
-   Konten terkait yang sudah diverifikasi.

## Tahap 5 --- Quality assurance

-   Technical SEO.
-   Structured data.
-   Sitemap dan robots.
-   Accessibility audit.
-   Security review.
-   PageSpeed/Lighthouse.
-   Cross-browser testing.
-   Search Console dan analytics.
-   Validasi semua link dan form.

------------------------------------------------------------------------

# 18. Daftar Informasi yang Harus Dikonfirmasi Sebelum Produksi

-   Domain resmi GM Academy.
-   Logo dan pedoman warna.
-   Nama badan usaha resmi jika akan dicantumkan.
-   Deskripsi perusahaan yang disetujui.
-   Alamat operasional yang boleh dipublikasikan.
-   Email dan nomor WhatsApp resmi.
-   Jam operasional.
-   Apakah semua bidang layanan benar-benar tersedia.
-   Posisi magang yang sedang dibuka.
-   Periode, durasi, persyaratan, dan kapasitas program.
-   Apakah program berbayar atau tidak; jangan diasumsikan.
-   Proses seleksi dan dokumen pendaftaran.
-   Foto kegiatan dan izin publikasi.
-   Portfolio dan izin penyebutan klien.
-   Penulis dan penanggung jawab konten.
-   Kebijakan privasi dan pengelolaan data.
-   Hosting, framework final, dan metode deployment.

------------------------------------------------------------------------

# 19. Ringkasan Arsitektur Akhir

``` text
GM ACADEMY
├── Beranda
├── Tentang Kami
├── Layanan
│   ├── Digital Marketing
│   ├── SEO
│   ├── Social Media Marketing
│   ├── Website Development
│   ├── Content Marketing
│   └── Digital Advertising
├── Program Magang
│   ├── Magang SMK
│   ├── Internship Mahasiswa
│   ├── Posisi Magang
│   ├── Kompetensi
│   └── Alur Pendaftaran
├── Portfolio
│   └── Detail Project
├── Artikel
│   └── Detail Artikel
├── FAQ
├── Karier
├── Kontak
└── 404
```

## Prinsip akhir

Website GM Academy harus menjadi website perusahaan digital profesional
yang memiliki dua jalur utama: **layanan digital marketing** dan
**program magang**. Setiap halaman harus memiliki fungsi dan konten yang
jelas, menggunakan Bahasa Indonesia, terhubung melalui navigasi dan
internal linking, serta dibangun dengan SEO, AEO, GEO, aksesibilitas,
keamanan, dan performa sebagai persyaratan sejak awal.

Target PageSpeed di atas 90 harus diperlakukan sebagai target yang diuji
dan dioptimasi, bukan janji skor permanen. Keberhasilan implementasi
ditentukan melalui pengujian nyata pada halaman production, bukan hanya
berdasarkan rancangan.
