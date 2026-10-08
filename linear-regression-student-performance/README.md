# Prediksi Student Performance Index dengan Linear Regression

Tugas mata kuliah Pembelajaran Mesin — Muhammad Rafa Enrico (TI-3C, POLINES)

## Deskripsi
Membangun model Multiple Linear Regression untuk memprediksi Performance Index siswa berdasarkan jam belajar, nilai sebelumnya, ekstrakurikuler, jam tidur, dan jumlah latihan soal.

## Hasil
| Metrik | Nilai |
|---|---|
| R² | 0,9884 |
| RMSE | 2,08 |
| MAE | 1,65 |
| Rata-rata R² (5-fold CV) | 0,9887 |

Faktor paling berpengaruh: **Previous Scores**, diikuti **Hours Studied**.

## File
- `Student_Performance_Index_LinearRegression.ipynb` — notebook analisis dan pemodelan
- `Student_Performance.csv` — dataset

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn (Google Colab)
