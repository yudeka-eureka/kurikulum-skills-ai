# METODOLOGI INSTRUKSIONAL & RANTAI HANDOFF MATERI (KIHAJAR ACADEMY)

Dokumen ini memuat standar pedagogi dan desain instruksional internasional yang wajib dipatuhi dalam penyusunan seluruh materi training Kihajar Academy.

---

## 1. RANTAI URUTAN KERJA (BACKWARD HANDOFF CHAIN)

Kelemahan terbesar pembuatan materi konvensional adalah menulis bab teori terlebih dahulu secara berurutan, lalu bingung merancang praktikum di akhir sesi.

Dalam Kihajar Academy, urutan penyusunan wajib mematuhi **Backward Development**:

```
[Tahap 1: Silabus Training] 
   └── Kunci Capaian SMART, IKU Kampus, dan Spesifikasi Portofolio Akhir.
        │
        ▼ (Gate 1 Approved)
[Tahap 2: Modul Praktikum / Kasus]
   └── Rancang Tugas Hands-on, Siapkan Starter Assets, & Lakukan Blind Dry-Run.
        │
        ▼ (Gate 2 Approved)
[Tahap 3: Modul Ajar Konseptual]
   └── Tulis Narasi Teori, Analogi, & Worked Examples HANYA untuk Mendukung Praktikum.
        │
        ▼ (Gate 3 Approved)
[Tahap 4: Slide Presentasi Pengajaran]
   └── Rangkum Intisari Visual (One Idea per Slide) & Tulis Presenter Notes Lengkap.
        │
        ▼ (Gate 4 Approved)
[Paket Materi Siap Rilis ke Kelas]
```

---

## 2. STANDAR PENYUSUNAN SILABUS (BACKWARD DESIGN & BLOOM)

### Format Capaian Pembelajaran (SMART)
Setiap capaian pembelajaran wajib memenuhi kriteria:
* **Specific**: Menyebutkan tindakan konkret yang dilakukan peserta.
* **Measurable**: Dapat dibuktikan secara fisik melalui artefak yang dihasilkan.
* **Achievable**: Realistis diselesaikan dalam alokasi waktu sesi.
* **Relevant**: Berkontribusi langsung pada portofolio akhir dan capaian IKU.
* **Time-bound**: Memiliki batasan durasi pengerjaan yang jelas.

### Penjenjangan Taksonomi Bloom 3 Ranah
* **Ranah Kognitif (Logika & Pemahaman)**:
  - *Dilarang keras menggunakan kata kerja pasif/abstrak*: "memahami", "mengetahui", "mempelajari".
  - *Gunakan kata kerja operasional aktif*: mengidentifikasi, membandingkan, mendiagnosis, memetakan, merumuskan, mengevaluasi.
* **Ranah Psikomotor (Keterampilan Teknis & Aksi)**:
  - Mengonfigurasi, merekayasa prompt, menjalankan skrip, menyaring dataset, mengintegrasikan API, memvalidasi hasil sitasi.
* **Ranah Afektif (Sikap Kerja & Integritas)**:
  - Disiplin etika sitasi, kepatuhan perlindungan data pribadi (UU PDP), transparansi deklarasi penggunaan AI, ketelitian validasi fakta.

---

## 3. STANDAR PENYUSUNAN MODUL PRAKTIKUM (DIÁTAXIS & SKILLABLE)

### Kerangka Diátaxis (Daniele Procida)
Jangan mencampuradukkan panduan belajar dengan panduan kerja:
* **Mode 1: Tutorial (Learning-Oriented Lab)**:
  - Digunakan pada sesi pengenalan perangkat Google AI.
  - Sifat: *Single linear path*, instruksi terperinci langkah demi langkah, menghilangkan kejutan error di luar skenario, bertujuan memberikan keberhasilan pertama (*zero frustration*).
* **Mode 2: How-To Guide / Case Challenge (Task-Oriented Lab)**:
  - Digunakan pada sesi inti dan proyek akhir.
  - Sifat: Menghadapkan peserta pada masalah riil industri/kampus yang kompleks, menuntut peserta mengambil keputusan analitis mandiri.

