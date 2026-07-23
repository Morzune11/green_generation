**MOCKUP WEBSITE**

# 🌿 Green Generation- Sistem Pengelolaan Bank Sampah & Tabungan Sekolah

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Green Generation** adalah platform antarmuka web modern berbasis ekosistem *Eco-Education* yang dirancang untuk mengelola penyetoran sampah plastik dan konversinya menjadi tabungan siswa di lingkungan sekolah secara efisien, transparan, dan terintegrasi.

---

## 🚀 Fitur Utama Berdasarkan Peran (*Role*)

Aplikasi ini dibagi menjadi beberapa modul antarmuka sesuai dengan peran pengguna:

### 👨‍🎓 1. Modul Siswa
* **Laporan Siswa**: Memantau riwayat penyetoran sampah dan akumulasi saldo tabungan.
* **Pengaturan Profil**: Mengelola data diri, nomor rekening tabungan, serta pembaruan kata sandi.

### 🏫 2. Modul Admin Sekolah
* **Setor Plastik**: Input dan catat penimbangan sampah plastik harian dari siswa/kelas.
* **Laporan Rekap Sekolah**: Melihat rekapitulasi total tonase sampah dan konversi nilai tabungan tingkat sekolah.
* **Pengaturan Profil**: Pengelolaan data identitas penanggung jawab dan informasi sekolah.

### 🚛 3. Modul Petugas Pungut
* **Pencatatan Penjemputan**: Menyelaraskan volume sampah yang dijemput dari lokasi sekolah.
* **Profil Petugas**: Pengelolaan data operasional lapangan.

### 🏦 4. Modul Admin Bank Sampah
* **Verifikasi & Rekap Keuangan**: Konfirmasi transaksi saldo masuk dari hasil daur ulang.
* **Pengaturan Akun**: Sinkronisasi data unit bank sampah mitra.

---

## 🎨 Keunggulan Desain & Antarmuka (UI/UX)

* **Design System Konsisten**: Menggunakan skema warna *Eco Green* (`#16a34a`) dan tipografi modern **Inter**.
* **Tata Letak Dua Kolom (*Grid System*)**: Layout responsif dan rapi pada modul pengaturan profil dan formulir input.
* **Layout Responsif**: Mendukung tampilan Desktop, Tablet (dengan *collapsible sidebar*), dan Perangkat Seluler.
* **Aksesibilitas & Feedback**: Dilengkapi efek *hover*, state *focus*, serta indikator status terikat (*readonly/disabled*).

---

## 📂 Struktur Direktori Proyek

```text
ClassApp/
│
├── 📁 Siswa/
│   ├── profile_siswa.html          # Halaman pengaturan profil siswa
│   └── laporan_siswa.html          # Halaman rekap tabungan siswa
│
├── 📁 AdminSekolah/
│   ├── profile_admin_sekolah.html  # Halaman profil admin sekolah
│   ├── setor_plastik_admin.html    # Form input penyetoran sampah
│   └── laporan_admin_sekolah.html  # Laporan rekapitulasi sekolah
│
├── 📁 Petugas/
│   └── profile_petugas.html        # Halaman profil petugas pengumpul
│
├── 📁 Bank/
│   └── profile_admin_bank.html     # Halaman profil admin bank sampah
│
├── 📁 Login/
│   ├── siswa.html                  # Login portal siswa
│   └── admin_sekolah.html          # Login portal admin sekolah
│
├── 📁 Icons/                       # Asset ikon pendukung
└── 📄 README.md                    # Dokumentasi proyek
