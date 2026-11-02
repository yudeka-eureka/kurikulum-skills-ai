# CONTOH & TEMPLATE BAKU MODUL AJAR KONSEPTUAL (KIHAJAR ACADEMY)

Dokumen ini adalah template acuan yang wajib diikuti oleh agent saat menghasilkan draf **Modul Ajar Konseptual**.

---

# MODUL AJAR: [JUDUL MODUL]
**Kihajar Academy — Bahan Pembelajaran Konseptual & Panduan Belajar Mandiri**

---

## BAB 1: [JUDUL BAB - DEKLARATIF & BERORIENTASI MASALAH]

### 1.1 Masalah Dunia Nyata & Sasaran Pembelajaran (Problem & Objectives)
`[Mulai bab dengan skenario masalah nyata di lingkungan kampus atau industri. Contoh: bagaimana peneliti menghabiskan puluhan jam membaca literatur yang akhirnya tidak relevan, atau bagaimana pelamar kerja gagal di tahap awal karena CV tidak lolos mesin ATS.]`

**Setelah menuntaskan bab ini, Anda akan mampu:**
1. Memahami prinsip kerja logika sistem [Nama Tools Google AI] dan batasan etisnya.
2. Mengidentifikasi pola penyusunan prompt efektif berbasis kebutuhan tugas nyata.
3. Menerapkan teknik penyelesaian masalah langkah-demi-langkah sebelum beralih ke sesi praktikum.

---

### 1.2 Aktivasi Konsep & Analogi Dunia Nyata (Activation)
`[Hubungkan konsep baru dengan pemahaman lama atau gunakan analogi sehari-hari yang akrab.]`

*Contoh Analogi*:
> Membayangkan Google NotebookLM sama seperti Anda mempekerjakan seorang asisten peneliti yang sangat teliti. Jika Anda memberinya 10 buku di mejanya dan memintanya menjawab pertanyaan HANYA dari 10 buku tersebut, ia tidak akan mengarang jawaban dari luar ruangan. Inilah yang disebut arsitektur *Source-Grounded AI* — model dikunci agar hanya berbicara dari dokumen yang Anda sediakan, sehingga risiko halusinasi dapat ditekan hingga mendekati nol.

---

### 1.3 Penjelasan Konsep Inti (Core Concept)
`[Sajikan teori dan prinsip kerja secara padat dan terstruktur. Gunakan tabel komparasi bila membedakan dua opsi atau istilah.]`

#### Tabel Perbandingan: AI Publik vs Google Workspace for Education
| Parameter | Akun Publik Pribadi (Gratis) | Akun Google Workspace for Education (GWFE) |
| :--- | :--- | :--- |
| **Pelatihan Model Publik** | Data naskah berisiko dimanfaatkan untuk melatih AI publik | **Zero Model Training**: Data naskah Anda dijamin tidak digunakan melatih AI publik |
| **Kepatuhan Privasi** | Standar konsumen umum | Selaras dengan regulasi perlindungan data global & **UU PDP** Indonesia |
| **Pemeriksaan Kemiripan** | Manual dan terbatas | **Originality Reports** tanpa batas per kelas |
| **Audit Hak Kekayaan Intelektual** | Rentan kebocoran temuan baru | Hak cipta dan kepemilikan naskah terlindungi penuh di bawah domain kampus |

---

### 1.4 Demonstrasi Kasus: Worked Example & Non-Example (Demonstration)
Untuk memahami kualitas instruksi, pelajari perbandingan kasus nyata berikut:

#### ❌ Non-Example (Contoh Buruk yang Memicu Halusinasi):
```
Prompt Buruk:
"Carikan jurnal bagus tentang AI di kampus dan buatkan tinjauan pustakanya sekarang juga."
```
*Mengapa ini gagal*: Prompt tidak memiliki batasan sumber, tidak menyebutkan variabel spesifik, dan membiarkan AI mencari secara bebas di web terbuka. Hasilnya adalah daftar kutipan yang sering kali fiktif (*hallucinated citations*) dengan nomor volume jurnal palsu.

#### ✅ Worked Example (Contoh Ideal Berbasis Sumber):
```
Prompt Teruji:
"Sebagai asisten peneliti akademik, telaah 5 berkas PDF yang telah diunggah di ruang kerja ini. 
Identifikasi:
1. Research gap yang belum terselesaikan pada artikel A dan B terkait adopsi AI oleh dosen.
2. Rekomendasi metodologi kuantitatif yang diusulkan oleh artikel C.
Sajikan dalam 2 paragraf padat dan cantumkan nomor sitasi persis di setiap temuan."
```
*Mengapa ini efektif*: Menetapkan persona yang tepat, membatasi ruang lingkup hanya pada dokumen terunggah (*grounded*), merinci instruksi hasil yang diinginkan, dan mewajibkan sitasi bernomor.

---

### 1.5 Latihan Refleksi Mikro (Application)
Sebelum membuka lembar kerja praktikum, jawablah pertanyaan penalaran berikut secara mandiri:
1. Jika Anda ingin meneliti topik baru di mana Anda belum memiliki file PDF jurnalnya, perangkat Google AI manakah yang sebaiknya Anda gunakan terlebih dahulu: Google Gemini atau Google NotebookLM? Mengapa?
2. Sebutkan satu risiko pelanggaran etika akademik jika seorang peneliti tidak mendeklarasikan penggunaan AI generatif dalam penulisan manuskrip jurnalnya.

---

### 1.6 Rangkuman Bab & Jembatan ke Praktikum (Integration)
* **Poin Kunci 1**: AI generatif berfungsi sebagai pemercepat kerja (*multiplier*), bukan pengganti nalar kritis dan tanggung jawab moral akademisi.
* **Poin Kunci 2**: Arsitektur *source-grounded* pada Google NotebookLM menjamin integritas sitasi ilmiah bebas fabrikasi.
* **Poin Kunci 3**: Penggunaan AI pada publikasi jurnal wajib diimbangi dengan transparansi metodologi (*AI Declaration*).

> **Langkah Selanjutnya**: Pemahaman konsep Anda telah tuntas. Sekarang, silakan beralih ke berkas **Modul Praktikum (Exercise 1)** untuk mempraktikkan langsung langkah-langkah di atas pada komputer kerja Anda.
