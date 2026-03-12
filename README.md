# 🏦 Prediksi Kemampuan Bayar Hutang Nasabah Bank (Bank Loan Default Prediction)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

Proyek *Data Mining* dan *Machine Learning* untuk memprediksi kemampuan nasabah bank dalam membayar hutang (kredit) menggunakan algoritma klasifikasi **Decision Tree**. 

Proyek ini merupakan implementasi teknis untuk tugas akademik Program Studi Teknik Informatika, **Universitas Komputer Indonesia (UNIKOM)**.

---

## 📖 Latar Belakang
Dalam industri perbankan, analisis risiko kredit adalah salah satu proses paling krusial. Memberikan pinjaman kepada nasabah yang memiliki risiko gagal bayar tinggi dapat menyebabkan kerugian finansial yang signifikan bagi bank. 

Proyek ini bertujuan untuk membangun model prediktif berbasis kecerdasan buatan yang dapat secara otomatis mengklasifikasikan apakah seorang nasabah mampu membayar hutangnya atau tidak, berdasarkan data historis dan profil demografi/finansial mereka.

## ✨ Alur Pemrosesan Data (Pipeline)
Proyek ini dibangun dengan *pipeline data engineering* dan pemodelan yang terstruktur:
- **🧹 Data Cleaning**: Penanganan data yang kotor dengan menghapus baris kosong (`NaN`) untuk menjaga integritas *dataset*.
- **✂️ Feature Selection**: Melakukan transformasi fitur dengan menghapus kolom-kolom yang tidak relevan (seperti ID Nasabah) agar tidak mengganggu pola *Machine Learning*.
- **🔄 Categorical Encoding**: Mengonversi data kategorikal (teks) menjadi representasi numerik agar dapat diproses oleh algoritma matematis.
- **📏 Normalisasi Data**: Menerapkan metode **Min-Max Scaling** untuk menstandarkan rentang nilai antar fitur, sehingga mengoptimalkan distribusi data sebelum proses *training*.
- **🌳 Pemodelan Decision Tree**: Membagi dataset menjadi *Training Set* dan *Testing Set*, lalu melatih model klasifikasi menggunakan algoritma pohon keputusan dari pustaka Scikit-Learn.

## 🛠️ Teknologi & Library yang Digunakan
- **Bahasa Pemrograman**: Python 3.x
- **Environment**: Jupyter Notebook (`.ipynb`)
- **Machine Learning**: Scikit-Learn (`sklearn.tree.DecisionTreeClassifier`)
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib / Seaborn

## 🚀 Cara Menjalankan Proyek

1. **Clone repositori ini (atau unduh file repositori):**
   ```bash
   git clone [https://github.com/username-anda/bank-loan-prediction.git](https://github.com/username-anda/bank-loan-prediction.git)
   cd bank-loan-prediction
2. **Pastikan library yang dibutuhkan sudah terinstall:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib jupyter
4. **Buka Jupyter Notebook di terminal/CMD:**
   ```bash
   jupyter notebook
6. **Jalankan File Notebook:**
   ```bash
   Buka file IF1-DecisionTree-10122119.ipynb di browser Anda dan jalankan sel (cell) kodenya secara berurutan.

##📄 Dokumentasi Lengkap
Detail analisis, statistik deskriptif dataset, serta evaluasi performa model (Akurasi, Precision, Recall) dapat dilihat secara komprehensif pada file laporan PDF yang dilampirkan di repositori ini:
👉 IF1-DecisionTree-10122119.pdf

##👨‍💻 Penulis
- Raditya Nalendra Utomo
- NIM: 10122119
- Kelas: IF-1 / Teknik Informatika
- Universitas Komputer Indonesia (UNIKOM)
   
