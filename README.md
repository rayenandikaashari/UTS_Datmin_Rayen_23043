# 🚗 Used Cars Price Prediction - UTS Data Mining

Proyek ini ditujukan buat **UTS Praktikum Data Mining** oleh saya **Rayen Andika Ashari (5A Informatika)**.  
Tujuan proyek ini adalah untuk melakukan **analisis dan prediksi harga mobil bekas** berdasarkan berbagai fitur seperti tahun, jarak tempuh, merek, dll.

---

## 📊 Deskripsi Singkat

Dataset yang digunakan adalah **Used Cars Price Prediction**
Isi dari Google Colab saya :

1. **Data Profiling dan Preparation**  
   - Memuat dataset dan melihat struktur datanya (`.info()`, `.describe()`)
   - Menangani nilai *missing* dan duplikasi
   - Menghapus kolom ID yang tidak relevan
   - Menstandarkan data numerik menggunakan `StandardScaler`
   - Melakukan *feature selection* dengan metode `VarianceThreshold`

2. **Exploratory Data Analysis (EDA)**  
   - Menampilkan distribusi fitur numerik menggunakan histogram  
   - Analisis korelasi antar variabel dengan *heatmap*  
   - Identifikasi pola dan hubungan antar fitur

3. **Modeling (Prediksi Harga Mobil)**  
   - Menggunakan model **Linear Regression**
   - Split data menjadi *train* dan *test set*
   - Evaluasi model menggunakan metrik:
     - `Mean Squared Error (MSE)`
     - `Mean Absolute Error (MAE)`
     - `R² Score`