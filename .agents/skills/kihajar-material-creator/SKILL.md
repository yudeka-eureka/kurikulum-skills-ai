---
name: kihajar-material-creator
description: >-
  Use this skill when the user wants to create, develop, or review training curriculum and learning materials for Kihajar Academy (Pelatihan AI Terapan untuk Institusi Pendidikan). Produces 4 standardized artifacts: Silabus Training, Modul Praktikum (Hands-On Lab), Modul Ajar Konseptual, and Slide Presentasi Pengajaran. Supports 3 specialized tracks: Dosen Peneliti, Mahasiswa Non-Tech, and Mahasiswa Tech across the Google AI ecosystem (Gemini, NotebookLM, Google Flow, Antigravity) with zero theory exam policy (pure functional deliverables).
---

# Kihajar Material Creator

Skill ini memandu AI agent untuk merancang dan memproduksi paket materi pelatihan profesional berstandar industri untuk **Kihajar Academy (Inisiatif Kemitraan Perguruan Tinggi bersama Eudeka & Google for Education Partner)**.

---

## 1. FONDASI UTAMA & PRINSIP TIDAK BOLEH DILANGGAR

Saat menyusun materi Kihajar Academy, agen **WAJIB** mematuhi 4 pilar berikut:

1. **Kebijakan Tanpa Ujian Teori (*Zero Exam Policy*)**:
   - Dilarang membuat kuis pilihan ganda, ujian esai teori, atau bank soal hafalan untuk penentuan sertifikasi.
   - Kelulusan sertifikat digital dinilai murni dari **Karya Portofolio Nyata (*Functional Deliverable*)**:
     - *Dosen Peneliti*: **Research Dossier** (Sintesis pustaka, draf manuskrip bab 1-3, form deklarasi etika AI).
     - *Mahasiswa Non-Tech*: **Career/Business Launchpad** (CV ramah ATS, portofolio studi kasus, canvas bisnis).
     - *Mahasiswa Tech*: **Agentic AI Repository** (Repositori GitHub proyek aktif, bot otomasi flow).
2. **Rantai Urutan Handoff Terbalik (*Backward Handoff Chain*)**:
   - Urutan wajib: **Silabus $\rightarrow$ Modul Praktikum $\rightarrow$ Modul Ajar $\rightarrow$ Slide Presentasi**.
   - Dilarang menulis Modul Ajar sebelum tugas dan aset di Modul Praktikum selesai dirancang dan diuji.
3. **Modular Toolkit Google AI ("Lego Bricks")**:
   - Selalu manfaatkan kombinasi perangkat resmi Google: **Google NotebookLM**, **Google Gemini in GWFE**, **Google Antigravity**, dan **Google Flow / Workflows**.
4. **Dukungan Indikator Kinerja Kampus (IKU)**:
   - Materi Dosen wajib dikaitkan dengan **IKU 5** (Publikasi Scopus/SINTA & Portofolio BKD).
   - Materi Mahasiswa wajib dikaitkan dengan **IKU 1** (Kesiapan Kerja Lulusan) dan **IKU 4** (Praktisi Mengajar).

---

## 2. PANDUAN EKSEKUSI OPERASIONAL AGEN

Agen dapat dijalankan dalam **Mode Paket Lengkap (End-to-End)** atau **Mode On-Demand (Dokumen Tunggal)** sesuai permintaan pengguna.

### Langkah 1: Diagnosis Parameter Modul
Sebelum mulai menyusun materi, tanyakan atau identifikasi 4 parameter kunci berikut:
1. **Topik Spesifik**: Apa keterampilan AI terapan yang akan diajarkan?
2. **Track Sasaran**:
   - `Track 1: Dosen Peneliti` (Riset, Jurnal Scopus/SINTA, BKD)
   - `Track 2: Mahasiswa Non-Tech` (Karir ATS, Solopreneur, Produktivitas)
   - `Track 3: Mahasiswa Tech` (Agentic AI, Antigravity, Google Flow)
3. **Kombinasi Tools Google AI**: (NotebookLM, Gemini in GWFE, Antigravity, atau Flow).
4. **Format Penghantaran**:
   - `Format A: Seminar / Roadshow Kampus (90-120 Menit)`
   - `Format B: Lokakarya Praktis (1 Hari Penuh / 4 Sesi @ 90 Menit)`

---

