[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8212453&assignment_repo_type=AssignmentRepo)
# Graded Challenge 1

_Graded Challenge ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Fulltime Program khususnya pada konsep Basic SQL, Python, serta Data Preparation with Pandas._

---

## Dataset Description

* Pada graded challenge ini, data diakses menggunakan `bigquery-public-data` pada Google Cloud Big Query.
* Buka [Google Cloud Platform](https://console.cloud.google.com/), masuk ke BigQuery, lalu buka tab `bigquery-public-data` atau klik link [berikut](https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=samples&page=dataset&_ga=2.245085957.1471931019.1642739417-486643658.1638156099) atau link [berikut](https://console.cloud.google.com/bigquery?p=bigquery-public-data&d=covid19_jhu_csse_eu&page=dataset&project=rock-wonder-317907) untuk langsung menuju ke dataset.

```{attention}
Perhatikan petunjuk penggunaan dataset!
```

1. Gunakan tabel `summary` pada database `covid19_jhu_csse_eu`.
2. Buatlah query sesuai dengan kebutuhan analisis/eksplorasi kamu (sesuaikan dengan problem statement).
3. Simpan dataset dalam bentuk csv, dengan nama `h8dsft_P0GC1_<nama-students>.csv`. Pastikan seluruh data tersimpan (*clue*: Simpan ke dalam Google Drive supaya data tersimpan seluruhnya, kemudian di download di local atau di-load ke Google Colab).
4. Salin query yang telah dibuat di Google Cloud Platform, tulislah pada bagian atas notebook!
5. Tampilkan `head` dan `tail` dari dataset pada notebook!

---

## Assignment Instructions

*Graded Challenge 1* dikerjakan dalam format ***notebook*** dengen beberapa **kriteria wajib** di bawah ini:

1. *Library* yang digunakan adalah **Pandas**.

2. *Project* dinyatakan selesai dan diterima untuk dinilai jika saat dilakukan `Run All` pada *notebook*, semua *cell* berhasil tereksekusi sampai akhir.

3. Isi *notebook* harus mengikuti *outline* di bawah ini:
   1. Perkenalan
      > Bab pengenalan harus diisi dengan identitas, latar belakang permasalahan, dan *problem statement* yang ingin dibahas.
   
   2. Import pustaka yang dibutuhkan
      > *Cell* pertama pada *notebook* **harus berisi dan hanya berisi** semua *library* yang digunakan dalam *project*.
   
   3. Data Loading
      > Bagian ini berisi query yang sudah dibuat dan proses *data loading* yang kemudian dilanjutkan dengan *explorasi data* secara sederhana.
   
   4. Data Cleaning
      > Bagian ini berisi proses penyiapan data berupa data cleaning sebelum dilakukan *explorasi data* lebih lanjut. Proses cleaning dapat berupa memberi nama baru untuk setiap kolom, mengisi missing values, menghapus kolom yang tidak dipakai, dan lain sebagainya.
   
   5. Explorasi Data
      > Bagian ini berisi explorasi data pada dataset diatas dengan menggunakan query, grouping, visualisasi sederhana, dan lain sebagainya.

   6. Pengambilan Kesimpulan
      > Pada bab terakhir ini, **harus berisi** kesimpulan yang mencerminkan hasil yang didapat dengan dibandingkan dengan *problem statement* yang sudah ditulis di bagian pengenalan.

4. *Notebook* harus diupload dalam repositori GitHub Clasroom masing-masing siswa untuk selanjutnya dinilai.

## Assignment Submission

- Simpan assignment pada sesi ini dengan nama `h8dsft_P0W1_<nama-student>.ipynb`, misal `h8dsft_P0W1_raka_ardhi.ipynb`.
- Push Assigment yang telah dibuat ke akun Github masing-masing student.

## Assignment Objectives

*Graded Challenge 1* ini dibuat guna mengevaluasi konsep Basic SQL, Python, serta Data Preparation with Pandas sebagai berikut:

- Mampu memuat data dengan Pandas
- Mampu menangani missing values pada dataset
- Mampu melakukan manipulasi kolom
- Mampu membuat query terhadap dataset
- Mampu melakukan grouping terhadap dataset
- Mampu melakukan visualisasi sederhana menggunakan Pandas

---

## Assignment Rubrics

### Code Review

| Criteria | Meet Expectations | Points |
| --- | --- | --- |
| Data Retrieval | Mampu menarik data dari BigQuery GCP menggunakan SQL | 5 pts |
| Data Loading | Mampu memuat data dengan Pandas | 3 pts |
| Missing Value | Mampu menangani missing values sehingga tidak ada missing values dalam dataset | 5 pts |
| Manipulating Columns | Mampu mengganti nama kolom. Mampu menghapus kolom yang tidak digunakan | 5 pts |
| Data Query | Mampu membuat **minimal 3 query** data | 5 each (total 15 pts) |
| Grouping and Aggregating | Mampu melakukan pengelompokan data **minimal 3 kelompok** | 5 each (total 15 pts) |
| Pandas Visualization | Mampu membuat **minimal 3 plot** dengan Pandas | 5 each (total 15 pts) |
| Apakah Kode Berjalan Tanpa Ada Error? | Kode berjalan tanpa ada error. Seluruh kode berfungsi dan dibuat dengan benar. | 5 pts |

### Readability

| Criteria | Meet Expectations | Points |
| --- | --- | --- |
| Tertata Dengan Baik | Semua baris kode terdokumentasi dengan baik dengan menggunakan Markdown untuk penjelasan kode. | 10 pts |


### Analysis

| Criteria | Meet Expectations | Points |
| --- | --- | --- |
| Problem Statement | Keberadaan problem statement yang akan dibahas | 11 pts |
| Overall Analysis | Menarik informasi/kesimpulan dari keseluruhan eksplorasi data yang dilakukan. | 11 pts |

---

```
Total Points : 100
```
---

## Score Reduction

Pengurangan poin akan diberlakukan jika Student terlambat mengumpulkan tugas yang telah diberikan. Adapun besarnya pengurangan adalah :

| Criteria | Max Points GC1 |
| --- | --- |
| Keterlambatan kurang dari 1 jam setelah deadline | 75 pts (75 %) |
| Keterlambatan lebih dari 1 jam - 1 hari setelah deadline | 50 pts (50 %) |
| Keterlambatan lebih dari 1 hari setelah deadline | 0 pts (0 %) |
