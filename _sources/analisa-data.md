# Analisa Data

## 1. Analisa Prediksi Tentang Apa?

Analisis prediksi dilakukan untuk memperkirakan **permintaan listrik (Demand)** di wilayah Victoria, Australia. Prediksi dilakukan menggunakan metode *time series forecasting* dengan memanfaatkan data historis permintaan listrik serta data suhu (*Temperature*) sebagai variabel eksternal (*exogenous variable*).

Model yang digunakan adalah **LightGBM Regressor (LGBMRegressor)** yang diimplementasikan melalui **ForecasterRecursive** dari library Skforecast.

---

## 2. Bagaimana Bentuk Data Trainingnya (Input dan Output)?

### Input (X)

Data masukan (*input features*) terdiri dari:

- `lag_1` : nilai Demand 1 hari sebelumnya
- `lag_2` : nilai Demand 2 hari sebelumnya
- `lag_3` : nilai Demand 3 hari sebelumnya
- `lag_4` : nilai Demand 4 hari sebelumnya
- `lag_5` : nilai Demand 5 hari sebelumnya
- `lag_6` : nilai Demand 6 hari sebelumnya
- `lag_7` : nilai Demand 7 hari sebelumnya
- `Temperature` : suhu rata-rata harian

### Output (y)

Data keluaran (*target variable*) adalah:

- `Demand` pada hari yang akan diprediksi.

Dengan demikian, model mempelajari hubungan antara nilai permintaan listrik pada beberapa hari sebelumnya dan suhu terhadap permintaan listrik pada hari berikutnya.

<br>

![alt text](image-48.png)

<br>

---

## 3. Apa Itu Lag?

*Lag* adalah nilai historis dari suatu variabel pada periode sebelumnya yang digunakan sebagai fitur dalam proses prediksi.

Contoh:

- `lag_1` menunjukkan nilai Demand satu hari sebelumnya.
- `lag_2` menunjukkan nilai Demand dua hari sebelumnya.
- `lag_7` menunjukkan nilai Demand tujuh hari sebelumnya.

Penggunaan lag bertujuan untuk membantu model mengenali pola dan ketergantungan waktu (*temporal dependency*) pada data deret waktu (*time series*).

---

## 4. Jelaskan Proses Analisis yang Dilakukan

Tahapan analisis yang dilakukan adalah sebagai berikut:

1. Mengambil dataset **vic_electricity** yang berisi data permintaan listrik dan suhu di Victoria, Australia.
2. Melakukan agregasi data menjadi frekuensi harian (*daily frequency*).
3. Membagi data menjadi data latih (*training set*) dan data uji (*testing set*).
4. Membuat fitur lag sebanyak 7 periode (`lag_1` sampai `lag_7`).
5. Menambahkan variabel suhu (*Temperature*) sebagai variabel eksternal.
6. Melatih model menggunakan **LGBMRegressor** dengan metode **ForecasterRecursive**.
7. Menghitung **Feature Importance** untuk mengetahui fitur yang paling berpengaruh terhadap prediksi.

<br>

![alt text](image-49.png)

<br>

8. Melakukan analisis **SHAP (SHapley Additive exPlanations)** untuk menjelaskan kontribusi masing-masing fitur terhadap hasil prediksi.

<br>

![alt text](image-50.png)

<br>

9. Membuat **SHAP Dependence Plot** untuk melihat hubungan antara fitur dan nilai prediksi.

<br>

![alt text](image-51.png)

<br>

10. Menghitung **Permutation Importance** sebagai metode alternatif untuk mengukur pentingnya fitur.

<br>

![alt text](image-52.png)

<br>

11. Membuat **Partial Dependence Plot (PDP)** untuk memahami pengaruh perubahan suatu fitur terhadap hasil prediksi.

<br>

![alt text](image-53.png)

<br>

12. Melakukan prediksi permintaan listrik untuk beberapa periode ke depan.

---

## Hasil Analisis

Berdasarkan hasil **Feature Importance**, **Permutation Importance**, dan **SHAP Analysis**, diperoleh beberapa temuan sebagai berikut:

1. Fitur **lag_1** merupakan fitur yang memiliki pengaruh paling besar terhadap hasil prediksi.
2. Variabel **Temperature** menjadi faktor kedua yang paling berpengaruh dalam menentukan nilai permintaan listrik.
3. Fitur **lag_7** juga memberikan kontribusi yang cukup signifikan terhadap model.
4. Nilai permintaan listrik pada hari sebelumnya memiliki hubungan positif terhadap hasil prediksi permintaan listrik pada hari berikutnya.
5. Hubungan antara suhu dan permintaan listrik bersifat non-linier, yang terlihat dari grafik SHAP Dependence Plot dan Partial Dependence Plot.
6. Model mampu memanfaatkan informasi historis serta faktor suhu untuk menghasilkan prediksi permintaan listrik yang lebih akurat.

---

## Kesimpulan

Model *time series forecasting* yang dibangun menggunakan **LGBMRegressor** dan **ForecasterRecursive** berhasil memprediksi permintaan listrik berdasarkan data historis dan suhu. Hasil analisis menunjukkan bahwa nilai permintaan listrik pada periode sebelumnya (*lag features*) merupakan faktor utama yang memengaruhi prediksi, sementara suhu berperan sebagai faktor eksternal yang turut memberikan kontribusi signifikan terhadap hasil prediksi.