### Hierarki Dokumen Lab (Skillable Standards)
1. **Exercise (Heading 1)**: Wadah besar kelompok latihan (misal: *Exercise 1: Ekstraksi Literatur Ilmiah Menggunakan NotebookLM*).
2. **Task (Heading 2)**: Tujuan kerja terukur yang diawali kata kerja tindakan dalam bentuk *sentence case* tanpa tanda titik di ujung (misal: *Task 2: Unggah berkas PDF dan petakan research gap*).
   - Wajib diawali 1-2 kalimat pengantar hasil (*outcome statement*).
3. **Numbered Steps (`1.`, `2.`, `3.`)**: Daftar langkah kerja urut.

### Formula Kalimat Instruksi Mikro "Where, What, Why"
Peserta lab membaca cepat sambil melihat layar. Gunakan formula baku:
* **Where (Di mana)**: Lokasi pada antarmuka layar (misal: *Pada panel sebelah kiri...*).
* **What (Apa yang dilakukan)**: Tindakan spesifik (misal: *...klik tombol Add Source...*).
* **Why (Mengapa)**: Alasan singkat tindakan (misal: *...untuk mengimpor berkas PDF riset.*).
* **Aturan Penting**:
  - Tepat **satu kalimat per nomor langkah**.
  - Huruf **tebal (bold)** hanya digunakan untuk elemen antarmuka (nama tombol/menu).
  - Teks prompt dan perintah disajikan dalam format kode siap salin (*copy-paste friendly*).
  - Sertakan **Tabel Troubleshooting** (*Gejala Error $\rightarrow$ Kemungkinan Penyebab $\rightarrow$ Solusi*) di akhir setiap latihan.

---

## 4. STANDAR PENYUSUNAN MODUL AJAR (GAGNÉ 6-BAGIAN & COGNITIVE LOAD)

### Manajemen Beban Kognitif (Cognitive Load Theory)
* **Kendalikan Intrinsic Load**: Scaffolding materi dari konsep fundamental menuju konsep kompleks.
* **Eliminasi Extraneous Load**: Tempatkan diagram arsitektur atau tangkapan layar antarmuka Google AI tepat menyatu dengan teks ulasan (*bebas split-attention effect*).
* **Fasilitasi Germane Load**: Berikan analogi konkret dunia nyata dan tabel komparasi istilah.

### Struktur 6 Bagian Wajib per Bab (Gagné & Merrill)
1. **Bagian 1: Masalah Dunia Nyata & Sasaran Bab**: Mulai dengan studi kasus masalah industri atau urgensi riset kampus.
2. **Bagian 2: Aktivasi Konsep**: Hubungkan topik dengan pengalaman sehari-hari peserta atau materi bab sebelumnya.
3. **Bagian 3: Pemaparan Konsep Inti**: Penjelasan logika dan prinsip kerja sistem secara padat dan terstruktur.
4. **Bagian 4: Worked Examples & Non-Examples**:
   - Tampilkan 1 contoh prompt sukses lengkap dengan hasilnya dan bedah alasan mengapa prompt tersebut efektif.
   - Tampilkan 1 contoh prompt buruk (*non-example*) yang memicu halusinasi dan jelaskan cara memperbaikinya.
5. **Bagian 5: Latihan Refleksi Mikro**: Pertanyaan penalaran cepat untuk mengecek pemahaman kognitif sebelum masuk praktikum.
6. **Bagian 6: Rangkuman & Jembatan ke Praktikum**: 3-5 poin intisari dan kalimat arahan beralih ke Modul Praktikum.

---

## 5. STANDAR PENYUSUNAN SLIDE PRESENTASI (MAYER PRINCIPLES)

* **Rule of One Idea Per Slide**: Setiap slide hanya memuat 1 pesan utama visual. Maksimal 3-4 butir poin ringkas.
* **Bukan Dokumen Bacaan**: Slide adalah alat bantu instruktur saat live di kelas, bukan pengganti buku teks modul ajar.
* **Presenter Notes Lengkap**: Setiap slide wajib dilengkapi skrip poin pembicaraan (*talking points*), estimasi menit, dan pertanyaan pemicu interaksi kelas.
* **Slide Transisi Praktikum (Lab Prompt Slide)**: Wajib menyertakan slide khusus yang memberi instruksi jelas saat kelas berpindah ke sesi hands-on lab.
