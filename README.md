# Beverage-Customer-Clustering-and-Prediction

# 🧠 BMLP Portfolio – Machine Learning Projects

Repository ini berisi dua proyek akhir dari Bangkit Machine Learning Path (BMLP) 2024 yang terdiri dari:

1. **Klasifikasi** hasil clustering data minuman
2. **Clustering** untuk segmentasi pelanggan berbasis transaksi

Link Google Drive terkait proyek: [Drive Folder](https://drive.google.com/drive/u/1/folders/1RQdd7YsCW3fVv5vX52LY3ZWs6RhwPdmk)

---

## 📁 1. Klasifikasi: Prediksi Klaster Pelanggan

**Notebook:** `[Klasifikasi]_Submission_Akhir_BMLP_Alif_Fauzan29.ipynb`

### 📌 Deskripsi
Proyek ini bertujuan untuk mengklasifikasikan pelanggan ke dalam klaster yang telah dihasilkan dari proses clustering sebelumnya. Dataset yang digunakan merupakan data transaksi minuman yang telah melalui proses clustering dan memiliki kolom `Cluster_KMeans` sebagai target.

### 🔍 Langkah Utama
- Memuat dataset hasil clustering (`hasil_clustering_beverage.csv`)
- Memilih fitur numerik seperti `Unit_Price`, `Quantity`, `Discount`, `Total_Price`, dan `Price_per_Unit`
- Melakukan splitting data ke dalam train-test set
- Melatih model klasifikasi seperti **Random Forest**, **Decision Tree**, dan **XGBoost**
- Evaluasi performa menggunakan **accuracy** dan **F1-score**
- Pemilihan model terbaik berdasarkan skor tertinggi

### 📈 Hasil
Model **XGBoost** menunjukkan performa terbaik dengan akurasi dan F1-score yang unggul dibanding model lain.

---

## 📁 2. Clustering: Segmentasi Pelanggan

**Notebook:** `[Clustering]_Submission_Akhir_BMLP_Alif_Fauzan29.ipynb`

### 📌 Deskripsi
Tujuan dari proyek ini adalah melakukan segmentasi pelanggan dari dataset transaksi penjualan minuman yang diperoleh dari Kaggle. Dataset berisi campuran data numerik dan kategorikal.

### 🔍 Langkah Utama
- Pemrosesan data termasuk encoding, normalisasi (MinMaxScaler), dan handling missing values
- Clustering dengan berbagai metode: **K-Means**, **DBSCAN**, **Agglomerative Clustering**, dan **Gaussian Mixture**
- Evaluasi performa dengan **Silhouette Score**
- Visualisasi hasil clustering menggunakan PCA
- Analisis dan interpretasi tiap klaster

### 📈 Hasil
Clustering berhasil mengelompokkan pelanggan ke dalam beberapa segmen yang berbeda, di mana model **K-Means** memberikan Silhouette Score tertinggi.

---

## 🛠 Tools & Library yang Digunakan

- Python
- Pandas, NumPy
- Scikit-Learn
- Matplotlib, Seaborn
- XGBoost
- PCA, Clustering methods (KMeans, DBSCAN, dsb.)

---

## ✍️ Catatan Tambahan

Kedua proyek ini mencerminkan pemahaman saya dalam menerapkan supervised dan unsupervised learning, serta bagaimana mengintegrasikan keduanya (clustering + classification). Seluruh tahapan dilakukan dengan Python dan pustaka open-source, menunjukkan kemampuan end-to-end dalam pipeline data science.

