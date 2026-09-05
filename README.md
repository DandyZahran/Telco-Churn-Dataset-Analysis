# Telco-Churn-Dataset-Analysis
Exploratory Data Analysis (EDA) pada Telco Customer Churn untuk mengidentifikasi pola dan faktor yang berkaitan dengan customer churn melalui analisis tenure, layanan internet, jenis kontrak, biaya bulanan, dan metode pembayaran.

# Telco Customer Churn - Exploratory Data Analysis

## Project Overview

Project ini melakukan Exploratory Data Analysis (EDA) pada dataset Telco Customer Churn untuk mengidentifikasi pola dan faktor yang berkaitan dengan customer churn.

Analisis berfokus pada lima variabel utama: tenure, jenis layanan internet, jenis kontrak, monthly charges, dan metode pembayaran.

## Objective

Tujuan analisis ini adalah:

* Memahami karakteristik pelanggan yang melakukan churn.
* Mengidentifikasi pola churn berdasarkan karakteristik layanan dan pelanggan.
* Menganalisis hubungan beberapa variabel dengan customer churn.
* Menghasilkan insight yang dapat menjadi dasar untuk analisis atau pemodelan churn selanjutnya.

## Research Questions

1. Bagaimana lama berlangganan (tenure months) memengaruhi tingkat churn pelanggan?
2. Bagaimana jenis layanan internet memengaruhi tingkat churn pelanggan?
3. Bagaimana jenis kontrak memengaruhi tingkat churn pelanggan?
4. Bagaimana biaya bulanan (monthly charges) memengaruhi tingkat churn pelanggan?
5. Bagaimana metode pembayaran memengaruhi tingkat churn pelanggan?

## Methodology

Analisis dilakukan melalui beberapa tahap:

1. Data Understanding
2. Data Cleaning
3. Exploratory Data Analysis
4. Data Visualization
5. Churn Analysis
6. Insight & Interpretation

## Key Findings

### 1. Tenure dan Customer Churn

Pelanggan dengan lama berlangganan 0-12 bulan memiliki tingkat churn tertinggi. Tingkat churn menurun seiring bertambahnya tenure. Pelanggan dengan tenure 49 bulan atau lebih memiliki tingkat churn yang sangat rendah. Hal ini menunjukkan bahwa periode awal berlangganan merupakan fase penting dalam mempertahankan pelanggan.

### 2. Internet Service dan Customer Churn

Pelanggan pengguna Fiber optic memiliki tingkat churn tertinggi. Sebaliknya, pelanggan tanpa layanan internet memiliki tingkat churn terendah. Temuan ini menunjukkan adanya perbedaan tingkat churn berdasarkan jenis layanan internet yang digunakan.

### 3. Contract dan Customer Churn

Pelanggan dengan kontrak Month-to-month memiliki tingkat churn jauh lebih tinggi dibandingkan kontrak One year dan Two year. Kontrak Two year memiliki tingkat churn terendah. Hal ini menunjukkan adanya hubungan antara durasi kontrak dan tingkat churn pelanggan.

### 4. Monthly Charges dan Customer Churn

Pelanggan dengan biaya bulanan lebih dari 70 memiliki tingkat churn tertinggi. Tingkat churn cenderung lebih rendah pada kelompok dengan biaya bulanan yang lebih rendah. Hal ini menunjukkan adanya hubungan antara biaya bulanan dan tingkat churn.

### 5. Payment Method dan Customer Churn

Pelanggan yang menggunakan Electronic check memiliki tingkat churn tertinggi. Sebaliknya, pelanggan yang menggunakan Bank transfer (automatic) dan Credit card (automatic) memiliki tingkat churn yang lebih rendah. Metode pembayaran dapat menjadi salah satu indikator untuk mengidentifikasi pelanggan dengan risiko churn yang lebih tinggi.

## Overall Insight

Hasil EDA menunjukkan adanya pola customer churn berdasarkan tenure, jenis layanan internet, jenis kontrak, monthly charges, dan metode pembayaran.

Pelanggan dengan tenure rendah, pengguna Fiber optic, kontrak Month-to-month, biaya bulanan tinggi, dan metode pembayaran Electronic check menunjukkan tingkat churn yang lebih tinggi dalam analisis ini.

Temuan ini dapat menjadi dasar untuk analisis lebih lanjut, seperti feature engineering dan pembangunan model prediksi customer churn.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

## Dataset

Dataset yang digunakan adalah Telco Customer Churn, yang berisi informasi mengenai karakteristik pelanggan, layanan yang digunakan, jenis kontrak, metode pembayaran, biaya berlangganan, dan status churn.

## Project Structure

```text
Telco-Customer-Churn-EDA/
│
├── dataset/
│   └── Telco-Customer-Churn.csv
│
├── notebook/
│   └── Telco_Customer_Churn_EDA.ipynb
│
└── README.md
```

## Future Work

Analisis ini dapat dikembangkan ke tahap berikutnya, seperti:

* Feature Engineering
* Feature Selection
* Predictive Modeling
* Model Evaluation
* Hyperparameter Tuning
* Customer Churn Prediction
