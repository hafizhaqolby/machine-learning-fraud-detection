# machine-learning-fraud-detection

Proyek ini bertujuan untuk membangun model Clustering dan Classification untuk menganalisis transaksi perbankan dan mendeteksi pola yang dapat digunakan untuk klasifikasi. <br>

## 📂 Struktur Folder
```
│-- [Clustering] Submission Akhir BMLP_Hafizha Nurul Qolby.ipynb
│-- [Klasifikasi] Submission Akhir BMLP_Hafizha Nurul Qolby.ipynb
│-- bank_transaction_data_2.csv
│-- clustered_data.csv
│-- classification_data.csv
```

## 🔍 1. Clustering dengan K-Means
- Clustering digunakan untuk mengelompokkan pelanggan berdasarkan pola transaksi mereka.
- Algoritma: K-Means
- Evaluasi Model: Menggunakan Elbow Method dan Silhouette Score
- Output: Dataset_clustering.csv, yang digunakan sebagai input untuk klasifikasi.

## 🔍 2. Klasifikasi dengan Random Forest
- Setelah clustering, hasilnya digunakan sebagai label untuk membangun model klasifikasi.
- Algoritma: Random Forest
- Metode Tuning: GridSearchCV untuk mencari parameter terbaik. <br>
### Evaluasi Model:
- Sebelum tuning: Akurasi = 100%
- Setelah tuning: Akurasi tetap 100%
  
## 📊 **Evaluation Results**
| Model | Accuracy | Precision | Recall | F1-Score |
|--------|----------|------------|---------|----------|
| Random Forest (Before Tuning) | 100% | 1.00 | 1.00 | 1.00 |
| Random Forest (After Tuning) | 100% | 1.00 | 1.00 | 1.00 |

## 🚀 Rekomendasi Pengembangan
- Coba algoritma lain: Misalnya, XGBoost atau Neural Network untuk meningkatkan performa model.
- Feature Engineering: Menambah fitur baru dari data transaksi untuk meningkatkan akurasi model.
- Tambahkan lebih banyak data: Dataset yang lebih besar bisa membantu meningkatkan generalisasi model.
