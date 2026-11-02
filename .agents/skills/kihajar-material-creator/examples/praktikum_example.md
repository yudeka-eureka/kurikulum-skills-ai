# CONTOH & TEMPLATE BAKU MODUL PRAKTIKUM (KIHAJAR ACADEMY)

Dokumen ini adalah template acuan yang wajib diikuti oleh agent saat menghasilkan draf **Modul Praktikum (Hands-On Lab Guide)**.

---

# MODUL PRAKTIKUM: [JUDUL PRAKTIKUM]
**Kihajar Academy — Panduan Laboratorium AI Terapan**

## 1. IKHTISAR SKENARIO LABORATORIUM
* **Tujuan Praktikum**: `[Menyelesaikan tugas nyata apa]`
* **Mode Diátaxis**: `[Mode Tutorial (Terbimbing) ATAU Mode How-To / Case Challenge]`
* **Estimasi Waktu**: `[Misal: 60 Menit]`
* **Prasyarat Lingkungan**:
  - Akun Google Workspace teraktivasi.
  - Peramban Chrome versi terbaru.
* **Aset Praktikum**:
  - Starter Assets: `[Link Google Drive / GitHub folder bahan awal]`
  - Solution Assets: `[Link kunci jawaban hasil akhir tervalidasi]`
  - Checkpoints: `[Titik pemulihan jika peserta tertinggal di tengah jalan]`

---

## 2. PANDUAN EKSEKUSI LANGKAH KERJA

### Exercise 1: [Nama Exercise 1 - Dimulai dengan Kata Benda / Fungsional]
`[1 paragraf pengantar mengenai sasaran besar yang dicapai pada Exercise 1 ini.]`

#### Task 1: [Nama Task - Diawali Kata Kerja Aksi, Sentence Case, Tanpa Titik]
Pada tugas ini, Anda akan [sebutkan outcome / hasil yang diperoleh setelah task ini tuntas].

1. Pada peramban web Anda, buka laman **Google NotebookLM** (notebooklm.google) untuk masuk ke dashboard utama.
2. Di pojok kiri atas layar, klik tombol **New Notebook** untuk membuat ruang kerja riset baru.
3. Pada jendela pop-up sumber referensi, pilih menu **Upload Sources**, lalu pilih berkas `dataset_jurnal_pustaka.pdf` dari folder starter assets Anda untuk memuat bahan telaah.
4. Tunggu hingga proses indexing selesai, lalu pastikan indikator hijau muncul di samping nama berkas untuk memverifikasi dokumen telah terbaca sempurna.

> **Penting**: Pastikan koneksi internet stabil selama proses pengunggahan berkas agar embedding dokumen tidak terputus.

#### Task 2: Ekstraksi Variabel dan Research Gap
Pada tugas ini, Anda akan memetakan variabel penelitian dan menemukan celah kebaruan riset secara otomatis.

1. Pada panel chat di bagian bawah, salin dan tempelkan prompt terstruktur berikut ke dalam kotak pesan:
```markdown
Berdasarkan dokumen yang telah diunggah, identifikasi dan buatkan tabel komparasi berisi:
1. Nama Penulis & Tahun
2. Variabel Independen dan Dependen
3. Metodologi yang Digunakan
4. Temuan Kunci
5. Keterbatasan Penelitian (Research Gap) yang Belum Terjawab
Sajikan jawaban secara lugas dan cantumkan nomor halaman sitasi persis di setiap poin.
```
2. Tekan tombol **Submit** atau **Enter** untuk mengirimkan perintah analisis kepada sistem.
3. Setelah jawaban muncul, klik ikon **Save to Note** pada panel kanan atas untuk menyimpan tabel hasil ekstraksi ke dalam lembar catatan proyek Anda.

---

### Exercise 2: [Nama Exercise 2 - Kasus Lanjutan / How-To Challenge]

#### Task 3: Verifikasi Sumber dan Formulasi Deklarasi Etika
Pada tugas ini, Anda akan memastikan keaslian kutipan dan merumuskan klausul etika AI sesuai standar Scopus.

1. Pada catatan tabel yang telah disimpan, klik nomor sitasi `[1]` untuk membuka langsung halaman PDF sumber guna memverifikasi kebenaran kutipan.
2. Di jendela dokumen utama Google Docs naskah Anda, buka menu **Tools**, lalu pilih **Originality Reports** untuk menjalankan pemindaian kemiripan teks.
3. Di akhir draf naskah riset Anda, tambahkan sub-judul baru **Declaration of Generative AI in Scientific Writing** dan tempelkan teks klausul transparansi berikut:
```markdown
Declaration: During the preparation of this manuscript, the author(s) utilized Google NotebookLM solely for literature synthesis and research gap mapping. All extracted information was manually verified against original sources. The author(s) take full responsibility for the content and integrity of this publication.
```

---

## 3. CHECKLIST VERIFIKASI MANDIRI
Pastikan seluruh kriteria berikut terpenuhi sebelum Anda menyerahkan tugas praktikum ini:
- [ ] Berkas starter berhasil diimpor tanpa pesan error.
- [ ] Tabel ekstraksi memuat minimal 5 artikel jurnal lengkap dengan sitasi persis.
- [ ] Draf naskah telah diverifikasi ke sumber aslinya.
- [ ] Klausul deklarasi etika AI telah tersemat di berkas naskah.

---

## 4. TABEL TROUBLESHOOTING KENDALA UMUM

| Gejala Error / Hambatan | Kemungkinan Penyebab | Solusi Perbaikan Langkah Demi Langkah |
| :--- | :--- | :--- |
| **Berkas PDF gagal dimuat atau indexing macet** | Format PDF berupa scan gambar tanpa lapisan teks (OCR). | Buka PDF di Google Drive $\rightarrow$ Klik kanan **Buka dengan Google Dokumen** untuk mengonversi menjadi teks $\rightarrow$ Simpan ulang sebagai PDF baru. |
| **Jawaban tidak memunculkan nomor sitasi** | Prompt tidak menginstruksikan pencantuman nomor sitasi secara eksplisit. | Ulangi prompt dengan menambahkan instruksi: *"Wajib sertakan penomoran sitasi sumber di setiap baris tabel."* |
| **Batas kuota prompt tercapai saat analisis** | Terlalu banyak dokumen tebal yang dianalisis dalam satu kueri besar. | Centang hanya 3-5 sumber prioritas di panel kiri, jalankan analisis per klaster, lalu gabungkan hasilnya ke catatan. |
