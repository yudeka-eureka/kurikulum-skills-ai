# QUALITY GATES, PEER-REVIEW, & STANDAR ETIKA (KIHAJAR ACADEMY)

Dokumen ini memuat daftar periksa kendali mutu (*Quality Gates*), protokol pengujian buta (*blind dry-run*), panduan bahasa bebas klise (*antislop*), serta standar etika AI akademik.

---

## 1. PROTOKOL CONTINUOUS PEER-REVIEW

Dalam model Tim Lean (1 Lead Trainer merangkap penulis), kendali mutu ditegakkan oleh **1 orang Peer Reviewer (Kolega Instruktur / QA)** di setiap akhir tahap sebelum penulis berpindah ke tahap berikutnya:

| Gerbang Mutu | Dokumen yang Ditinjau | Peninjau Utama | Syarat Kelulusan Mutu (Quality Gate) |
| :--- | :--- | :--- | :--- |
| **Gate 1** | Silabus Training | Peer Reviewer | Capaian SMART 3 ranah terdefinisi, luaran portofolio fungsional terkunci, relevan dengan IKU kampus. |
| **Gate 2** | Modul Praktikum / Kasus | Peer Reviewer (QA) | Lolos **Blind Dry-Run** (0 langkah ambigu), aset starter/solution teruji di Google Drive/GitHub, tabel troubleshooting lengkap. |
| **Gate 3** | Modul Ajar Konseptual | Peer Reviewer | Struktur 6 bagian lengkap, menyertakan *worked example* & *non-example*, bebas *split-attention*, lolos uji bahasa *antislop*. |
| **Gate 4** | Slide Presentasi Dual Format | Lead Trainer & Reviewer | Tersedia versi Roadshow (90m) dan Workshop (1 Hari), memenuhi aturan *One Idea per Slide*, 100% slide memiliki Presenter Notes. |

Ulasan dilakukan secara lincah melalui fitur **Komentar Google Docs** dengan batas respons maksimal 1x24 jam per gerbang.

---

## 2. PROTOKOL BLIND DRY-RUN TESTING

*Blind Dry-Run* adalah pengujian eksekusi laboratorium secara independen oleh pihak ketiga untuk membuktikan bahwa instruksi praktikum benar-benar dapat diikuti tanpa bimbingan lisan:

1. **Lingkungan Bersih**: Peer Reviewer menyiapkan akun Google Workspace uji coba yang belum pernah menjalankan lab tersebut sebelumnya.
2. **Eksekusi Literal**: Reviewer menjalankan instruksi baris demi baris secara harfiah. Reviewer **dilarang bertanya** atau meminta bantuan kepada penulis modul.
3. **Pencatatan Hambatan**:
   - Jika Reviewer berhenti atau tersesat pada langkah tertentu, langkah tersebut dinilai **Gagal / Ambigu** dan wajib direvisi.
   - Jika muncul pesan error tak terduga, catat detailnya untuk dimasukkan ke dalam **Tabel Troubleshooting**.
4. **Kalibrasi Waktu**: Catat durasi riil pengerjaan. Jika waktu eksekusi melampaui estimasi lebih dari 20%, instruksi harus disederhanakan atau dipecah menjadi beberapa *Exercise*.

---

## 3. PANDUAN BAHASA & HIGIENE ANTISLOP (ANTISLOP COPYWRITING)

Materi pelatihan Kihajar Academy wajib ditulis dengan bahasa Indonesia yang elegan, lugas, dan bebas dari gaya tulisan mesin (*AI-generated slop*):

### Aturan Redaksional:
1. **Gunakan Kalimat Aktif & Pelaku Jelas**: Hindari kalimat pasif bertumpuk. Tulis "Instruktur memandu..." bukan "Dipandukanlah oleh instruktur...".
2. **Eliminasi Kosakata Klise Hiperbolis**:
   - ❌ *Hapus kata-kata*: "merevolusi", "membuka cakrawala tanpa batas", "menyelami lebih dalam", "lanskap digital yang dinamis", "sangat penting untuk dicatat bahwa", "tak terbantahkan lagi".
   - ✅ *Ganti dengan*: kalimat lugas, data terukur, atau contoh konkret langsung.
3. **Disiplin Huruf Tebal (Bold)**:
   - ❌ Jangan menebalkan setiap kata penting di dalam paragraf sehingga teks tampak berantakan.
   - ✅ Gunakan huruf tebal HANYA untuk nama elemen antarmuka tombol/menu Google AI, judul heading, atau istilah teknis saat pertama kali didefinisikan.
4. **Klaim Wajib Disertai Bukti**: Jangan membuat klaim keberhasilan tanpa menyertakan konteks data atau studi kasus industri yang dapat diverifikasi.

---

## 4. STANDAR ETIKA AI AKADEMIK & PERLINDUNGAN DATA

Seluruh modul wajib menanamkan prinsip penggunaan AI yang bertanggung jawab (*Responsible AI*):

1. **Kepatuhan Deklarasi AI Scopus & Jurnal Internasional**:
   - Ajarkan dosen dan mahasiswa cara menuliskan klausul transparansi penggunaan AI pada bagian metodologi atau *acknowledgement* (contoh: *"During the preparation of this manuscript, the author(s) used Google NotebookLM to synthesize background literature. The authors reviewed and edited the content and take full responsibility for the content of the publication."*).
2. **Privasi & Kerahasiaan Data (UU PDP & ISO/IEC 42001)**:
   - Tegaskan perbedaan mendasar antara akun Google personal (gratis) dengan **Google Workspace for Education (GWFE)** institusional.
   - Pada akun institusional kampus berlisensi, data riset tidak digunakan untuk melatih model publik Google AI (*zero model training guarantee*).
3. **Pemberantasan Fabrikasi & Halusinasi**:
   - Tanamkan disiplin *Source Grounding*: selalu verifikasi nomor halaman, nama penulis, dan tautan DOI jurnal asli sebelum mencantumkan sitasi. Modul praktikum wajib melatih teknik *fact-checking* silang.
