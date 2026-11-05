# PRODUCT REQUIREMENTS DOCUMENT (PRD)
# EXIT — Early Investment Take-over

| Informasi | Keterangan |
|---|---|
| Nama Produk | EXIT (Early Investment Take-over) |
| Jenis Produk | Web Application Prototype |
| Versi | 2.0 |
| Status | Draft for Team Discussion |
| Penyusun | System Analyst |
| Acuan | User Stories — Project EXIT (US-01–US-32) |

---

## 1. Product Overview

### 1.1 Deskripsi Produk

EXIT (Early Investment Take-over) merupakan konsep platform digital yang memfasilitasi investor untuk menawarkan pengalihan posisi investasi sebelum jatuh tempo kepada investor lain yang berminat mengambil alih posisi tersebut.

EXIT mempertemukan investor yang ingin menawarkan posisi investasinya (lender lama) dengan investor yang tertarik mengambil alih posisi investasi tersebut (lender baru).

Untuk mendukung proses tersebut, EXIT menyediakan fasilitas pengajuan posisi investasi, pemeriksaan awal kelayakan, eksplorasi posisi investasi, penyajian informasi dan risiko, rekomendasi matching, negosiasi, pengajuan permintaan take-over, perbandingan penawaran, serta pemantauan status dan riwayat aktivitas.

EXIT menggunakan sistem satu akun yang dapat mengakses fungsi penawaran maupun permintaan take-over. Dengan demikian, pengguna dapat bertindak sebagai investor penjual maupun investor pembeli sesuai kebutuhan dan aktivitasnya.

Pada tahap pengembangan ini, EXIT diwujudkan dalam bentuk prototype aplikasi berbasis web untuk menggambarkan mekanisme dan pengalaman penggunaan platform.

### 1.2 Product Vision

Menyediakan platform fasilitasi take-over posisi investasi yang membantu meningkatkan fleksibilitas investor melalui proses penawaran, pencarian, matching, negosiasi, dan pemantauan posisi investasi secara terstruktur dan informatif.

### 1.3 Product Scope

EXIT berfokus pada fasilitasi proses pengalihan posisi investasi dari investor lama kepada investor lain yang berminat, mulai dari penyampaian informasi posisi hingga proses pengajuan permintaan dan pemantauan perkembangannya.

EXIT bukan pemilik posisi investasi, bukan pihak yang menjamin pembelian posisi, dan bukan bursa atau exchange. Pengalihan posisi investasi tetap bergantung pada ketentuan instrumen dan platform asal.

---

## 2. Background and Problem Statement

### 2.1 Latar Belakang

Investasi dengan jangka waktu tertentu dapat membatasi fleksibilitas investor ketika membutuhkan likuiditas sebelum periode investasi berakhir. Dalam kondisi tersebut, investor yang ingin mengakhiri posisi investasinya lebih awal membutuhkan pihak lain yang bersedia mengambil alih posisi tersebut.

Di sisi lain, investor yang berminat mengambil alih posisi investasi membutuhkan informasi yang memadai untuk mempertimbangkan keputusan, seperti nilai posisi, sisa tenor, imbal hasil, riwayat pembayaran, risiko, dan ketentuan pengalihan.

Proses mempertemukan kedua pihak juga membutuhkan informasi yang terstruktur agar investor dapat menemukan posisi yang sesuai, menyampaikan permintaan, melakukan negosiasi, dan memantau perkembangan proses.

Berdasarkan kebutuhan tersebut, EXIT dikembangkan sebagai platform fasilitasi yang menghubungkan investor penjual dan investor pembeli melalui mekanisme penawaran dan permintaan take-over.

### 2.2 Problem Statement

Permasalahan yang menjadi dasar pengembangan EXIT meliputi:

1. Investor yang ingin mengakhiri posisi investasi sebelum jatuh tempo membutuhkan sarana untuk menawarkan posisi tersebut kepada investor lain.
2. Investor yang berminat mengambil alih posisi investasi membutuhkan akses terhadap informasi posisi yang jelas dan relevan.
3. Informasi mengenai nilai posisi, sisa tenor, imbal hasil, riwayat pembayaran, dan risiko perlu disajikan agar calon investor dapat melakukan pertimbangan.
4. Investor penjual dan pembeli membutuhkan mekanisme untuk saling menemukan, menyampaikan permintaan, dan melakukan negosiasi.
5. Pengguna membutuhkan informasi mengenai status pengajuan, aktivitas, serta perkembangan matching agar proses dapat dipantau.

EXIT dirancang untuk menjawab kebutuhan tersebut melalui satu platform yang menyediakan fasilitas penawaran, eksplorasi, matching, negosiasi, dan pemantauan take-over.

---

## 3. Product Goals and Objectives

Pengembangan EXIT memiliki tujuan sebagai berikut:

1. **Memfasilitasi penawaran posisi investasi:** Menyediakan sarana bagi investor untuk mengajukan posisi investasi yang ingin ditawarkan sebelum jatuh tempo.
2. **Mempermudah eksplorasi investasi:** Menyediakan daftar posisi investasi yang dapat dicari dan difilter oleh investor.
3. **Meningkatkan transparansi informasi:** Menyajikan informasi posisi investasi, termasuk nilai posisi, tenor, imbal hasil, riwayat pembayaran, risiko, dan ketentuan take-over.
4. **Memfasilitasi matching investor:** Menyediakan rekomendasi calon investor berdasarkan karakteristik posisi investasi dan kriteria yang ditentukan, termasuk profil risiko investor.
5. **Mendukung proses negosiasi:** Menyediakan fasilitas interaksi dan pengajuan permintaan take-over antara investor penjual dan pembeli.
6. **Mendukung perbandingan penawaran:** Menyediakan ringkasan perbandingan beberapa penawaran agar investor dapat mempertimbangkan pilihan yang tersedia.
7. **Menyediakan pemantauan proses:** Memungkinkan pengguna melihat status pengajuan, riwayat aktivitas, dan informasi ketika belum ditemukan kecocokan matching.

---

## 4. Target Users

### 4.1 Calon Pengguna

Calon pengguna merupakan individu yang mengakses landing page untuk memahami layanan EXIT sebelum melakukan registrasi.

Kebutuhan:
- Mengetahui informasi dasar dan manfaat EXIT.
- Memahami cara kerja dan mekanisme take-over.
- Mengetahui fitur utama yang tersedia.
- Memperoleh jawaban atas pertanyaan umum.

### 4.2 Investor Penjual (Lender Lama)

Investor yang memiliki posisi investasi dan ingin menawarkan posisi tersebut agar dapat diambil alih oleh investor lain.

Kebutuhan:
- Mengajukan posisi investasi.
- Mengisi informasi posisi investasi.
- Mengetahui hasil pemeriksaan awal kelayakan.
- Mengetahui kekurangan informasi pengajuan.
- Mengubah atau membatalkan pengajuan sesuai status.
- Memantau status penawaran dan perkembangan matching.
- Melakukan negosiasi dengan calon investor pembeli.

### 4.3 Investor Pembeli (Lender Baru)

Investor yang berminat menemukan dan mengambil alih posisi investasi yang ditawarkan investor lain.

Kebutuhan:
- Melihat posisi investasi yang tersedia.
- Mencari dan memfilter posisi investasi.
- Melihat detail informasi, risiko, dan ketentuan posisi.
- Melengkapi profil investor, termasuk profil risiko.
- Memperoleh rekomendasi matching.
- Membandingkan beberapa penawaran.
- Mengajukan permintaan take-over.
- Melakukan negosiasi dengan investor penjual.

### 4.4 Penggunaan Satu Akun

