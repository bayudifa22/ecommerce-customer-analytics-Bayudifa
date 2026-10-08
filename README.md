# Machine Learning - E-Commerce Customer Analytics

## Deskripsi

Project ini merupakan implementasi Machine Learning menggunakan dataset E-Commerce Sales Customer Analytics.

Tujuan dari project ini adalah memprediksi apakah seorang customer merupakan repeat customer berdasarkan data transaksi dan karakteristik customer.

## Dataset

Nama dataset:

E-Commerce Sales Customer Analytics

Dataset yang digunakan dalam project ini diperoleh dengan mengunduh dataset dari Kaggle:

E-Commerce Sales and Customer Analytics - Kaggle

File dataset yang digunakan:

ecommerce_sales_customer_analytics_150k.csv

Jumlah data:

138.116 baris

Jumlah kolom:

46 kolom

Target:

`is_repeat_customer`

## Jenis Machine Learning

Project ini menggunakan:

**Binary Classification**

Karena target `is_repeat_customer` memiliki dua kategori.

## Tahapan

Tahapan yang dilakukan dalam project:

1. Import Library
2. Load Dataset
3. Data Understanding
4. Data Cleaning
5. Missing Value Analysis
6. Duplicate Data
7. Exploratory Data Analysis
8. Feature Selection
9. Feature Engineering
10. Train Test Split
11. Data Preprocessing
12. Modeling
13. Model Evaluation
14. Confusion Matrix
15. Cross Validation
16. Kesimpulan

## Algoritma

Model yang digunakan:

- Logistic Regression
- Decision Tree
- Random Forest

## Evaluasi

Metrik evaluasi:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Cross Validation

## Struktur Repository

```text
ML/
│
├── data/
│   └── ecommerce_sales_customer_analytics_150k.csv
│
├── ML_Bayu_Difa.ipynb
├── README.md
└── .gitignore

