# **\`WORKBOOK: LEMBAR KERJA MAHASISWA (WS08)**

## **Peer Critique I & Design Revision / Decision Log**

### **INFORMASI UTAMA**

- **Mata Kuliah**: Konsep Sistem Informasi (KSI)
- **Kerangka Kerja**: Project-Based Learning (PBL) Level 1
- **Learning Moment**: _Fase 4: Design (Minggu 6–7)_
- **Sub-CPMK / SFIA**: S-03.1 (Intermediate) | SFIA CSMG L2 (_Communication & Peer Assessment_)
- **Keterkaitan Deliverable**: Sumber utama penyusunan **Decision Log (TPL-08)** dan **Deliverable D2 Final (TPL-02)**
- **Phase Lead**: **Mahasiswa D** (_Phase Lead 4 — Design_)

### **RUANG KERJA TIM (WORKSPACE)**

#### **1\. IDENTIFIKASI KELOMPOK & REVIEWER**

- **Nama Tim Penyaji**: Tim Gyanatama
- **Nama Tim Penguji (Reviewer)**: Valencia
- **Tanggal Sesi Critique I**: 11/11/2026

#### **2\. MATRIKS EVALUASI SAKSI CRITIQUE I (PENGUJI SEJAWAT)**

_Petunjuk untuk Tim Penguji: Berikan skor (1-5) dan catatan konstruktif berdasarkan protokol Be Kind, Be Specific, Be Helpful._

| **Aspek Evaluasi**                              | **Skor (1-5)** | **Catatan Kritis Penilai (_Be Specific & Be Helpful_)**                                                                        |
| ----------------------------------------------- | -------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **1\. Kejelasan Problem Framing & Boundaries**  | 4              | Penjabaran sudah baik, tetapi masih kurang pada bagian Worksheet 4 di mana workspace tidak sinkron antara penting dan terukur. |
| **2\. Konsistensi Arsitektur 4 Lapisan SI**     | 4              | Sudah terstruktur, rapi dan mudah dimengerti.                                                                                  |
| **3\. Kelengkapan IPO & Error Handling**        | 4              | Sesuai, tetapi pada IPO pengguna hanya menginputkan nomor, saran dari kami tetap perlu menginputkan nama.                      |
| **4\. Kebenaran Logika Flowchart & Pseudocode** | 4              | Pada flowchart penamaan pada tabel belum sesuai                                                                                |
| **5\. Kelayakan Operasional untuk Mitra**       | 4              | Sudah layak. Cukup perhatikan pada penataan kalimat.                                                                           |

#### **3\. REKAPITULASI CATATAN UMPAN BALIK CRITIQUE I**

_Petunjuk untuk Tim Penyaji: Catat seluruh masukan sticky notes dari tim penilai dan dosen pembimbing._

\[ KELOMPOK ISU CRITIQUE I \]

```
1. Masukan Arsitektur & Infrastruktur:
   - Pada error handling, menggunakan primary key agar ada nomor tetap dan pasti.
2. Masukan Logika Flowchart & Error Handling:
   - Sudah sesuai, hanya salah pada penamaan tabel
3. Masukan Kelayakan Operasional Mitra:
   - Sudah layak, cukup perhatikan pada penataan kalimat.
```



#### **4\. MATRIKS DECISION LOG REVISI DESAIN (SINKRON DENGAN TPL-08)**

Saring umpan balik di atas menggunakan 3 Dimensi Kelayakan O'Brien (**Operasional, Teknis, Ekonomi**):

| **ID Masukan** | **Catatan Umpan Balik Diterima**                           | **Status (_Diterima / Ditolak_)** | **Alasan Pertimbangan Kelayakan (O'Brien)**                                 | **Rencana Tindak Lanjut Revisi**                           |
| -------------- | ---------------------------------------------------------- | --------------------------------- | --------------------------------------------------------------------------- | ---------------------------------------------------------- |
| **CR-01**      | _Tambahkan penanganan eror jika stok kurang di flowchart._ | **DITERIMA**                      | **Teknis**: Mencegah eror logika saat koding di Python.                     | Memperbarui diagram flowchart & pseudocode pada WS07 & D2. |
| **CR-02**      | _Tambahkan fitur e-wallet otomatis via API Bank._          | **DITOLAK**                       | **Teknis & Operasional**: Melebihi batasan waktu semester (_Out of Scope_). | Mempertahankan batas sistem tunai/QRIS statis.             |
| **CR-03**      | \_**\_**\_**\_**\_**\_**\_**\_**\_**\_**\___               | \_**\_**\___                      | \_**\_**\_**\_**\_**\_**\_**\_**\_**\_**\___                                | \_**\_**\_**\_**\_**\_**\_**\_**\_**\_**\___               |

### **CHECKLIST REFLEKSI & PENGESAHAN WS08**

- Seluruh masukan Critique I telah tercatat dengan rapi.
- Keputusan DITERIMA/DITOLAK didasarkan pada analisis kelayakan terukur.
- Berkas **TPL-08 (Decision Log)** telah diperbarui berdasarkan hasil WS08.
- Diagram flowchart dan pseudocode pada D2 (TPL-02) telah direvisi.
- Tim penilai memberikan rating profesional pada **TPL-09 (Meeting & Assessment Log)**.

**Tanggal Pengesahan**: \_**\_**\_**\_**\_**\_**\__  
**Tanda Tangan Phase Lead 4 (Design)**: \_**\_**\_**\_**\_**\_**\__  
**Tanda Tangan Dosen Pembimbing / Coach**: \_**\_**\_**\_**\_**\_**\__