Satu akun pengguna dapat mengakses fungsi penawaran dan permintaan take-over. Pengguna tidak dibatasi untuk hanya menjadi investor penjual atau investor pembeli.

Perbedaan aktivitas ditentukan berdasarkan fitur yang digunakan:
- **Offer Your Position:** digunakan ketika pengguna bertindak sebagai investor penjual.
- **Permintaan Take-over:** digunakan ketika pengguna bertindak sebagai investor pembeli.

---

## 5. Product Features

### 5.1 Landing Page and Platform Information

Fitur ini menyediakan informasi pengenalan EXIT bagi calon pengguna sebelum masuk ke aplikasi.

Kebutuhan fitur:
- Menampilkan informasi dasar, tujuan, dan manfaat EXIT.
- Menampilkan penjelasan cara kerja dan alur take-over posisi investasi.
- Menampilkan fitur utama EXIT.
- Menyediakan Frequently Asked Questions (FAQ).
- Menampilkan identitas visual dan branding EXIT.

**Referensi User Story:** US-01, US-02, US-03, US-04, US-09.

### 5.2 User Registration and Authentication

Fitur ini menyediakan mekanisme pembuatan akun dan akses pengguna ke aplikasi EXIT.

Kebutuhan fitur:
- Menyediakan form registrasi pengguna baru.
- Menyediakan input nama, tanggal lahir, nomor telepon, dan email.
- Menyediakan proses OTP untuk registrasi.
- Melakukan validasi data registrasi.
- Menyediakan fitur login bagi pengguna terdaftar.
- Menampilkan informasi apabila login gagal.
- Menyediakan fitur logout untuk mengakhiri sesi pengguna.

**Referensi User Story:** US-05, US-06, US-07, US-08.

### 5.3 Dashboard and Investment Exploration

Fitur ini menyediakan ringkasan aktivitas investor serta sarana untuk menemukan posisi investasi yang tersedia.

**A. Dashboard**
- Menampilkan ringkasan aktivitas investor.
- Menampilkan bagian My Activity.
- Menampilkan bagian Recent Activity.

**B. Explore Investment**
- Menampilkan daftar posisi investasi yang tersedia.
- Menyediakan halaman detail posisi investasi.
- Menampilkan informasi nilai posisi, tenor, imbal hasil, dan risiko.
- Menyediakan pencarian berdasarkan kata kunci, termasuk instrumen atau platform.
- Menyediakan filter berdasarkan kategori yang tersedia.

**C. Integrated Account Access**
- Menyediakan akses ke halaman Offer Your Position.
- Menyediakan akses ke fungsi permintaan take-over.
- Kedua fungsi dapat diakses menggunakan satu akun.

**Referensi User Story:** US-12, US-13, US-14, US-15, US-16, US-17.

### 5.4 Position Submission and Eligibility

Fitur ini digunakan oleh investor penjual untuk mengajukan posisi investasi yang ingin ditawarkan melalui EXIT.

Kebutuhan fitur:
- Menyediakan halaman Offer Your Position.
- Menyediakan fungsi untuk membuat penawaran.
- Menyediakan form input informasi posisi investasi.
- Menyediakan fungsi pengiriman pengajuan untuk ditinjau.
- Menampilkan status Menunggu Pemeriksaan setelah pengajuan dikirim.
- Menampilkan indikator hasil pemeriksaan awal kelayakan.
- Menampilkan hasil pemeriksaan berupa Layak atau Tidak Layak.
- Memberikan informasi mengenai data atau informasi yang belum lengkap.
- Menyediakan fungsi perubahan atau pembatalan pengajuan sesuai statusnya.
- Menampilkan status pengajuan melalui bagian aktivitas investor.

**Tahapan pengajuan:**

1. Investor penjual membuat penawaran.
2. Investor mengisi informasi posisi investasi.
3. Investor mengirim pengajuan untuk ditinjau.
4. Sistem menampilkan status Menunggu Pemeriksaan.
5. Pengajuan melalui pemeriksaan awal.
6. Sistem menampilkan hasil pemeriksaan dan informasi kekurangan data apabila diperlukan.
7. Investor dapat memantau serta mengelola pengajuan sesuai statusnya.

