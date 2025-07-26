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

1. **Tahap 1** – **Instalasi & Import**  
   Mengimpor pustaka yang diperlukan untuk analisis dan pemodelan.

2. **Tahap 2** – **Load Dataset**  
   Memuat dataset yang berisi data medis yang digunakan untuk analisis lebih lanjut.

3. **Tahap 3** – **Exploratory Data Analysis (EDA)**  
   Melakukan analisis eksplorasi data dengan visualisasi untuk memahami pola dan distribusi dalam data.

4. **Tahap 4** – **Feature Engineering (severity scoring)**  
   Mengolah fitur dari dataset, termasuk memberi skor pada keparahan penyakit asma berdasarkan data.

5. **Tahap 5** – **Ordinal Classification (RandomForest)**  
   Menerapkan model klasifikasi ordinal menggunakan RandomForest untuk memprediksi tingkat keparahan asma.

6. **Tahap 6** – **Model Evaluation**  
   Mengevaluasi model menggunakan metode seperti Cross-Validation, ROC-AUC, dan confusion matrix untuk mengukur kinerja model.

7. **Tahap 7** – **Explainable ML**  
   Menggunakan regresi logistik dan SHAP untuk penjelasan hasil model dan memahami faktor-faktor yang mempengaruhi keputusan model.

8. **Tahap 8** – **Clustering (KMeans + t-SNE)**  
   Menggunakan teknik clustering (KMeans) dan visualisasi (t-SNE) untuk memetakan pola dalam data dan hubungan antar fitur.

9. **Tahap 9** – **Visualisasi Cluster vs Severity**  
   Menganalisis dan memvisualisasikan hasil clustering dengan tingkat keparahan penyakit asma.

10. **Tahap 10** – **Save Model**  
    Menyimpan model yang sudah dilatih untuk digunakan lebih lanjut dalam aplikasi atau analisis lainnya.

---

## 🗂️ Struktur Direktori

