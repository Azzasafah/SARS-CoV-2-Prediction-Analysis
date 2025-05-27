# 🦠 Prediksi Risiko SARS-CoV-2 Menggunakan AI Project Cycle 💡🔬

Proyek ini merupakan implementasi dari siklus proyek kecerdasan buatan (AI Project Cycle) untuk memprediksi risiko infeksi SARS-CoV-2 berdasarkan data gejala dan riwayat pasien. Proyek dilakukan menggunakan **Logistic Regression**, **SMOTE**, serta berbagai metode klasifikasi.

---

## 🚀 AI Project Cycle yang Diterapkan
1. **Problem Scoping**: Prediksi potensi infeksi SARS-CoV-2 berdasarkan data gejala dan riwayat pasien.
2. **Data Acquisition**: Menggunakan dataset gejala COVID-19 yang bersifat kredensial.
3. **Data Exploration**: Analisis distribusi dan korelasi pada atribut seperti gejala, usia, riwayat isolasi, dsb.
4. **Modelling**:
   - Logistic Regression untuk klasifikasi awal.
   - Oversampling dengan **SMOTE** untuk mengatasi data imbalance.
   - Evaluasi dengan berbagai algoritma supervised.
5. **Evaluation**:
   - Model dibandingkan berdasarkan akurasi, F1-score, dan ROC-AUC.

---

## 🛠 Teknologi dan Tools
- Python (Google Colab)
- `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
- Logistic Regression, Support Vector Classifier (SVC), Random Forest, K-Nearest Neighbors (KNN)
- SMOTE (imbalanced-learn)

---

## 🔎 Pembelajaran dan Evaluasi Model
- Menggunakan **confusion matrix** dan **classification report** untuk mengevaluasi model.
- Hasil: Dengan penambahan SMOTE, **Recall** meningkat dari **67% menjadi 91%**, sementara **akurasi** sedikit menurun menjadi **87%**.

---

## ⚖️ Penyeimbangan Data dengan SMOTE
- Data tidak seimbang (misal: mayoritas kelas non-COVID-19).
- SMOTE digunakan untuk memperbaiki distribusi kelas dan meningkatkan performa model.

---

## 🤖 Perbandingan Model Klasifikasi

| Model                              | Akurasi |
|------------------------------------|---------|
| Logistic Regression (Before SMOTE) | 87%     |    
| Logistic Regression (After  SMOTE) | 86%     |


> Random Forest menunjukkan performa terbaik secara keseluruhan.

---

## 📈 Visualisasi
- Plot confusion matrix untuk tiap model
- ROC Curve untuk perbandingan model
- Feature Importance (untuk Random Forest)

---

## 👤 Kontribusi
Proyek ini merupakan kolaborasi. Saya berkontribusi pada:
- Exploratory Data Analysis (EDA)
- Clustering & SMOTE
- Penerapan & evaluasi model klasifikasi
- Visualisasi & dokumentasi

---

## 📁 File yang Tersedia
- `covid_early_stage_symptoms.ipynb`: Dataset
- `README.md`: Dokumentasi proyek

---

## 🌐 Sumber Data
- (https://www.kaggle.com/datasets/martuza/early-stage-symptoms-of-covid19-patients)

---

## 📌 Catatan
- Proyek ini bertujuan sebagai studi analisis data, bukan diagnosis medis.
