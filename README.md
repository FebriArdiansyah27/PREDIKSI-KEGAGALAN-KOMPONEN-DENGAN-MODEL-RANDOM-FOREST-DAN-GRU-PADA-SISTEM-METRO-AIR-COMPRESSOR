# PREDIKSI-KEGAGALAN-KOMPONEN-DENGAN-MODEL-RANDOM-FOREST-DAN-GRU-PADA-SISTEM-METRO-AIR-COMPRESSOR

# Prediksi Kegagalan Komponen pada Sistem Metro Air Compressor
Penelitian ini mengembangkan model prediksi kegagalan komponen pada sistem Metro Air Compressor menggunakan dua algoritma machine learning, yaitu Random Forest (RF) dan Gated Recurrent Unit (GRU). Dataset yang digunakan dalam penelitian ini diambil dari Kaggle, berisi laporan kegagalan peralatan industri dan data sensor yang relevan.

## Model yang Digunakan
Random Forest (RF)
Random Forest adalah algoritma ensemble yang diperkenalkan oleh Breiman pada tahun 2001. Algoritma ini menggabungkan hasil dari beberapa pohon keputusan untuk meningkatkan akurasi prediksi dan mengurangi overfitting.

## Gated Recurrent Unit (GRU)
GRU adalah jenis jaringan saraf berulang (Recurrent Neural Network, RNN) yang diperkenalkan oleh Cho et al. pada tahun 2014. GRU memiliki mekanisme gating yang memungkinkan model untuk menyimpan dan melupakan informasi secara adaptif, yang membuatnya cocok untuk pemrosesan data sekuensial.

## Persyaratan
Sebelum menjalankan kode, pastikan Anda telah menginstal beberapa pustaka Python yang diperlukan:

pandas

numpy

scikit-learn

tensorflow

keras

matplotlib

Anda dapat menginstal pustaka-pustaka tersebut menggunakan pip:


pip install pandas numpy scikit-learn tensorflow keras matplotlib
Struktur Direktori
Pastikan struktur direktori Anda sesuai dengan berikut ini:

├── MetroPT3(AirCompressor).csv
│  
├── model.py
│  
└── README.md
## Langkah-langkah Menjalankan Kode

1. import semua file sesuai dengan struktur yang telah diberikan 
2. jalankan kode berikut:


python model.py



Kesimpulan
File README ini menjelaskan tujuan dari penelitian, model yang digunakan, persyaratan yang diperlukan, serta langkah-langkah untuk menjalankan kode. Dengan mengikuti panduan ini, Anda dapat mereplikasi eksperimen dan memprediksi kegagalan komponen pada sistem Metro Air Compressor menggunakan model Random Forest dan GRU.
