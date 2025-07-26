<!-- badges: start -->
[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/license-MIT-green)](/LICENSE)
<!-- badges: end -->

# Asthma Machine Learning Pipeline

Proyek ini adalah implementasi pipeline machine learning untuk memprediksi penyakit asma menggunakan dataset medis. Pipeline ini mencakup tahap eksplorasi data, rekayasa fitur, pelatihan model, evaluasi, dan penjelasan model menggunakan teknik Machine Learning.

---

## 👨‍💻 Informasi Pengembang

**Nama**: Mohammad Wijdan Arrosyid  
**NIM**: 202210370311497

---

## 🔗 Referensi Pustaka

Pustaka yang digunakan:

- Pandas, Numpy untuk manipulasi data.
- Matplotlib, Seaborn untuk visualisasi.
- Scikit-learn untuk algoritma machine learning.
- SHAP untuk Explainable AI.
- Statsmodels untuk analisis statistik.

---

## 📖 Deskripsi

Pipeline ini dirancang untuk memprediksi penyakit asma berdasarkan dataset yang diberikan. Berikut adalah tahapan yang dilakukan dalam proyek ini:

1. **Instalasi & Import**: Mengimpor pustaka yang diperlukan.
2. **Load Dataset**: Memuat dataset untuk analisis.
3. **Exploratory Data Analysis (EDA)**: Menganalisis data untuk memahami pola dan distribusi.
4. **Feature Engineering (severity scoring)**: Mengolah fitur dan memberi skor keparahan asma.
5. **Ordinal Classification (RandomForest)**: Menggunakan RandomForest untuk klasifikasi tingkat keparahan.
6. **Model Evaluation**: Mengevaluasi model dengan Cross-Validation, ROC-AUC, dan confusion matrix.
7. **Explainable ML**: Menggunakan regresi logistik dan SHAP untuk penjelasan hasil model.
8. **Clustering (KMeans + t-SNE)**: Menerapkan KMeans dan t-SNE untuk visualisasi pola data.
9. **Visualisasi Cluster vs Severity**: Menganalisis hasil clustering dan keparahan asma.
10. **Save Model**: Menyimpan model yang sudah dilatih untuk penggunaan lebih lanjut.

---

## 🗂️ Struktur Direktori
```text
.
├── dataset/               # Berisi asthma_disease_data.csv (dataset penyakit asma)
├── notebooks/             # Berisi asthma_ml_pipeline.ipynb (notebook pipeline ML asma)
├── requirements.txt       # File yang berisi daftar pustaka yang dibutuhkan 
└── README.md              # Dokumentasi proyek ini
