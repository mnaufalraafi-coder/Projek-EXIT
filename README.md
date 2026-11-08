# EXIT - Early Investment Take Over

> **Your Investment, Your Exit**

EXIT adalah prototipe platform fintech yang membuka akses likuiditas bagi investasi yang lebih luas dan inklusif. Lewat mekanisme take-over posisi investasi, EXIT mempertemukan investor yang ingin keluar lebih awal dengan investor lain yang bersedia mengambil alih, secara terstruktur dan transparan.

Proyek ini dibuat untuk tugas proyek Scrum mata kuliah **Inovasi Keuangan Digital** (Sekolah Vokasi UI).

> **Catatan:** EXIT masih berupa prototipe untuk keperluan akademik. Seluruh data dan transaksi di dalamnya hanya contoh dan bukan produk investasi yang sebenarnya.

---

## Latar Belakang

Banyak investor memegang posisi investasi yang fleksibilitasnya terbatas sebelum periode investasinya berakhir. Ketika membutuhkan dana lebih awal, pilihan untuk keluar sering kali sempit, tidak transparan, atau merugikan.

EXIT hadir sebagai layanan digital untuk mengalihkan atau melepas posisi investasi secara terstruktur, sehingga investor punya jalur keluar yang lebih jelas dan investor baru bisa masuk ke investasi yang sudah berjalan.

## Nilai yang Ditawarkan

- **Flexibility:** investor tidak harus menunggu sampai investasi jatuh tempo.
- **Transparency:** nilai dan kondisi posisi investasi ditampilkan secara terbuka.
- **Liquidity opportunity:** peluang mendapatkan dana lebih awal lewat take-over.
- **Convenience:** proses dilakukan secara digital dari awal sampai akhir.

## Alur Take-Over

```
Existing Investor -> EXIT -> Verification -> Valuation -> Matching -> New Investor -> Settlement
```

1. **Existing Investor** mengajukan posisi investasi yang ingin dilepas.
2. **Verification** memastikan identitas dan kepemilikan posisi.
3. **Valuation** menentukan nilai posisi yang akan dialihkan.
4. **Matching** mempertemukan posisi dengan investor yang berminat.
5. **New Investor** mengambil alih posisi tersebut.
6. **Settlement** menyelesaikan perpindahan dana dan hak investasi.

## Ekosistem

Aktor yang terlibat dalam ekosistem EXIT:

- Existing investor dan new investor
- Platform EXIT
- Asset / product provider
- Verification / KYC provider
- Valuation / data provider
- Payment / settlement
- Technology provider
- Regulator

## Halaman yang Tersedia

| File | Keterangan |
| --- | --- |
| `index.html` | Halaman utama: hero, cara kerja, fitur, dan FAQ |
| `login.html` | Halaman masuk ke aplikasi investor |
| `assets/` | Gambar yang dipakai halaman (logo dan ilustrasi hero) |

## Struktur Repositori

```
Projek-EXIT/
├── README.md
├── index.html
├── login.html
└── assets/
    ├── logo.png
    └── hero.png
```

## Menjalankan Secara Lokal

Proyek ini berupa HTML dan CSS statis, jadi tidak perlu instalasi apa pun.

1. Clone repositori:
   ```bash
   git clone https://github.com/<username>/Projek-EXIT.git
   cd Projek-EXIT
   ```
2. Buka `index.html` langsung di browser, atau jalankan server lokal, misalnya dengan ekstensi **Live Server** di VS Code.

Untuk menampilkannya secara online, aktifkan **GitHub Pages** di *Settings > Pages*, pilih branch `main` dan folder `/ (root)`.

## Desain

Tampilan mengikuti identitas visual EXIT:

| Peran | Warna |
| --- | --- |
| Latar | `#f9f6f1` (krem) |
| Aksen utama | `#b07932` (perunggu emas) |
| Teks utama | `#0f1b33` (navy) |
| Badge | `#f5e2c4` (peach) |

Font: **Playfair Display** untuk judul dan **Plus Jakarta Sans** untuk teks.

## Tim dan Peran

Pengembangan memakai kerangka kerja **Scrum** dengan pembagian peran:

- Scrum Master
- System Analyst
- UI/UX Designer
- Vibe Coder
- Quality Assurance (QA)

## Rencana Pengembangan

- [x] Halaman utama (`index.html`)
- [x] Halaman login (`login.html`)
- [ ] Dashboard investor
- [ ] Daftar posisi investasi yang tersedia untuk take-over
- [ ] Alur pengajuan dan pengambilalihan posisi
- [ ] Dokumentasi (`docs/`)

## Lisensi

Proyek akademik. Belum ada lisensi terbuka yang ditetapkan.
