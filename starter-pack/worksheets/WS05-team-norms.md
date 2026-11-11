# **WORKBOOK: LEMBAR KERJA MAHASISWA WS05**

## **Formulasi Kebutuhan Fungsional: User Story & Acceptance Criteria**

Mata Kuliah: **Konsep Sistem Informasi (KSI)**  
Kerangka Kerja: **Project-Based Learning (PBL) Level 1**  
Fase Learning Spine: **Fase 3 — Define (Minggu 3)**  
Sub-CPMK / SFIA: **S-01.1 (Intermediate - Problem Framing) & S-03.1 (Intermediate - Pemetaan SI)** | **SFIA BUSA L1, REQM L2**  
Keterkaitan Deliverable: **Bahan Utama Deliverable D2 (System & Solution Design - TPL-02)**

### **1\. Identifikasi Kelompok & Rotasi Kepemimpinan**

- **Nama Kelompok**: Gyanatama
- **Objek UMKM Mitra**: Laundry Mamikha
- **Phase Lead 3 (Define)**: Purnomo Hardianto (Mahasiswa C)
- **Anggota Tim**: 1. Renaufal Azizul Ahnaf 2. Muhammad Rifqi Azis 3. Muhammad Wizdan Akbar Firdaus 4. Labib Fawwaz

### **2\. Landasan Konseptual: Analisis Sistem "What" vs "How"**

Dalam tahap _Systems Analysis_, fokus utama tim adalah menentukan **APA (_What_)** yang dibutuhkan pengguna bisnis untuk memecahkan masalahnya, **BUKAN BAGAIMANA (_How_)** sistem dibangun secara teknis (Marakas & O'Brien, 2013).

- **User Story** merepresentasikan kebutuhan fungsional dari sudut pandang pengguna bisnis dengan pola:  
  \$\$\\text{"Sebagai \[Peran Pengguna\], Saya ingin \[Kemampuan/Fitur\], Sehingga \[Manfaat Bisnis Nyata\]"}\$\$
- **Acceptance Criteria (Given-When-Then)** mendefinisikan batas kondisi kapan sebuah fitur dinyatakan selesai dan memenuhi syarat penerimaan pengguna (Rainer et al., 2021).

### **3\. Workspace A: Formulasi User Story Fungsional**

Petakan minimal **3 User Story Utama** yang langsung menjawab akar masalah pada D1 / WS04:

#### **User Story 1 (Prioritas Utama / Core Feature)**

- **Sebagai (_As a_)**: _Kasir Laundry Mamikha_
- **Saya ingin (_I want to_)**: _mencatatan rincian lembar pakaian pada nota tertulis atau sistem digital dan penghitungan ulang jumlah lembar sebelum diserahkan kembali ke customer._
- **Sehingga (_So that_)**_:_ _saya bisa memverifikasi apakah baju yang hilang tersebut benar-benar ada di manifes masuk laundry._

#### **User Story 2 (Fitur Manajemen Stok Data)**

- **Sebagai (_As a_)**: _Mas Harley (owner laundry)_
- **Saya ingin (_I want to_)**: _mencatat pemakaian pelicin dan bahan setrika per periode atau per order._
- **Sehingga (_So that_)**: _saya bisa memastikan takaran sesuai standar dan tidak terlalu sedikit sehingga hasil kurang rapi._

#### **User Story 3 (Fitur Pelaporan / Informasi)**

- **Sebagai (_As a_)**: _Mas Harley (owner laundry)_
- **Saya ingin (_I want to_)**: _melihat rekap kasus barang tertukar per periode_
- **Sehingga (_So that_)**: _menemukan pola penyebab (misalnya pada jam sibuk atau karyawan tertentu) dan memperbaiki prosedur._

### **4\. Workspace B: Acceptance Criteria Berbasis Skenario (Given-When-Then)**

Susun kriteria penerimaan terstruktur untuk **User Story 1** (mencakup Skenario Sukses dan Skenario Penanganan Eror):

#### **Skenario 1A: Transaksi Penjualan Berhasil (Happy Path)**

- **Diberikan (_Given_)**: _kasir menerima cucian dari customer dan kasir langsung menimbang cucian untuk menentukan total harga yang akan dibayar customer._
- **Ketika (_When_)**: _kasir mengisi nota dengan nama/nomor customer, tanggal masuk, serta rincian per jenis pakaian (jenis, jumlah lembar, catatan kondisi/warna)._
- **Maka (_Then_)**: _sistem menyimpan nota dengan nomor unik, menampilkan total lembar otomatis, dan nota dapat dicetak atau diberikan ke customer._

#### **Skenario 1B: Penanganan Pembayaran Kurang / Eror (Exception Path)**

- **Diberikan (_Given_)**: _customer mengklaim kehilangan pakaian di laundry tersebut._
- **Ketika (_When_)**: _jenis atau jumlah yang diklaim tidak ada di manifes masuk._
- **Maka (_Then_)**: _sistem menampilkan bahwa item tersebut tidak tercatat saat penerimaan, mencatat klaim sebagai "Tidak Terdokumentasi di Manifes", dan menyediakan kolom catatan agar kasir bisa meneruskannya ke owner._

### **5\. Workspace C: Catatan Validasi Kebutuhan dengan Mitra (Field Confirmation)**

- **Tanggal Validasi**: 11 November 2026
- **Narahubung Mitra**: Mas Harley (Pemilik)
- **Hasil Konfirmasi User Story**:  
  \[[√]] Seluruh User Story disetujui mitra  
  \[ \] Terdapat penyesuaian/revisi kebutuhan (Tuliskan revisi jika ada):

### **6\. Verifikasi Integritas AI (TPL-07) & Pengesahan**

- **Penggunaan AI Co-pilot**:  
  Apakah tim menggunakan AI untuk membantu merumuskan skenario _Given-When-Then_? \[ \] Ya \[ \] Tidak  
  _(Jika Ya, wajib melampirkan formulir_ **_TPL-07: AI Usage Disclosure & Verification Note_**_)_.

**Tanda Tangan Tim & Pengesahan Dosen**:

- **Phase Lead 3**: \_**\_**\_**\_**\_**\_**\_**\__ (Tanggal: \_**\_**\_**\_)
- **Dosen Coach**: \_**\_**\_**\_**\_**\_**\_**\__ (Tanggal: \_**\_**\_**\_) \[ \] Approved