[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9039688&assignment_repo_type=AssignmentRepo)
# Live Code 3

## Instruction

Live Code ini dikerjakan dalam format ***notebook*** dan push file notebook pekerjaannya ke <strong>repository soal</strong>. **Beri nama file dengan: h8_p0lc3_NAMA.ipynb**

---

## Problem

Kamu adalah seorang data analis di Austin Smart City. Saat ini, kamu sedang membantu kepolisian kota Austin untuk mempelajari kondisi tindak kejahatan di kota Austin.

Dataset yang akan digunakan dapat diakses menggunakan `bigquery-public-data` pada Google Cloud Big Query.

Buka [Google Cloud Platform](https://console.cloud.google.com/), masuk ke BigQuery, lalu buka tab `bigquery-public-data` atau klik link [berikut](https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=samples&page=dataset&_ga=2.245085957.1471931019.1642739417-486643658.1638156099) atau link [berikut](https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=austin_crime&t=crime&page=table) untuk langsung menuju ke tabel.

`PERHATIKAN!`
* Data yang digunakan adalah tabel `crime` pada dataset `austin_crime`.
* Setiap jawaban, wajib menyertakan query yang dikerjakan pada BigQuery ke dalam notebook di tiap nomor penjabaran masalahnya
* Simpan setiap hasil Query ke dalam file .csv dengan format nama file: `P0LC3_Nama_Nomor Soal.csv` contoh: `P0LC3_Fahmi_1.csv`.
* Load data menggunakan Pandas untuk setiap soal.

Supaya analisismu terarah, kita perlu membuat penjabaran masalah dan kemudian dapat disimpulkan. Namun, sebelum membuat penjabaran masalah, pastikan sudah menentukan *problem statement* agar kesimpulan yang dibuat lebih terarah.

### **PROBLEM STATEMENT**
1. Definisikan problem statement berdasarkan penjabaran masalah di bawah yang akan teman-teman jawab menggunakan SQL!

### **Penjabaran Masalah**
1. Tampilkan tabel crime sampai 5 baris pertama
2. Apa saja jenis tindak kejahatan yang terjadi di kota Austin selama tahun 2016?
3. Berapa banyak kasus tindak kejahatan berdasarkan kasus pembersihannya (clearance status) selama tahun 2016?
4. Jenis kejahatan apa saja yang paling banyak belum terselesaikan kasusnya di tahun 2016?
5. Di bulan apa di tahun 2016 kasus pencurian (theft) sangat banyak terjadi?
6. Di distrik apa yang paling banyak terjadi kasus pencurian selama 2016?
7. Berapa lama rata-rata waktu (dalam hari) kasus tindak kejahatan 'theft' terselesaikan sejak kasus tersebut terangkat selama tahun 2016? (`Hint: Hitung selisih hari dari timestamp hingga clearance date`)

**PERHATIKAN:** untuk nomor 2-6, tiap nomor diharuskan ada insight yang disampaikan. Tidak perlu membuat plot/data visualisasi. Hanya tampilkan berupa dataframe (langsung hasil dari query)!

### **Poin Analisis**
1. Dari penjabaran yang sudah kamu bahas (pertanyaan 2-7), apa kesimpulan yang kamu dapat sampaikan?

---

## Assignment Rubrics

### 1. Code Review
**Impementasi Code Python**
|No.|Criteria|Meet Expectations|Points|
|--- |--- |--- |--- |
|a|SQL Queries|Mampu mengolah data sampai siap dianalisa meliputi data cleaning dan missing value checking/handling | 5 pts each (35 pts max) |

### 2. Conceptual & Analysis
**Menjawab Pertanyaan**
|No.|Criteria|Meet Expectations|Points|
|--- |--- |--- |--- |
|a|Problem Statement|Mampu mendefinisikan problem statement| 4 pts |
|b|Insights|Mampu memberikan kesimpulan/insight dari masing-masing penjabaran (poin penjabaran 2-7) | 6 pts each (36 pts max) |
|c|Overall Analysis|Mampu memberikan kesimpulan/insight dari penjabaran dan problem statement pada poin analisis| 15 pts |

### 3. Readability

|Criteria|Meet Expectations|Points|
|--- |--- |--- |
|Tertata Dengan Baik|Semua Cell Di Notebook Terdokumentasi Dengan Baik Dengan Markdown Pada Tiap Cell Untuk Penjelasan Kode dan **Format Notebook Sesuai dengan Template**.| 10 pts |

---

```{admonition} Total Points
**100**
```
