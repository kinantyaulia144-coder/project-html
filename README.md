# Analisis Regresi Linear: Pengeluaran vs Jumlah Penduduk Kota Palu (BPS)

Proyek analisis data menggunakan Python untuk memenuhi tugas mata kuliah Statistika & Probabilitas. Proyek ini menerapkan metode regresi linear sederhana untuk memodelkan hubungan antara demografi (Jumlah Penduduk) dan ekonomi (Pengeluaran Bukan Makanan) di Kota Palu, Sulawesi Tengah.

---

## 📌 Deskripsi Proyek
Proyek ini menguji sejauh mana perubahan jumlah penduduk (dalam ribu jiwa) memengaruhi pengeluaran per kapita per bulan untuk kebutuhan bukan makanan di Kota Palu. Data historis yang digunakan mencakup rentang waktu tahun 2017 hingga 2025 bersumber dari Badan Pusat Statistik (BPS).

## 📊 Dataset
Data yang dianalisis merupakan data resmi BPS dengan rincian variabel sebagai berikut:
* **Variabel Independen (X):** Jumlah Penduduk (ribu jiwa)
* **Variabel Dependen (Y):** Pengeluaran Bukan Makanan (Rp/kapita/bulan)

## 🛠️ Alur Analisis (Workflow)
Di dalam Jupyter Notebook (`analisis pengeluaran.ipynb`), seluruh kode diatur ke dalam 6 tahapan utama:
1. Load Data: Inisialisasi data historis BPS Kota Palu (2017-2025) ke dalam DataFrame Pandas.
2. Model Regresi Linear: Fitting data menggunakan `LinearRegression` dari `scikit-learn`.
3. Evaluasi Model: Menghitung metrik performa model berupa Koefisien Determinasi (R²) dan Root Mean Squared Error (RMSE).
4. Prediksi Data Baru: Memprediksi nilai pengeluaran masa depan berdasarkan skenario jumlah penduduk (390 ribu, 395 ribu, dan 400 ribu jiwa).
5. Visualisasi Hasil: Membuat diagram dua panel (Scatter Plot + Garis Regresi & Diagram Batang).
6. Interpretasi & Kesimpulan: Menarik insight praktis dari output statistik yang dihasilkan model.

## 📈 Struktur Folder Proyek