**Referensi User Story:** US-18, US-19, US-20, US-21, US-22, US-23.

### 5.5 Investor Matching and Position Information

Fitur ini mendukung proses pencocokan antara posisi investasi yang ditawarkan dan calon investor yang berpotensi mengambil alih posisi tersebut.

Kebutuhan fitur:
- Menyediakan rekomendasi calon investor berdasarkan kriteria matching.
- Mempertimbangkan karakteristik posisi investasi yang ditawarkan.
- Mempertimbangkan profil investor, termasuk profil risiko investor pembeli.
- Menyediakan informasi risiko posisi investasi.
- Menampilkan riwayat pembayaran.
- Menampilkan nilai pengalihan.
- Menampilkan sisa tenor.
- Menampilkan ketentuan take-over.

Profil risiko investor pembeli menjadi salah satu pertimbangan dalam proses matching.

**Referensi User Story:** US-24, US-25.

### 5.6 Negotiation, Take-over Request, and Price Comparison

Fitur ini memfasilitasi interaksi investor penjual dan investor pembeli dalam menyampaikan permintaan serta membahas penawaran take-over.

**A. Negotiations**
- Menyediakan bagian Negotiations.
- Memfasilitasi negosiasi antara investor penjual dan investor pembeli.
- Mendukung pembahasan untuk mencapai kesepakatan harga take-over.

**B. Take-over Request**
- Menyediakan fungsi pengajuan permintaan take-over pada halaman Explore Investment atau detail posisi.
- Memungkinkan investor pembeli menyampaikan minat untuk mengambil alih posisi investasi yang dipilih.
- Menghubungkan permintaan tersebut dengan posisi investasi yang dituju.

**C. Price Comparison**
- Menyediakan fasilitas perbandingan beberapa penawaran yang telah melalui proses matching.
- Menampilkan ringkasan perbandingan investasi.
- Menampilkan parameter perbandingan berdasarkan informasi penawaran yang tersedia.

**Referensi User Story:** US-26, US-27, US-28.

### 5.7 Activity Tracking and History

Fitur ini digunakan untuk memantau aktivitas dan perkembangan proses penawaran maupun take-over.

Kebutuhan fitur:
- Menampilkan riwayat aktivitas pengguna pada bagian Activity.
- Menampilkan perkembangan status proses take-over.
- Menyediakan kategori atau tampilan Semua untuk melihat aktivitas terkait.
- Menampilkan informasi kondisi matching.
- Menampilkan jumlah permintaan yang masuk.
- Menampilkan informasi apabila belum ditemukan kecocokan matching.
- Menampilkan informasi tindak lanjut yang dapat dilakukan oleh pemilik posisi.

Apabila belum ditemukan calon investor yang sesuai, sistem menampilkan informasi no-match pada halaman My Offers. Informasi tersebut mencakup kondisi matching, jumlah permintaan yang masuk, dan tindak lanjut yang dapat dilakukan oleh pemilik posisi.

**Referensi User Story:** US-29, US-30, US-31.

---

## 6. MVP Scope and Development Priority

### 6.1 Ruang Lingkup Pengembangan

Pengembangan prototype EXIT mengikuti lima kelompok sprint dalam backlog User Stories.

| Sprint | Fokus Pengembangan | User Story |
|---|---|---|
| Sprint 1 | Foundation and User Access | US-01 sampai US-11 |
| Sprint 2 | Investment Dashboard and Exploration | US-12 sampai US-17 |
| Sprint 3 | Position Submission and Eligibility | US-18 sampai US-23 |
| Sprint 4 | Matching, Negotiation and Price Simulation | US-24 sampai US-28 |
| Sprint 5 | Tracking, History and Finalization | US-29 sampai US-32 |

