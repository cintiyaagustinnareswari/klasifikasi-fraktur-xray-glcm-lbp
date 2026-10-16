# Klasifikasi Fraktur Citra X-ray Menggunakan GLCM, LBP, Feature Fusion, SVM, ANN, dan BNN

## Deskripsi Proyek

Proyek ini membahas perbandingan metode ekstraksi fitur Gray Level Co-occurrence Matrix (GLCM), Local Binary Pattern (LBP), dan Feature Fusion pada klasifikasi patah tulang berdasarkan citra X-ray. Proses klasifikasi dilakukan menggunakan tiga algoritma, yaitu Support Vector Machine (SVM), Artificial Neural Network (ANN), dan Bayesian Neural Network (BNN).

Penelitian ini bertujuan untuk membandingkan performa setiap kombinasi metode ekstraksi fitur dan algoritma klasifikasi dalam mengenali patah tulang pada citra X-ray.

**Proyek ini dibuat untuk memenuhi tugas akademik.**

## Metode yang Digunakan

### 1. Ekstraksi Fitur
- **GLCM (Gray Level Co-occurrence Matrix):** Mengekstraksi fitur tekstur berdasarkan hubungan antarpiksel.
- **LBP (Local Binary Pattern):** Mengekstraksi fitur tekstur berdasarkan pola lokal pada citra.
- **Feature Fusion:** Menggabungkan fitur GLCM dan LBP untuk digunakan dalam proses klasifikasi.

### 2. Algoritma Klasifikasi
- **SVM (Support Vector Machine)**
- **ANN (Artificial Neural Network)**
- **BNN (Bayesian Neural Network)**

### 3. Evaluasi Model

Performa model dievaluasi menggunakan beberapa metrik:
- Accuracy
- Precision
- Recall
- F1-Score

## Dataset

Dataset yang digunakan adalah **Bone Fracture Detection** yang diperoleh dari Kaggle. Setelah proses pembersihan data, penelitian menggunakan 2.060 citra.

## Tahapan Penelitian

1. Pengumpulan dan pembersihan dataset.
2. Preprocessing citra, meliputi resize, konversi grayscale, CLAHE, median blur, dan Gaussian blur.
3. Ekstraksi fitur menggunakan GLCM, LBP, dan Feature Fusion.
4. Klasifikasi menggunakan SVM, ANN, dan BNN.
5. Evaluasi dan perbandingan performa model.

## Hasil

Berdasarkan hasil yang dilaporkan dalam penelitian, kombinasi **Feature Fusion dan ANN** memperoleh performa terbaik dengan hasil sebagai berikut:

| Metrik | Nilai |
|---|---:|
| Accuracy | 72,29% |
| Precision | 75,80% |
| Recall | 72,29% |
| F1-Score | 71,72% |

Hasil tersebut menunjukkan performa model pada eksperimen yang dilakukan dalam penelitian ini.

## Teknologi

Proyek ini berfokus pada pengolahan citra, ekstraksi fitur, dan klasifikasi menggunakan metode machine learning.

## Tujuan Akademik

Repository ini disusun sebagai dokumentasi kode dan hasil eksperimen untuk keperluan tugas akademik. Proyek ini juga menjadi sarana pembelajaran mengenai penerapan ekstraksi fitur dan algoritma klasifikasi pada citra medis.

## Penulis

- Nadine Putri Aulia
- Umi Imro’atus Sholekhah
- Cintiya Agustin Nareswari

Universitas Negeri Surabaya
