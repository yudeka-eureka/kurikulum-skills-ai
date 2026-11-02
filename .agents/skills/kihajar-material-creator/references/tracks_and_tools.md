# PANDUAN TRACK & MODULAR TOOLKIT GOOGLE AI (KIHAJAR ACADEMY)

Dokumen ini memetakan karakteristik 3 track sasaran utama dan ekosistem perangkat Google AI yang menjadi standar dalam kurikulum Kihajar Academy.

---

## 1. PEMETAAN 3 TRACK SASARAN KAMPUS

### Track 1: Dosen Peneliti (Riset, Publikasi, dan BKD)
* **Karakteristik Audiens**: Dosen tetap, ketua tim peneliti, reviewer internal, pengelola jurnal kampus, pimpinan LPPM.
* **Tantangan Utama**:
  - Rata-rata 7+ jam tersita setiap minggu hanya untuk urusan administrasi dan penelusuran literatur manual.
  - Tuntutan akreditasi LAM/BAN-PT dan **IKU 5** (luaran penelitian bereputasi Scopus/WoS/SINTA).
  - Kekhawatiran isu plagiarisme dan privasi data riset kampus saat menggunakan AI publik.
* **Fokus Kompetensi**:
  1. *Sintesis Pustaka Presisi*: Menelaah puluhan/ratusan PDF jurnal sekaligus untuk memetakan variabel, metodologi, dan *research gap*.
  2. *Rekayasa Prompt Akademik*: Perancangan instrumen survei, kuesioner, dan validasi hubungan antarvariabel.
  3. *Olah Data & Visualisasi*: Analisis regresi, pemodelan statistik, dan pembuatan grafik standar jurnal.
  4. *Penulisan Akademik & Etika*: Penyuntingan manuskrip berbahasa Inggris, parafrasa etis, dan kepatuhan format Deklarasi AI Scopus.
* **Luaran Portofolio Wajib**: **Research Dossier** (Sintesis pustaka NotebookLM + Draf manuskrip bab 1-3 + Bukti olah data Sheets + Form Deklarasi Etika AI).

---

### Track 2: Mahasiswa Non-Tech (Karir ATS, Solopreneur, Produktivitas)
* **Karakteristik Audiens**: Mahasiswa aktif program Diploma/Sarjana dari rumpun ilmu sosial, humaniora, ekonomi, hukum, dan bisnis (FEB, FISIP, FIB, FH, Fikom).
* **Tantangan Utama**:
  - Kecemasan bahwa peran kerja mereka akan terdisrupsi atau digantikan oleh AI setelah lulus.
  - Kesulitan menembus sistem penyaringan otomatis pelamar kerja modern (*Applicant Tracking System / ATS*).
  - Kebutuhan membangun sumber penghasilan mandiri atau rintisan usaha sejak masa kuliah.
* **Fokus Kompetensi**:
  1. *Optimasi Karir & Profil*: Mengonversi riwayat organisasi dan tugas kuliah menjadi resume/CV yang ramah ATS dan profil LinkedIn profesional.
  2. *Simulasi Wawancara*: Latihan tanya-jawab teknis dan studi kasus wawancara kerja menggunakan persona rekruter AI.
  3. *Riset Pasar & Solopreneurship*: Validasi ide bisnis, riset pesaing, penulisan proposal penawaran, dan pembuatan aset konten pemasaran digital.
  4. *Produktivitas Akademik*: Meringkas materi kuliah, menyusun laporan magang, dan asistensi tugas akhir secara etis.
* **Luaran Portofolio Wajib**: **Career/Business Launchpad** (CV ramah ATS terverifikasi + Portofolio studi kasus industri + Canvas model bisnis solopreneur).
* **Dukungan Indikator**: **IKU 1** (Kesiapan Kerja Lulusan) dan penunjang **SKPI** (Surat Keterangan Pendamping Ijazah).

---

