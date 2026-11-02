# Kurikulum & SOP Pembuatan Materi Training AI Terapan — Kihajar Academy
**Inisiatif Kemitraan Perguruan Tinggi bersama Eudeka (Mitra Resmi Google for Education & Google Professional Development Partner)**

Repositori ini memuat dokumen standar operasional prosedur (SOP), blueprint desain instruksional, slide konsep, dan skill agen AI untuk memproduksi paket materi pelatihan AI terapan bagi institusi pendidikan tinggi (Dosen & Mahasiswa: Tech & Non-Tech).

---

## 🎯 4 Pilar Inti Kurikulum Kihajar Academy

1. **Kebijakan Tanpa Ujian Teori (*Zero Exam Policy*)**:
   Kelulusan dan sertifikasi digital terverifikasi dinilai murni dari **Karya Portofolio Fungsional Nyata**:
   * **Dosen Peneliti**: *Research Dossier* (Sintesis pustaka, draf manuskrip artikel jurnal bab 1–3, dan form deklarasi etika AI Scopus) $\rightarrow$ Mendukung **IKU 5 & BKD**.
   * **Mahasiswa Non-Tech**: *Career/Business Launchpad* (CV lolos uji ATS, portofolio studi kasus industri, model bisnis solopreneur) $\rightarrow$ Mendukung **IKU 1 & SKPI**.
   * **Mahasiswa Tech**: *Agentic AI Repository* (Repositori GitHub aktif dengan kode berjalan, multi-agent bot, dan otomasi alur kerja) $\rightarrow$ Mendukung **IKU 1 & IKU 4**.

2. **Rantai Handoff Terbalik (*Backward Development Chain*)**:
   Urutan wajib penyusunan dokumen:
   $$\text{Silabus Training} \longrightarrow \text{Modul Praktikum (Hands-on Lab)} \longrightarrow \text{Modul Ajar Konseptual} \longrightarrow \text{Slide Presentasi}$$
   *Modul Ajar tidak boleh ditulis sebelum tugas praktikum dirancang dan diuji secara independen (Blind Dry-Run).*

3. **Modular Toolkit Google AI ("Lego Bricks")**:
   Modul dirancang lepas-pasang memanfaatkan ekosistem resmi Google:
   * **Google NotebookLM**: Asisten riset ilmiah bebas halusinasi (*source-grounded AI*).
   * **Google Gemini in GWFE**: Integrasi produktivitas & analisis statistik di Google Docs & Sheets.
   * **Google Antigravity**: Platform rekayasa *Agentic AI* & autonomous pair-programming.
   * **Google Flow & AppSheet**: Otomasi alur kerja tanpa kode (*low-code/no-code workflows*).

4. **Model Penghantaran Dual Format (*Dual Delivery*)**:
   * **Format Kilat**: Seminar / Roadshow Kampus (90–120 Menit) skala 100–500+ peserta.
   * **Format Mendalam**: Lokakarya Praktis 1 Hari (6 Jam / 4 Sesi @ 90 Menit) dengan 70% porsi *hands-on lab*.

---

## 📂 Struktur Repositori

```text
├── README.md                                          # Dokumentasi utama repositori
├── .gitignore                                         # Berkas pengabaian git
│
├── SOP_WORKFLOW_PEMBUATAN_MATERI_TRAINING_KIHAJAR.md  # Dokumen SOP resmi khusus Kihajar Academy
├── SOP_WORKFLOW_PEMBUATAN_MATERI_TRAINING.md          # Dokumen SOP dasar (Universal/Multi-domain)
│
├── Konsep_Workflow_Materi_Training_Kihajar.pdf        # Salinan PDF slide konsep Kihajar Academy (16:9)
├── Konsep_Workflow_Pembuatan_Materi_Training.pdf      # Salinan PDF slide konsep workflow universal
│
└── .agents/skills/kihajar-material-creator/           # Skill Antigravity untuk otomatisasi pembuatan materi
    ├── SKILL.md                                       # Instruksi utama aktivasi skill
    ├── references/                                    # Manual metodologi & standar (tracks, handoff, gates)
    └── examples/                                      # Template baku (silabus, praktikum, modul, slide)
```

---

## 🔗 Tautan Dokumen Kolaborasi (Google Workspace)

* **Google Docs SOP Kihajar Academy**: [Buka di Google Docs](https://docs.google.com/document/d/1cdGERDleXC4-5hnnxIX3X4qEUm_MEubXu0wkhlYWltI/edit)
* **Google Slides Konsep Kihajar Academy**: [Buka di Google Slides](https://docs.google.com/presentation/d/1jcyR8XrzAxZAmsHM4MajnY4slZhUDUNiaYj6D6UNiZA/edit)
* **Google Docs SOP Universal**: [Buka di Google Docs](https://docs.google.com/document/d/1pSCScbKY9r5T_YcZhuj-q3UnmiWNvF3fFNcNGAIr4k4/edit)
* **Google Slides Konsep Universal**: [Buka di Google Slides](https://docs.google.com/presentation/d/1Ql20ZgnUJ-RxjAGHPpoBLImgkPxJtmW44hUkYjHa3b8/edit)

---

## 🤖 Pemanfaatan Skill Antigravity `kihajar-material-creator`

Skill ini terpasang secara otomatis di `.agents/skills/kihajar-material-creator/` (dan secara global di `~/.gemini/config/skills/`).

Anda dapat memerintahkan asisten AI untuk memproduksi materi training baru dengan mengetik:
> *"Buatkan paket materi training Kihajar Academy lengkap untuk topik **Sintesis Pustaka Ilmiah dengan Google NotebookLM** untuk **Track Dosen Peneliti**."*

Agen AI akan mematuhi seluruh aturan pedagogi, formula kalimat *Where-What-Why*, alur 6 bagian Gagné, dan menghasilkan dokumen yang siap diaudit.
