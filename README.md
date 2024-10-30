# Proyek Clustering dan Classification Harga Saham

Proyek ini melakukan analisis clustering dan classification pada data harga saham.

## Dataset

Data harga saham diambil dari Yahoo Finance menggunakan library yfinance. Saham yang dianalisis meliputi: AAPL, GOOGL, MSFT, AMZN, FB, TSLA, NVDA, JPM, V, JNJ.

## Clustering

### Langkah-langkah
1. Import Library
2. Memuat Dataset Harga Saham
3. Pra-pemrosesan Data
   - Menghitung returns
   - Menghitung indikator teknikal (SMA, RSI)
4. Normalisasi Fitur
5. Pemodelan Clustering menggunakan K-means
6. Evaluasi Model Clustering
   - Menentukan jumlah cluster optimal dengan silhouette score
7. Visualisasi Hasil Clustering menggunakan PCA
8. Analisis Cluster

Detail implementasi dapat dilihat di [stock_clustering.py](stock_clustering.py)

## Classification

### Langkah-langkah
1. Memuat Data Hasil Clustering
2. Pembagian Data (Train/Test Split)
3. Pembangunan Model Klasifikasi
   - Random Forest
   - Support Vector Machine (SVM)
4. Tuning Hyperparameter menggunakan GridSearchCV
5. Evaluasi Model
6. Analisis Fitur Penting

Detail implementasi dapat dilihat di [stock_classification.py](stock_classification.py)

### Hasil Klasifikasi
Hasil evaluasi model sebelum dan sesudah tuning dapat dilihat dalam output program.

## Kesimpulan

[Tambahkan kesimpulan dan insight dari analisis Anda di sini]

## Penggunaan

1. Install dependencies:
