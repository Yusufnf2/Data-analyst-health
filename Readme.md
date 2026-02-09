# Stroke Risk Analysis Using Healthcare Data
Proyek ini berfokus pada analisis data kesehatan untuk mengidentifikasi faktor-faktor yang berkontribusi terhadap risiko stroke pada pasien. Melalui eksplorasi data, visualisasi, dan pemodelan prediktif, proyek ini menunjukkan bagaimana data dapat digunakan untuk mendukung pengambilan keputusan di bidang kesehatan.

## Tujuan Proyek
Tujuan utama dari proyek ini adalah:
* Mengidentifikasi faktor kesehatan dan demografis yang berhubungan dengan risiko stroke
* Melakukan eksplorasi data untuk menemukan pola dan insight penting
* Membangun model prediktif untuk memperkirakan kemungkinan seseorang terkena stroke
* Menyajikan hasil analisis dalam bentuk visualisasi yang mudah dipahami

 Proyek ini dirancang untuk menunjukkan kemampuan analisis data end-to-end, mulai dari data mentah hingga insight yang dapat ditindaklanjuti.

## Dataset
Dataset yang digunakan berisi informasi kesehatan pasien, termasuk:
* Data demografis (usia, jenis kelamin, status pernikahan, dll.)
* Riwayat penyakit (hipertensi, penyakit jantung)
* Gaya hidup (status merokok, tipe pekerjaan)
* Indikator kesehatan (BMI, kadar glukosa rata-rata)
* Label target: apakah pasien pernah mengalami stroke atau tidak

Data ini digunakan untuk memahami hubungan antara kondisi kesehatan dan risiko stroke.

## Tools & Teknologi
Beberapa tools dan library yang digunakan dalam proyek ini:
* Python
* Pandas – manipulasi dan pembersihan data
* NumPy – komputasi numerik
* Matplotlib & Seaborn – visualisasi data
* Scikit-learn – preprocessing dan pemodelan machine learning
* Jupyter Notebook – environment analisis

## Tahapan Analisis
1. Data Cleaning & Preprocessing
* Menangani missing values
* Encoding variabel kategorikal
* Normalisasi / standarisasi fitur numerik
* Deteksi dan penanganan outlier
  
2. Exploratory Data Analysis (EDA)
Dilakukan untuk memahami distribusi data dan hubungan antar variabel, seperti:
* Distribusi usia terhadap kasus stroke
* Hubungan hipertensi dan penyakit jantung dengan stroke
* Pengaruh kadar glukosa dan BMI terhadap risiko stroke
* Perbandingan risiko berdasarkan gender dan status merokok

Visualisasi digunakan secara intensif untuk memperjelas pola dalam data.

4. Feature Engineering
* Seleksi fitur yang paling relevan terhadap target
* Transformasi variabel untuk meningkatkan performa model

5. Modeling
Algoritma machine learning yang digunakan yaitu Decision Tree.

Model dilatih untuk memprediksi kemungkinan pasien mengalami stroke berdasarkan data kesehatannya.

6. Evaluasi Model
Model dievaluasi menggunakan metrik seperti:
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Fokus utama adalah kemampuan model dalam mendeteksi pasien berisiko tinggi (recall pada kelas stroke).

## Insight Utama
Beberapa insight penting yang diperoleh dari analisis:
* Usia merupakan salah satu faktor risiko paling signifikan
* Pasien dengan hipertensi dan penyakit jantung memiliki kemungkinan stroke yang lebih tinggi
* Kadar glukosa yang tinggi berkorelasi dengan peningkatan risiko stroke
* Gaya hidup dan kondisi kesehatan jangka panjang berperan besar dalam risiko

Insight ini menunjukkan pentingnya deteksi dini dan pengelolaan penyakit kronis untuk mencegah stroke.

## Dampak & Relevansi Bisnis/Kesehatan
Hasil analisis dan model prediktif ini dapat digunakan untuk:
* Membantu tenaga medis dalam identifikasi pasien berisiko tinggi
* Mendukung program pencegahan dan intervensi dini
* Menjadi dasar pengembangan sistem pendukung keputusan (decision support system) di bidang kesehatan

## Pengembangan Selanjutnya
Beberapa pengembangan yang dapat dilakukan:
* Hyperparameter tuning untuk meningkatkan performa model
* Menangani class imbalance dengan teknik seperti SMOTE
* Deployment model ke dalam bentuk web app atau API
* Penambahan interpretabilitas model (SHAP / feature importance lanjutan)
  
## Tentang Saya
Proyek ini merupakan bagian dari portofolio saya sebagai Data Analyst yang berfokus pada:
* Data cleaning & preprocessing
* Exploratory Data Analysis
* Data visualization
* Machine learning dasar untuk analisis prediktif

Saya tertarik menggunakan data untuk menghasilkan insight yang berdampak dan mendukung pengambilan keputusan berbasis data.

