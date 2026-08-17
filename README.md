# Data Science 2026 — Nazarul Bagus Riyadi

**Nama Lengkap**    : Nazarul Bagus Riyadi

**NIM**             : 240401010229

**Kelas**           : IF404

**Prodi**           : PJJ Informatika

**Dosen**           : Syahid Abdullah, S.Si., M.Kom.

---

## Perkenalan

Saya Nazarul Bagus Riyadi, mahasiswa PJJ Informatika angkatan 2024. Repository ini merupakan portofolio hasil praktikum **Pengantar Data Science** (kode: 200302305) yang mendokumentasikan perjalanan belajar saya dari Pertemuan 1 hingga Pertemuan 10.

Tujuan belajar Data Science bagi saya adalah memahami alur kerja seorang data practitioner — mulai dari eksplorasi data, pembersihan, analisis statistik, visualisasi, persiapan data untuk machine learning, hingga membangun model prediksi (regresi dan klasifikasi). Setiap notebook merekam proses berpikir, kode, output, dan refleksi pembelajaran.

Di dalam repository ini terdapat 9 notebook hands-on yang mencakup: pengenalan Python untuk data science, manipulasi data dengan Pandas & NumPy, data cleaning, statistika deskriptif, visualisasi, preprocessing ML, regresi linear, klasifikasi dasar, serta ensemble dan data imbalanced. Dataset pendukung (misalnya `housing_dirty.csv` untuk Pertemuan 3) tersedia di repository terpisah: [data-science-source](https://github.com/arulriyadi/data-science-source).

---

## Daftar Notebook

| No | Pertemuan | Topik | Link Notebook |
|----|-----------|-------|---------------|
| 1 | Pertemuan 1 | Pengenalan Data Science | [Buka Notebook](Pertemuan1_NazarulBagusRiyadi_240401010229.ipynb) |
| 2 | Pertemuan 2 | Struktur Data Python, NumPy & Pandas | [Buka Notebook](Pertemuan2_NazarulBagusRiyadi_240401010229.ipynb) |
| 3 | Pertemuan 3 | Data Cleaning: Missing Values, Outlier & Ekstraksi Data | [Buka Notebook](Pertemuan3_NazarulBagusRiyadi_240401010229.ipynb) |
| 4 | Pertemuan 4 | Statistika Dasar & Analisis Data | [Buka Notebook](Pertemuan4_NazarulBagusRiyadi_240401010229.ipynb) |
| 5 | Pertemuan 5 | Visualisasi Data | [Buka Notebook](Pertemuan5_NazarulBagusRiyadi_240401010229.ipynb) |
| 6 | Pertemuan 6 | Persiapan Data (Preprocessing ML) | [Buka Notebook](Pertemuan6_NazarulBagusRiyadi_240401010229.ipynb) |
| 7 | Pertemuan 7 | Pengantar Machine Learning: Regresi Linear | [Buka Notebook](Pertemuan7_NazarulBagusRiyadi_240401010229.ipynb) |
| 8 | Pertemuan 9 | Algoritma Klasifikasi (Bagian 1): Logistic Regression, Decision Tree, Confusion Matrix, Accuracy, Precision, Recall, F1-Score | [Buka Notebook](Pertemuan9_NazarulBagusRiyadi_240401010229.ipynb) |
| 9 | Pertemuan 10 | Algoritma Klasifikasi (Bagian 2): Random Forest, Imbalanced Dataset, Customer Churn | [Buka Notebook](Pertemuan10_NazarulBagusRiyadi_240401010229.ipynb) |

---

## Dataset & Sumber Data

| Sumber | Digunakan di | Link |
|--------|--------------|------|
| Dataset housing (data kotor) | Pertemuan 3 | [data-science-source](https://github.com/arulriyadi/data-science-source) |
| Titanic, Iris, Tips | P2, P4, P5, P6 | Seaborn / URL publik (di dalam notebook) |
| Dataset sintetis gaji | Pertemuan 7 | Digenerate di notebook |
| Breast Cancer Wisconsin | Pertemuan 9 | `sklearn.datasets.load_breast_cancer()` |
| Telco Customer Churn | Pertemuan 10 | URL publik IBM (di dalam notebook) |

---

## Tools & Library

| Kategori | Tools / Library |
|----------|----------------|
| Bahasa | Python 3 |
| Manipulasi Data | Pandas, NumPy |
| Visualisasi | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Statistik | SciPy |
| Lingkungan | Google Colab, Jupyter Notebook |
| Version Control | Git & GitHub |

---

## Cara Menjalankan

### Via Google Colab

1. Buka [Google Colab](https://colab.research.google.com)
2. Tab **GitHub** → tempel URL: `https://github.com/arulriyadi/data-science-2026`
3. Pilih notebook yang ingin dibuka
4. **Runtime → Restart & Run All**

### Via Lokal

```bash
git clone https://github.com/arulriyadi/data-science-2026.git
cd data-science-2026
pip install pandas numpy matplotlib seaborn scikit-learn scipy requests jupyter
jupyter notebook
```

---

## Kesimpulan Perjalanan Belajar (Pertemuan 1–10)

Sepanjang pertemuan ini, saya mempelajari alur kerja Data Science secara bertahap:

1. **Pertemuan 1–2** — Fondasi Python, Pandas, dan NumPy untuk membaca serta mengeksplorasi data tabular (dataset Titanic).
2. **Pertemuan 3** — Data cleaning end-to-end: menghapus duplikat, imputasi missing values, menangani outlier dengan IQR, dan ekstraksi data dari REST API.
3. **Pertemuan 4** — Statistika deskriptif dan analisis univariat/bivariat pada dataset Iris, termasuk korelasi dan distribusi antar fitur.
4. **Pertemuan 5** — Visualisasi data dengan dashboard 6 grafik pada dataset Tips, menggunakan framework What–So what–Now what.
5. **Pertemuan 6** — Preprocessing untuk ML: imputasi, encoding, stratified split, dan feature scaling tanpa data leakage.
6. **Pertemuan 7** — Membangun dan mengevaluasi model Regresi Linear (MAE, RMSE, R²) dengan visualisasi residual.
7. **Pertemuan 9** — Klasifikasi biner pada Breast Cancer Wisconsin: membandingkan Logistic Regression dan Decision Tree memakai Confusion Matrix, Accuracy, Precision, Recall, dan F1-Score. Recall kelas ganas diprioritaskan karena False Negative berarti kanker terlewat.
8. **Pertemuan 10** — Random Forest pada Telco Customer Churn (26.5% churn). Accuracy paradox: di threshold 0.5 kedua model ~0.79 Accuracy, tetapi Recall churn baru naik ke 0.671 setelah threshold diturunkan ke 0.35.

**Temuan utama:** Data Science bukan sekadar menjalankan kode — setiap tahap (eksplorasi → cleaning → analisis → visualisasi → modeling) saling terkait dan urutannya penting. Metrik evaluasi harus dipilih sesuai konteks: Recall untuk diagnosis medis, Recall/F1 kelas minoritas untuk churn — Accuracy saja bisa menyesatkan.

**Keterbatasan & langkah selanjutnya:** Dataset masih contoh publik. Pertemuan 11–13 akan menambah clustering, asosiasi/rekomendasi, serta dasar deep learning dan NLP.

---

*Praktikum Data Science — Semester 4, 2026*
