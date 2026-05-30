```markdown
# 📍 K-Means Clustering on GPS Trajectory Data

Projek ini berfokus pada implementasi algoritma **K-Means Clustering** untuk mengelompokkan data trajektori GPS menggunakan dataset `go_track_tracks.csv`. Proses analisis mencakup *data preprocessing*, visualisasi sebaran data, normalisasi fitur dengan *Min-Max Scaling*, hingga evaluasi performa model clustering.

## 🚀 Fitur Utama
* **Data Cleansing**: Menghapus kolom yang tidak relevan (`linha`) untuk mengoptimalkan proses klasterisasi.
* **Feature Selection**: Fokus pada fitur penting yaitu koordinat/jarak dan kecepatan (`distance` & `speed`).
* **Data Normalization**: Transformasi data menggunakan `MinMaxScaler` agar skala antar fitur seimbang.
* **Model Clustering**: Implementasi `KMeans` dari library *scikit-learn* dengan penentuan jumlah klaster ($n\_clusters = 3$).
* **Visualisasi Hasil**: Plot interaktif sebaran data hasil klaster lengkap dengan posisi titik *Centroid* masing-masing klaster.

## 🛠️ Library yang Digunakan
Pastikan library Python berikut sudah terinstal di environment sebelum menjalankan kode:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
