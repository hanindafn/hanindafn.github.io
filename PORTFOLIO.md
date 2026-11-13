# Portofolio Profesional & Kasus Proyek

**Haninda Faisa Nurrofifah**  
*Informatics Engineering Graduate | Data Analytics & Mining | Full-Stack Web Developer*  
📍 Sukoharjo / Surakarta, Jawa Tengah, Indonesia  
✉️ [haninda.faisa@gmail.com](mailto:haninda.faisa@gmail.com) | 🌐 [LinkedIn](https://linkedin.com/in/haninda-faisa) | 💻 [GitHub](https://github.com/hanindafn)

---

## 📌 Ringkasan Eksekutif (Executive Summary)

Lulusan S1 Teknik Informatika Universitas Muhammadiyah Surakarta dengan IPK **3.92 / 4.00**. Memiliki keahlian teruji dalam **Data Analytics, Data Mining, Machine Learning/NLP, dan Full-Stack Web Development**. 

Berpengalaman memimpin tim pengembangan aplikasi sistem informasi pemerintahan (*SI TOEKANG* di Diskominfo Surakarta) dan mempublikasikan penelitian ilmiah sebagai **First Author** di konferensi internasional bereputasi IEEE (*SIML 2026*). Terampil dalam siklus data menyeluruh (ekstraksi, *data cleaning*, analisis statistik inferensial, *predictive modeling*) serta implementasi solusi perangkat lunak yang terukur menggunakan Python, SQL, Laravel, dan Filament.

---

## 🎓 Pendidikan

**Universitas Muhammadiyah Surakarta (UMS)** — Surakarta, Jawa Tengah  
*Sarjana Komputer (S.Kom) - Teknik Informatika* | **2022 – 2026**  
- **IPK**: **3.92 / 4.00**
- **Mata Kuliah Utama**: *Data Warehouse, Data Mining, Machine Learning Fundamentals, Database Systems, Algorithms & Data Structures, Statistics, Object-Oriented Programming, Web Programming*.

---

## 💼 Pengalaman Kerja & Kepemimpinan

### 1. Team Lead & Fullstack Web Developer Intern
**Dinas Komunikasi, Informatika, Statistik dan Persandian (Diskominfo) Surakarta**  
*Maret 2025 – Mei 2025*
- Memimpin tim dalam merancang dan mengembangkan **SI TOEKANG** (*Integrated Government Maintenance System*), sistem pelaporan dan pemeliharaan sarana prasarana TI pemerintahan kota Surakarta.
- Mengubah alur kerja pelaporan manual via WhatsApp menjadi portal berbasis web yang terpusat dengan fitur *role-based access control*, pelacakan status penanganan (*ticketing*), dan rekam jejak servis terstruktur.
- Merancang arsitektur basis data relasional MySQL ternormalisasi dan membangun modul CRUD interaktif menggunakan ekosistem **Laravel & Filament**.
- Mengakomodasi kebutuhan pemangku kepentingan OPD (*Organisasi Perangkat Daerah*) ke dalam arsitektur sistem informasi yang efisien dan andal.

### 2. Asisten Laboratorium Komputer & Sains Data
**Program Studi Teknik Informatika, Universitas Muhammadiyah Surakarta**  
*2023 – 2026*
- Membimbing **30+ mahasiswa per semester** dalam praktikum *Data Warehouse* dan *Data Mining*, meliputi tahap pra-pemrosesan data (*cleaning, transformation*), klasifikasi, dan *clustering* dengan Python dan SQL.
- Menjadi mentor praktikum untuk mata kuliah *Object-Oriented Programming (OOP)*, Algoritma & Struktur Data, serta Pemrograman Web Full-Stack.
- Menyusun materi modul praktikum, studi kasus teknis, dan instrumen penilaian performa mahasiswa.

---

## 🔬 Publikasi Ilmiah & Pengalaman Riset

### 1. Penulis Utama (First Author) — Konferensi Internasional IEEE
**Judul**: *"A Socio-Technical Analysis of Bug-Introducing Commits in the Apache Ecosystem"*  
**Publikasi**: *2026 International Conference on Smart Computing, IoT, and Machine Learning (SIML 2026)*  
**DOI**: [10.1109/SIML69834.2026.11621096](https://doi.org/10.1109/SIML69834.2026.11621096)  
- Mengembangkan *mining pipeline* berbasis **RA-SZZ** (*Refactoring-Aware SZZ*) dengan Python dan PyDriller untuk menelusuri *Bug-Introducing Commits* (BICs) secara akurat pada 5 repositori *open-source* berskala besar (ActiveMQ, Camel, Hadoop, HBase, Tuscany) yang mencakup **>150.000 commit**.
- Mengintegrasikan data historis commit Git dengan metadata isu JIRA untuk mengevaluasi interaksi faktor teknis (ukuran commit, prioritas bug) dan sosio-teknis (*ownership concentration, bus factor, self-correction, developer tenure*).
- Menerapkan pengujian statistik **Spearman Rank Correlation** dan **Mann–Whitney U Test** untuk mengukur signifikansi faktor risiko *regression bug* dan durasi penyelesaian (*Time-to-Fix*).
- **Temuan Kunci**:
  - Ukuran perubahan kode (*change size*) tidak berkorelasi linier dengan *regression bug*, melainkan kerentanan komponen (*component risk*) yang memegang peranan krusial ($r$ hingga $0.56$).
  - Perilaku *self-correction* (developer yang memicu bug memperbaikinya sendiri) terbukti mempercepat resolusi bug hingga **58.8%** (pada Apache Hadoop).

### 2. Peneliti Pendamping (Co-Author)
**Judul**: *"Understanding Workflow Dynamics Beyond Conventional Performance Metrics"*  
*Status: Under Journal Review (2026)*  
- Melakukan eksplorasi data (*Exploratory Data Analysis* - EDA), pembersihan data anomali, dan standarisasi variabel penelitian.
- Berkontribusi dalam interpretasi temuan empiris serta penulisan manuskrip ilmiah pada bagian metodologi dan analisis hasil.

---

## 💻 Studi Kasus Proyek Pilihan (Project Case Studies)

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ 1. SI TOEKANG - Sistem Pemeliharaan Terpadu Instansi Pemerintah             │
├─────────────────────────────────────────────────────────────────────────────┤
│ Tech Stack : Laravel, Filament, PHP, MySQL, Bootstrap/Tailwind              │
│ Peran      : Team Lead & Full-Stack Developer                               │
│ Dampak     : Efisiensi pelaporan naik 100%, menghilangkan tiket tercecer    │
└─────────────────────────────────────────────────────────────────────────────┘
```
- **Latar Belakang**: Pelaporan kendala sarpras dan pemeliharaan TI sebelumnya dilakukan secara tersebar via WhatsApp, memicu seringnya tiket terlupakan, ketiadaan metrik respon tim teknis, dan sulitnya audit aset.
- **Solusi**: Membangun portal berbasis web dengan *dashboard* pemantauan real-time untuk admin, teknisi, dan perwakilan OPD.
- **Fitur Utama**:
  - Pembuatan tiket kendala dengan lampiran bukti visual.
  - Alur persetujuan dan penugasan teknisi otomatis (*ticket assignment*).
  - Riwayat servis inventaris perangkat keras dan rekapitulasi data periodik.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ 2. Analisis Sentimen Ulasan Pengguna Aplikasi iQIYI                         │
├─────────────────────────────────────────────────────────────────────────────┤
│ Tech Stack : Python, IndoBERT, Transformers, Scikit-learn, Selenium/BS4     │
│ Peran      : Data Scientist / ML Engineer                                   │
│ Fokus      : Natural Language Processing (NLP) & User Satisfaction Trends   │
└─────────────────────────────────────────────────────────────────────────────┘
```
- **Latar Belakang**: Mengetahui sentimen publik dan keluhan spesifik pengguna platform *video on-demand* iQIYI dari ulasan berbahasa Indonesia yang sarat bahasa informal/slang.
- **Solusi & Pipeline**:
  - Scraping ribuan ulasan ulasan aplikasi dari Google Play Store.
  - Normalisasi teks: pembersihan emoji, stopword removal, *slang-word normalization*, dan tokenisasi.
  - Melakukan *fine-tuning* model Transformer pretrained **IndoBERT** untuk klasifikasi multi-kelas/biner sentimen.
  - Evaluasi performa model dengan metrik *Accuracy, Precision, Recall, F1-Score*, dan matriks konfusi (*confusion matrix*).
  - Menyusun *insight actionable* mengenai fitur yang paling disukai dan dikeluhkan pelanggan.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ 3. Website Interaktif Merchandise Studio                                    │
├─────────────────────────────────────────────────────────────────────────────┤
│ Tech Stack : Laravel, MySQL, JavaScript, Procreate                          │
│ Peran      : Full-Stack Web Developer & Visual Asset Designer               │
│ Output     : Platform Showcase Katalog Digital & Identitas Visual           │
└─────────────────────────────────────────────────────────────────────────────┘
```
- **Solusi**: Merancang *brand identity* studio merchandise mulai dari ilustrasi digital kustom (Procreate) hingga implementasi web responsif (Laravel & MySQL) untuk memamerkan katalog produk kreatif dan manajemen galeri karya secara mandiri.

---

## 🛠️ Keahlian & Keterampilan Teknis (Skill Matrix)

| Kategori | Teknologi & Metodologi |
| :--- | :--- |
| **Programming Languages** | Python, SQL, PHP, JavaScript, HTML5/CSS3 |
| **Data Analytics & Mining** | Data Cleaning, Exploratory Data Analysis (EDA), Statistical Testing (Spearman, Mann-Whitney U), Data Warehouse, Data Mining |
| **Machine Learning & NLP** | Scikit-learn, IndoBERT, Hugging Face, Feature Engineering, Classification, Clustering |
| **Web Development & DB** | Laravel, Filament, MySQL, Relational Database Modeling, REST API |
| **Tools & Platforms** | Git, GitHub, PyDriller, JIRA, Looker Studio, Tableau, Microsoft Excel, Procreate |
| **Bahasa** | Bahasa Indonesia (Native), Bahasa Inggris (Profisien) |

---

## 📞 Kontak & Profil

- **Email**: [haninda.faisa@gmail.com](mailto:haninda.faisa@gmail.com)
- **LinkedIn**: [linkedin.com/in/haninda-faisa](https://linkedin.com/in/haninda-faisa)
- **GitHub**: [github.com/hanindafn](https://github.com/hanindafn)
- **Lokasi**: Sukoharjo / Surakarta, Jawa Tengah, Indonesia