Pembagian tersebut menjadi urutan pengembangan berdasarkan backlog tim.

### 6.2 Batasan Prototype

Berdasarkan ketentuan ruang lingkup prototype yang telah disepakati:

1. EXIT merupakan platform fasilitasi take-over posisi investasi, bukan bursa atau exchange.
2. Proses take-over hanya dapat dilakukan apabila diperbolehkan oleh ketentuan instrumen dan platform asal.
3. Data, penawaran, harga, dan imbal hasil dalam prototype dapat menggunakan data simulasi.
4. Simulasi tidak berarti transaksi investasi sungguhan telah terjadi.
5. Matching tidak menjamin seluruh posisi investasi memperoleh pembeli.

### 6.3 Kebutuhan Internal Proyek

Beberapa User Story merupakan kebutuhan internal pengembangan proyek, bukan fitur yang digunakan oleh investor.

| User Story | Kebutuhan | Keluaran |
|---|---|---|
| US-10 | Dokumentasi kebutuhan produk | Dokumen kebutuhan produk tersedia untuk mendukung pengembangan |
| US-11 | Repository proyek | Repository tersedia dan dapat diakses anggota tim terkait |
| US-32 | Pengujian dan perbaikan prototype | Fitur diuji, bug diidentifikasi, dan perbaikan dilakukan |

---

## 7. Functional Requirements

Kebutuhan fungsional berikut merupakan ringkasan kemampuan yang harus disediakan sistem berdasarkan User Stories.

| ID | Functional Requirement | Referensi |
|---|---|---|
| FR-01 | Sistem menampilkan informasi dasar dan manfaat EXIT. | US-01 |
| FR-02 | Sistem menampilkan cara kerja dan alur take-over. | US-02 |
| FR-03 | Sistem menampilkan informasi fitur utama EXIT. | US-03 |
| FR-04 | Sistem menyediakan FAQ. | US-04 |
| FR-05 | Sistem menyediakan registrasi dengan input nama, tanggal lahir, nomor telepon, email, dan OTP. | US-05 |
| FR-06 | Sistem menyediakan login bagi pengguna terdaftar. | US-06 |
| FR-07 | Sistem menyediakan logout. | US-07 |
| FR-08 | Sistem menampilkan informasi ketika login gagal. | US-08 |
| FR-09 | Sistem menampilkan identitas visual dan branding EXIT. | US-09 |
| FR-10 | Sistem menyediakan dashboard yang menampilkan ringkasan aktivitas investor. | US-12 |
| FR-11 | Sistem menampilkan daftar posisi investasi yang tersedia. | US-13 |
| FR-12 | Sistem menampilkan detail posisi investasi. | US-14 |
| FR-13 | Sistem menyediakan pencarian posisi investasi berdasarkan kata kunci. | US-15 |
| FR-14 | Sistem menyediakan filter posisi investasi berdasarkan kategori. | US-16 |
| FR-15 | Sistem memungkinkan satu akun mengakses fungsi penawaran dan permintaan take-over. | US-17 |
| FR-16 | Sistem menyediakan form pengajuan posisi investasi. | US-18 |
| FR-17 | Sistem menyediakan input informasi posisi investasi. | US-19 |
| FR-18 | Sistem menampilkan status dan indikator pemeriksaan kelayakan posisi. | US-20 |
| FR-19 | Sistem memberikan informasi mengenai kekurangan data pengajuan. | US-21 |
| FR-20 | Sistem menampilkan status pengajuan posisi investasi. | US-22 |
| FR-21 | Sistem menyediakan fungsi perubahan dan pembatalan pengajuan sesuai status. | US-23 |
| FR-22 | Sistem menampilkan rekomendasi matching berdasarkan kriteria yang ditentukan. | US-24 |
| FR-23 | Sistem menampilkan informasi risiko dan ketentuan posisi investasi. | US-25 |
| FR-24 | Sistem menyediakan fasilitas negosiasi antara investor penjual dan pembeli. | US-26 |
| FR-25 | Sistem menyediakan pengajuan permintaan take-over oleh investor pembeli. | US-27 |
| FR-26 | Sistem menyediakan perbandingan beberapa penawaran. | US-28 |
| FR-27 | Sistem menampilkan riwayat aktivitas pengguna. | US-29 |
| FR-28 | Sistem menampilkan status perkembangan proses take-over. | US-30 |
| FR-29 | Sistem menampilkan informasi apabila belum ditemukan kecocokan matching. | US-31 |