### Langkah 2: Produksi Fase 1 — Silabus Training
* Baca panduan detail di: [references/tracks_and_tools.md](./references/tracks_and_tools.md)
* Terapkan template acuan: [examples/silabus_example.md](./examples/silabus_example.md)
* **Kaidah Wajib**:
  - Gunakan kata kerja operasional aktif Taksonomi Bloom (Kognitif, Psikomotor, Afektif).
  - Tentukan instrumen bukti evaluasi portofolio sebelum menyusun matriks jadwal.
  - Sediakan tabel matriks jadwal sesi dengan pembagian durasi *chunking* 10–15 menit.

---

### Langkah 3: Produksi Fase 2 — Modul Praktikum / Kasus
* Baca panduan detail di: [references/backward_handoff.md](./references/backward_handoff.md)
* Terapkan template acuan: [examples/praktikum_example.md](./examples/praktikum_example.md)
* **Kaidah Wajib**:
  - Gunakan hierarki: **Exercise (H1) $\rightarrow$ Task (H2) $\rightarrow$ Numbered Steps (`1.`, `2.`)**.
  - Awali setiap Task dengan 1-2 kalimat pengantar hasil kerja (*outcome statement*).
  - Tulis setiap langkah dengan formula **Where, What, Why** dalam **tepat satu kalimat per langkah**.
  - Cetak **tebal (bold)** HANYA pada nama tombol/menu antarmuka Google AI.
  - Sajikan semua prompt dan kode dalam format blok teks siap salin (*copyable*).
  - Cantumkan **Tabel Troubleshooting** (*Gejala $\rightarrow$ Penyebab $\rightarrow$ Solusi*) di akhir modul.

---

### Langkah 4: Produksi Fase 3 — Modul Ajar Konseptual
* Baca panduan detail di: [references/backward_handoff.md](./references/backward_handoff.md)
* Terapkan template acuan: [examples/modul_ajar_example.md](./examples/modul_ajar_example.md)
* **Kaidah Wajib**:
  - Terapkan struktur 6 bagian konsisten: *1. Kasus Riil & Sasaran $\rightarrow$ 2. Aktivasi Konsep $\rightarrow$ 3. Teori Inti $\rightarrow$ 4. Worked Example & Non-Example $\rightarrow$ 5. Latihan Refleksi $\rightarrow$ 6. Rangkuman & Jembatan ke Lab*.
  - Sajikan contoh prompt ideal (*Worked Example*) bersanding dengan contoh prompt buruk yang memicu halusinasi (*Non-Example*).
  - Patuhi standar **Antislop Copywriting**: gunakan bahasa Indonesia yang lugas, aktif, profesional, tanpa kata-kata klise AI hiperbolis (baca [references/quality_gates.md](./references/quality_gates.md)).

---

### Langkah 5: Produksi Fase 4 — Slide Presentasi Pengajaran
* Baca panduan detail di: [references/backward_handoff.md](./references/backward_handoff.md)
* Terapkan template acuan: [examples/slides_outline_example.md](./examples/slides_outline_example.md)
* **Kaidah Wajib**:
  - Terapkan rasio layar **16:9** dengan prinsip multimedia Richard Mayer.
  - Aturan *One Idea Per Slide*: maksimal 3-4 butir poin ringkas, dilarang menumpuk paragraf panjang.
  - Sediakan **Slide Transisi Praktikum (Lab Prompt Slide)** yang jelas mengarahkan kelas membuka modul lab.
  - Setiap slide wajib dilengkapi **Presenter Notes** (skrip lisan instruktur, estimasi menit, dan pemicu interaksi).

---

## 3. CHECKLIST KELAYAKAN PAKET MATERI (QUALITY GATE)

Sebelum menyatakan materi selesai, lakukan validasi mandiri berdasarkan checklist [references/quality_gates.md](./references/quality_gates.md):
- [ ] Sasaran selaras dengan profil track dan metrik IKU kampus yang dituju.
- [ ] Bebas dari ujian teori hafalan; portofolio luaran karya didefinisikan secara tegas.
- [ ] Modul praktikum mematuhi aturan 1 kalimat per nomor dengan formula *Where, What, Why*.
- [ ] Modul ajar memuat perbandingan *Worked Example* dan *Non-Example*.
- [ ] Slide presentasi dilengkapi Presenter Notes dan slide penanda transisi lab.
- [ ] Bahasa Indonesia lugas, terstruktur rapi, dan bebas klise AI (*Antislop passed*).