### Track 3: Mahasiswa Tech (Agentic AI, Coding, Inovasi Digital)
* **Karakteristik Audiens**: Mahasiswa jurusan Teknik Informatika, Ilmu Komputer, Sistem Informasi, Sains Data, Teknik Elektro, dan Rekayasa Perangkat Lunak.
* **Tantangan Utama**:
  - Coding konvensional (menulis sintaks manual baris-demi-baris) mulai digantikan oleh AI, sementara industri menuntut penguasaan *Agentic AI* dan *AI-assisted engineering*.
  - Portofolio coding di GitHub sering kali hanya berupa proyek tutorial generik yang tidak memiliki nilai jual bagi rekruter tech.
* **Fokus Kompetensi**:
  1. *Autonomous Agentic Coding*: Menguasai Google Antigravity untuk menjalankan agen mandiri, refactoring arsitektur, dan pair-programming cerdas.
  2. *Integrasi Gemini API & AI Studio*: Prototyping prompt multimodal, function calling, dan integrasi structured JSON ke dalam aplikasi.
  3. *Otomasi Alur Kerja (Google Flow & AppSheet)*: Membangun pipeline pemrosesan data cerdas tanpa/rendah kode.
  4. *Quality Assurance & Debugging*: Pengujian kode otomatis, vulnerability check, dan optimasi performa.
* **Luaran Portofolio Wajib**: **Agentic AI Repository** (Repositori GitHub proyek nyata dengan kode berjalan, deployment aktif, dan dokumentasi arsitektur AI).
* **Dukungan Indikator**: **IKU 1** (Talenta Digital Unggul) dan **IKU 4** (Praktisi Industri Mengajar).

---

## 2. MODULAR TOOLKIT GOOGLE AI ("LEGO BRICKS")

Instruktur dapat memasang dan mengombinasikan modul perangkat Google AI berikut secara fleksibel:

| Perangkat Google AI | Peran & Kekuatan Utama | Penerapan Ideal per Track |
| :--- | :--- | :--- |
| **Google NotebookLM** | Model berbasis sumber tertutup (*source-grounded*). Menelaah hingga puluhan dokumen PDF/catatan tanpa halusinasi, mencantumkan sitasi persis per kutipan, dan menyediakan fitur *Audio Overview*. | • **Track 1**: Tinjauan pustaka, pemetaan research gap, sintesis proposal riset.<br>• **Track 2**: Riset pasar kompetitor, telaah materi kuliah tebal. |
| **Google Gemini in GWFE** | Asisten produktivitas terintegrasi langsung di Google Docs (*Help Me Write*), Sheets (*Help Me Analyze*), dan Slides. Dilengkapi privasi tingkat enterprise kampus (data tidak dipakai melatih model publik). | • **Track 1**: Draf manuskrip jurnal, analisis data regresi, formula statistik.<br>• **Track 2**: Optimasi bahasa CV, copywriting proposal bisnis.<br>• **Track 3**: Brainstorming skema basis data & pseudocode. |
| **Google Antigravity** | Platform rekayasa *Agentic AI* generasi baru dari Google DeepMind. Memungkinkan eksekusi agen mandiri, navigasi codebase kompleks, background tasks, subagent spawning, dan pair-programming canggih. | • **Track 3**: Proyek coding software skala penuh, debugging otomatis, arsitektur multi-agent, refactoring sistem. |
| **Google Flow & Workflows** | Orkestrasi alur kerja tanpa kode / rendah kode (*low-code/no-code*). Menghubungkan Google Workspace, API, dan Gemini untuk mengotomasi alur data. | • **Track 2**: Otomasi form pendaftaran dan pengiriman email otomatis.<br>• **Track 3**: Pipeline pemrosesan dokumen cerdas, webhook, dan bot event-driven. |
| **Google AI Studio** | Lingkungan kerja cepat untuk rekayasa prompt tingkat lanjut, pengujian parameter model (temperature, safety settings), multimodal inputs, dan export kode API. | • **Track 1**: Perancangan instrumen riset terstruktur.<br>• **Track 3**: Prototyping API, system instructions, function calling. |