US-10, US-11, dan US-32 merupakan kebutuhan internal proyek dan tidak dimasukkan sebagai functional requirement aplikasi.

---

## 8. Business Rules

### 8.1 Account and User Access

1. Pengguna baru melakukan registrasi untuk memiliki akun EXIT.
2. Registrasi mencakup nama, tanggal lahir, nomor telepon, email, dan OTP.
3. Pengguna terdaftar dapat melakukan login.
4. Sistem memberikan informasi ketika proses login gagal.
5. Pengguna dapat mengakhiri sesi melalui logout.
6. Satu akun dapat digunakan untuk mengakses fungsi penawaran maupun permintaan take-over.

### 8.2 Position Submission

1. Investor penjual dapat mengajukan posisi investasi melalui fitur Offer Your Position.
2. Pengajuan harus memuat informasi posisi investasi yang diminta oleh form.
3. Pengajuan yang dikirimkan masuk ke status Menunggu Pemeriksaan.
4. Sistem menampilkan hasil pemeriksaan awal berupa Layak atau Tidak Layak.
5. Sistem memberikan informasi apabila terdapat kekurangan data atau informasi.
6. Pengajuan dapat diubah atau dibatalkan sesuai status yang berlaku.

### 8.3 Investment Exploration

1. Daftar posisi investasi menampilkan posisi yang tersedia untuk dieksplorasi.
2. Pengguna dapat mencari posisi berdasarkan kata kunci.
3. Pengguna dapat memfilter posisi berdasarkan kategori yang tersedia.
4. Informasi detail posisi menjadi bahan pertimbangan investor sebelum mengajukan permintaan take-over.

### 8.4 Matching

1. Matching dilakukan berdasarkan kriteria yang ditentukan.
2. Karakteristik posisi investasi menjadi salah satu dasar pencocokan.
3. Profil investor, termasuk profil risiko investor pembeli, menjadi pertimbangan dalam proses matching.
4. Hasil matching merupakan rekomendasi dan tidak menjamin terjadinya take-over.
5. Sistem dapat menampilkan kondisi no-match apabila belum ditemukan investor yang sesuai.

### 8.5 Negotiation and Take-over Request

1. Investor pembeli dapat mengajukan permintaan take-over terhadap posisi investasi yang dipilih.
2. Investor penjual dan investor pembeli dapat melakukan negosiasi.
3. Negosiasi ditujukan untuk mencapai kesepakatan harga take-over.
4. Beberapa penawaran dapat dibandingkan berdasarkan parameter informasi yang tersedia.
5. Pengajuan permintaan atau tercapainya kesepakatan dalam prototype tidak otomatis berarti hak investasi telah dialihkan.

### 8.6 Position Transfer

1. EXIT hanya berperan sebagai platform fasilitasi take-over.
2. EXIT bukan bursa atau exchange.
3. Pengalihan posisi investasi harus mengikuti ketentuan instrumen dan platform asal.
4. Simulasi pada prototype tidak merepresentasikan transaksi investasi sungguhan.

---

## 9. Non-Functional Requirements

### 9.1 Usability
Antarmuka harus mudah dipahami agar pengguna dapat mengenali fungsi utama, melakukan registrasi, menjelajahi posisi investasi, dan menggunakan fitur penawaran maupun permintaan.

### 9.2 Data Validation
Sistem harus menyediakan validasi pada data registrasi dan informasi posisi investasi yang dimasukkan pengguna.

### 9.3 Information Clarity
Informasi nilai posisi, tenor, imbal hasil, risiko, riwayat pembayaran, nilai pengalihan, dan ketentuan take-over harus disajikan dengan jelas.

### 9.4 Status Visibility
Status pengajuan, hasil pemeriksaan, perkembangan matching, dan riwayat aktivitas harus dapat diketahui pengguna melalui aplikasi.

### 9.5 Interface Consistency
Landing page dan aplikasi harus memiliki identitas visual yang konsisten agar pengguna dapat mengenali platform EXIT.

---

## 10. Assumptions, Constraints, and Risks

### 10.1 Assumptions

1. EXIT dikembangkan sebagai prototype platform fasilitasi take-over posisi investasi.
2. Data posisi investasi dan informasi terkait dapat menggunakan data simulasi.
3. Rekomendasi matching menggunakan kriteria yang ditentukan dalam pengembangan prototype.
4. Satu akun dapat digunakan untuk fungsi penawaran dan permintaan take-over.
5. Informasi risiko dan ketentuan posisi investasi disediakan sebagai bahan pertimbangan pengguna.

### 10.2 Constraints

1. EXIT bukan bursa atau exchange.
2. Prototype tidak merepresentasikan transaksi investasi sungguhan.
3. Data, penawaran, harga, dan imbal hasil dapat berupa data simulasi.
4. Pengalihan posisi investasi bergantung pada ketentuan instrumen dan platform asal.
5. Matching tidak menjamin seluruh posisi investasi memperoleh pembeli.

### 10.3 Risks

| Risiko | Dampak terhadap Produk |
|---|---|
| Posisi investasi tidak memenuhi kriteria pemeriksaan awal | Posisi tidak dapat melanjutkan proses penawaran sesuai hasil pemeriksaan |
| Informasi posisi tidak lengkap | Calon investor kesulitan melakukan penilaian |
| Tidak ditemukan investor yang sesuai | Proses matching tidak menghasilkan rekomendasi yang relevan |
| Perbedaan ekspektasi harga | Negosiasi dapat mengalami hambatan |
| Ketentuan instrumen atau platform asal tidak memungkinkan pengalihan | Take-over tidak dapat dilaksanakan meskipun terdapat minat dari investor lain |

---

## 11. Success Metrics

Keberhasilan prototype EXIT dinilai berdasarkan keterlaksanaan fungsi yang telah ditentukan dalam User Stories.

| Area | Indikator Keberhasilan | Referensi |
|---|---|---|
| Platform Information | Informasi pengenalan, cara kerja, fitur, FAQ, dan identitas EXIT tersedia. | US-01–US-04, US-09 |
| Account Access | Registrasi, login, logout, dan informasi login gagal tersedia. | US-05–US-08 |
| Dashboard | Dashboard menampilkan ringkasan aktivitas investor. | US-12 |
| Investment Exploration | Daftar, detail, pencarian, dan filter posisi investasi dapat digunakan. | US-13–US-16 |
| Account Integration | Satu akun dapat mengakses fungsi penawaran dan permintaan. | US-17 |
| Position Submission | Investor dapat mengajukan posisi dan mengisi informasi yang dibutuhkan. | US-18–US-19 |
| Eligibility | Sistem menampilkan status pemeriksaan dan informasi kekurangan data. | US-20–US-21 |
| Offer Management | Status, perubahan, dan pembatalan pengajuan dapat dikelola sesuai ketentuan. | US-22–US-23 |
| Matching | Sistem menampilkan rekomendasi matching berdasarkan kriteria yang ditentukan. | US-24 |
| Risk Information | Detail risiko dan ketentuan posisi dapat dilihat pengguna. | US-25 |
| Negotiation | Fasilitas negosiasi dan permintaan take-over tersedia. | US-26–US-27 |
| Comparison | Informasi beberapa penawaran dapat dibandingkan. | US-28 |
| Activity Tracking | Riwayat dan status proses take-over dapat dipantau. | US-29–US-30 |
| No-Match | Sistem menampilkan informasi ketika belum ditemukan kecocokan. | US-31 |
| Quality Assurance | Fitur diuji, bug diidentifikasi, dan perbaikan dilakukan. | US-32 |

---

## 12. Items Requiring Team Confirmation

Beberapa detail dalam User Stories masih memerlukan keputusan tim sebelum implementasi agar tidak terjadi perbedaan interpretasi antara System Analyst, UI/UX Designer, Vibe Coder, dan QA.

| User Story | Hal yang Perlu Dikonfirmasi |
|---|---|
| US-05 | Apakah OTP dikirim secara aktual atau disimulasikan dalam prototype? |
| US-12 | Informasi apa saja yang ditampilkan pada My Activity dan Recent Activity? |
| US-14 dan US-25 | Bagaimana susunan informasi detail posisi investasi yang akan ditampilkan? |
| US-20 dan US-21 | Apa kriteria Layak dan Tidak Layak serta informasi yang harus dilengkapi pengguna? |
| US-23 | Status pengajuan apa saja yang memungkinkan perubahan atau pembatalan? |
| US-24 | Apa parameter karakteristik posisi dan profil risiko yang digunakan untuk matching? |
| US-26 | Bagaimana bentuk interaksi, penyampaian penawaran harga, dan respons kedua pihak? |
| US-27 | Acceptance Criteria saat ini menyebut hasil simulasi, sedangkan judul dan NOTE menjelaskan pengajuan permintaan take-over. Keduanya perlu diselaraskan. |
| US-28 | Informasi apa saja yang dibandingkan dalam ringkasan penawaran? |
| US-31 | Tindak lanjut apa yang tersedia bagi pemilik posisi ketika belum ditemukan kecocokan? |

Keputusan atas hal-hal tersebut menjadi dasar penyempurnaan User Stories dan penyusunan User Flow.

---

## 13. Document Relationship and Next Development Outputs

PRD ini menjadi dokumen acuan utama dalam proses analisis dan pengembangan prototype EXIT. Setiap dokumen berikutnya harus diturunkan dari kebutuhan produk yang telah dijelaskan dalam PRD.

Urutan dokumen dan pekerjaan pengembangan:

1. **Product Requirements Document (PRD)**  
   Menjelaskan gambaran produk, permasalahan, tujuan, pengguna, fitur, ruang lingkup, kebutuhan fungsional, aturan bisnis, dan batasan sistem.

2. **User Stories**  
   Menjabarkan kebutuhan dalam PRD menjadi tindakan spesifik berdasarkan sudut pandang pengguna, disertai Acceptance Criteria yang dapat diuji.

3. **User Flow**  
   Menggambarkan urutan interaksi pengguna dengan sistem, termasuk pilihan tindakan, kondisi, dan hasil pada setiap proses.

4. **Database Design**  
   Menentukan data yang perlu disimpan, struktur tabel, atribut, dan hubungan antardata berdasarkan User Stories dan User Flow.

5. **UI/UX Design and Prototype Development**  
   Menerjemahkan kebutuhan dan alur sistem menjadi rancangan antarmuka serta implementasi prototype aplikasi.

6. **Quality Assurance (QA)**  
   Melakukan pengujian terhadap fitur berdasarkan User Stories dan Acceptance Criteria, mengidentifikasi bug, serta memastikan prototype berjalan sesuai kebutuhan.

---

**End of Document**

*Dokumen ini merupakan acuan kebutuhan produk EXIT untuk pengembangan prototype. Perubahan kebutuhan dan keputusan implementasi selanjutnya perlu diselaraskan dengan User Stories, User Flow, dan kesepakatan tim.*
