# Data Understanding

## Korelasi antara sepal_width dan sepal_length
![sepal_width dan sepal_length](iris1.png)
<br>
Dari gambar di atas menunjukkan korelasi antara sepal_widh dan sepal_length sangat lemah atau tidak ada korelasi, dikarenakan Titik-titik data tersebar tanpa membentuk pola yang jelas, menunjukkan bahwa tidak ada hubungan yang kuat antara sepal length dan sepal width. artinya Kedua variabel ini dapat dianggap sebagai fitur yang berdiri sendiri dan tidak saling mempengaruhi secara linear.


## Korelasi antara petal_width dan petal_length
![petal_width dan petal_length](iris2.png)
<br>
dari gambar di atas menunjukkan korelasi antara petal_width dan petal_length sangat kuat, dikarenakan Titik-titik data membentuk pola yang jelas dari kiri bawah ke kanan atas, menunjukkan bahwa semakin besar nilai petal_length, semakin besar pula nilai petal_width. artinya kedua variabel sangat rapat membentuk pola linear yang jelas. namun terdapat Dua cluster yang terpisah kemungkinan besar merepresentasikan iris yang berbeda, tetapi tidak menyebabkan ambigu.


## Korelasi antara sepal_length dan petal_length
![sepal_length dan petal_length](iris3.png)
<br>
Dari gambar di atas menunjukkan korelasi antara sepal_length dan petal_length sangat kuat, dikarenakan titik-titik data membentuk pola yang jelas dari kiri bawah ke kanan atas, menunjukkan bahwa semakin besar nilai sepal_length, semakin besar pula nilai petal_length. Artinya kedua variabel sangat rapat membentuk pola linear yang jelas. Namun terdapat dua cluster yang terpisah kemungkinan besar merepresentasikan iris yang berbeda, tetapi tidak menyebabkan ambigu.


## Korelasi antara sepal_length dan petal_width
![sepal_length dan petal_width](iris4.png)
<br>
Dari gambar di atas menunjukkan korelasi antara sepal_length dan petal_width sangat kuat, dikarenakan titik-titik data membentuk pola yang jelas dari kiri bawah ke kanan atas, menunjukkan bahwa semakin besar nilai sepal_length, semakin besar pula nilai petal_width. Artinya kedua variabel sangat rapat membentuk pola linear yang jelas. Namun terdapat dua cluster yang terpisah kemungkinan besar merepresentasikan iris yang berbeda, tetapi tidak menyebabkan ambigu.


## Korelasi antara sepal_width dan petal_length
![sepal_width dan petal_length](iris5.png)
<br>
Dari gambar di atas menunjukkan korelasi antara sepal_width dan petal_length cenderung lemah, dikarenakan titik-titik data tidak membentuk pola linear yang konsisten dari kiri bawah ke kanan atas. Terlihat adanya dua cluster yang sangat terpisah secara vertikal, di mana cluster bawah memiliki petal_length rendah dan cluster atas memiliki petal_length tinggi, namun dalam masing-masing cluster tidak ada hubungan yang jelas dengan sepal_width. Artinya kedua variabel tidak menunjukkan pola yang rapat dan penyebaran data relatif acak. Dua cluster yang terpisah ini kemungkinan besar merepresentasikan spesies iris yang berbeda dengan karakteristik yang sangat berbeda, dan pemisahan yang sangat jelas ini tidak menyebabkan ambigu.


## Korelasi antara sepal_width dan petal_width
![sepal_width dan petal_width](iris6.png)
<br>
Dari gambar di atas menunjukkan korelasi antara sepal_width dan petal_width lemah atau tidak konsisten, dikarenakan titik-titik data tidak membentuk pola linear yang jelas dari kiri bawah ke kanan atas. Terlihat adanya dua cluster yang sangat terpisah secara vertikal, di mana cluster bawah memiliki petal_width sangat rendah dan cluster atas memiliki petal_width lebih tinggi, namun dalam masing-masing cluster penyebaran data relatif acak tanpa menunjukkan hubungan yang kuat dengan sepal_width. Artinya kedua variabel tidak membentuk pola linear yang rapat dan peningkatan sepal_width tidak diikuti oleh peningkatan petal_width secara konsisten. Dua cluster yang terpisah ini kemungkinan besar merepresentasikan spesies iris yang berbeda, dan pemisahan yang sangat jelas ini tidak menyebabkan ambigu.


## Statistik dikriptif
![Statistik dikriptif](iris7.jpg)
<br>
Berdasarkan tabel statistik deskriptif di atas, dataset Iris menunjukkan karakteristik yang menarik untuk setiap variabel pengukuran. Pada sepal_length, nilai rata-rata sebesar 5.84 cm sangat dekat dengan median 5.8 cm, mengindikasikan distribusi data yang relatif simetris dan terkonsentrasi di kisaran 5-6 cm dengan variasi yang kecil. Sementara itu, sepal_width memiliki mean 3.05 cm dengan median dan mode sama-sama bernilai 3 cm, menunjukkan bahwa lebar sepal cenderung homogen antar spesies dengan penyebaran data yang rapat. Berbeda dengan pengukuran sepal, variabel petal_length dan petal_width menunjukkan pola yang lebih kompleks. Nilai mode pada petal_length (1.5 cm) dan petal_width (0.2 cm) sangat berbeda dengan median masing-masing (4.35 cm dan 1.3 cm), yang mengindikasikan adanya distribusi bimodal atau dua kelompok data yang terpisah jelas. Hal ini diperkuat oleh nilai dispersi yang lebih tinggi pada petal_width (0.63) dibandingkan variabel lainnya, menunjukkan bahwa pengukuran petal memiliki variabilitas yang lebih besar dan lebih efektif untuk membedakan antar spesies.

## Google Collab
![Google Collab](collab.png)
<br>
https://colab.research.google.com/drive/1oBRw-sXud9UBPtUMbNaHNfiLkg3Ivz17?usp=sharing
<br>

<br>
Analisis dilakukan pada variabel sepal_length dari dataset Iris dengan jumlah data sebanyak 150 observasi.Nilai rata-rata sebesar 5,84 dan median sebesar 5,8 menunjukkan bahwa distribusi data cukup seimbang, karena kedua nilai tersebut hampir sama. Nilai minimum adalah 4,3 dan maksimum 7,9, sehingga rentang data tergolong cukup luas.Kuartil pertama (Q1) sebesar 5,1 dan kuartil ketiga (Q3) sebesar 6,4 menunjukkan bahwa sebagian besar data berada dalam interval tersebut. Standar deviasi sebesar 0,83 menandakan bahwa penyebaran data tidak terlalu besar dan masih relatif stabil.Nilai skewness sebesar 0,31 menunjukkan distribusi sedikit condong ke kanan, tetapi tidak signifikan. Modus sebesar 5,0 dengan frekuensi 10 kali menunjukkan bahwa nilai tersebut paling sering muncul.Secara keseluruhan, distribusi panjang sepal cenderung stabil, relatif simetris, dan tidak menunjukkan adanya penyimpangan ekstrem yang berarti.
<br>

### Kode
<br>

```sql

import pandas as pd
from scipy import stats

df = pd.read_csv("/content/IRIS.csv")

print("Daftar Kolom:", df.columns.tolist())
print("-" * 30)

print("Jumlah data     :", df['sepal_length'].count())
print("Rata-rata       :", df['sepal_length'].mean())
print("Nilai minimal   :", df['sepal_length'].min())
print("Q1              :", df['sepal_length'].quantile(0.25))
print("Q2 (Median)     :", df['sepal_length'].quantile(0.5))
print("Q3              :", df['sepal_length'].quantile(0.75))
print("Nilai Max       :", df['sepal_length'].max())
print("Kemencengan 1   :", "{0:.2f}".format(round(df['sepal_length'].skew(), 2)))
print("Kemencengan 2   :", "{0:.6f}".format(round(df['sepal_length'].skew(), 6)))
print("Standar Deviasi :", "{0:.2f}".format(round(df['sepal_length'].std(), 2)))
print("Variansi        :", "{0:.2f}".format(round(df['sepal_length'].var(), 2)))

mode = stats.mode(df['sepal_length'], keepdims=True)
print("Nilai modus {} dengan jumlah {}".format(mode.mode[0], mode.count[0]))
```

### Output
<br>

```sql
Daftar Kolom: ['sepal_length', 'sepal_width', 'petal_length', 'petal_width', 'species']
------------------------------
Jumlah data     : 150
Rata-rata       : 5.843333333333334
Nilai minimal   : 4.3
Q1              : 5.1
Q2 (Median)     : 5.8
Q3              : 6.4
Nilai Max       : 7.9
Kemencengan 1   : 0.31
Kemencengan 2   : 0.314911
Standar Deviasi : 0.83
Variansi        : 0.69
Nilai modus 5.0 dengan jumlah 10
```

## Revisi
<br>

## Google Collab
<br>

![Google Collab1](collab1.png)

<br>

![Google Collab1](collab2.png)

<br>

![Google Collab1](collab3.png)

<br>

### Link
<br>

https://colab.research.google.com/drive/1oBRw-sXud9UBPtUMbNaHNfiLkg3Ivz17?usp=sharing

<br>

### Kode Lengkap

```python
import pandas as pd
from scipy import stats

df = pd.read_csv("IRIS.csv")

print("Daftar Kolom:", df.columns.tolist())
print("-" * 60)

kolom_numerik = ['sepal_length', 'sepal_width', 'petal_length', 'petal_width']

for kolom in kolom_numerik:
    print(f"\n Statistik untuk kolom: {kolom.upper()}")
    print("-" * 40)
    print("Jumlah data     :", df[kolom].count())
    print("Rata-rata       :", "{0:.2f}".format(df[kolom].mean()))
    print("Nilai minimal   :", df[kolom].min())
    print("Q1              :", "{0:.2f}".format(df[kolom].quantile(0.25)))
    print("Q2 (Median)     :", "{0:.2f}".format(df[kolom].quantile(0.5)))
    print("Q3              :", "{0:.2f}".format(df[kolom].quantile(0.75)))
    print("Nilai Max       :", df[kolom].max())
    print("Kemencengan 1   :", "{0:.2f}".format(round(df[kolom].skew(), 2)))
    print("Kemencengan 2   :", "{0:.6f}".format(round(df[kolom].skew(), 6)))
    print("Standar Deviasi :", "{0:.2f}".format(round(df[kolom].std(), 2)))
    print("Variansi        :", "{0:.2f}".format(round(df[kolom].var(), 2)))
    
    mode_result = stats.mode(df[kolom].dropna(), keepdims=True)
    if len(mode_result.mode) > 0 and not pd.isna(mode_result.mode[0]):
        print("Nilai modus     : {} dengan frekuensi {}".format(
            mode_result.mode[0], mode_result.count[0]))
    else:
        print("Nilai modus     : Tidak ada modus tunggal")

print(f"\n Statistik untuk kolom: SPECIES")
print("-" * 40)
print("Jumlah data     :", df['species'].count())
print("Jumlah unik     :", df['species'].nunique())
print("Nilai unik      :", df['species'].unique().tolist())
print("\nDistribusi frekuensi:")
print(df['species'].value_counts())
print("\nModus (kategori paling sering):", df['species'].mode().values[0])
```
### Output

```text
Daftar Kolom: ['sepal_length', 'sepal_width', 'petal_length', 'petal_width', 'species']
------------------------------------------------------------

 Statistik untuk kolom: SEPAL_LENGTH
----------------------------------------
Jumlah data     : 150
Rata-rata       : 5.84
Nilai minimal   : 4.3
Q1              : 5.10
Q2 (Median)     : 5.80
Q3              : 6.40
Nilai Max       : 7.9
Kemencengan 1   : 0.31
Kemencengan 2   : 0.314911
Standar Deviasi : 0.83
Variansi        : 0.69
Nilai modus     : 5.0 dengan frekuensi 10

 Statistik untuk kolom: SEPAL_WIDTH
----------------------------------------
Jumlah data     : 150
Rata-rata       : 3.05
Nilai minimal   : 2.0
Q1              : 2.80
Q2 (Median)     : 3.00
Q3              : 3.30
Nilai Max       : 4.4
Kemencengan 1   : 0.33
Kemencengan 2   : 0.334053
Standar Deviasi : 0.43
Variansi        : 0.19
Nilai modus     : 3.0 dengan frekuensi 26

 Statistik untuk kolom: PETAL_LENGTH
----------------------------------------
Jumlah data     : 150
Rata-rata       : 3.76
Nilai minimal   : 1.0
Q1              : 1.60
Q2 (Median)     : 4.35
Q3              : 5.10
Nilai Max       : 6.9
Kemencengan 1   : -0.27
Kemencengan 2   : -0.274464
Standar Deviasi : 1.76
Variansi        : 3.11
Nilai modus     : 1.5 dengan frekuensi 14

 Statistik untuk kolom: PETAL_WIDTH
----------------------------------------
Jumlah data     : 150
Rata-rata       : 1.20
Nilai minimal   : 0.1
Q1              : 0.30
Q2 (Median)     : 1.30
Q3              : 1.80
Nilai Max       : 2.5
Kemencengan 1   : -0.10
Kemencengan 2   : -0.104997
Standar Deviasi : 0.76
Variansi        : 0.58
Nilai modus     : 0.2 dengan frekuensi 28

 Statistik untuk kolom: SPECIES
----------------------------------------
Jumlah data     : 150
Jumlah unik     : 3
Nilai unik      : ['Iris-setosa', 'Iris-versicolor', 'Iris-virginica']

Distribusi frekuensi:
species
Iris-setosa        50
Iris-versicolor    50
Iris-virginica     50
Name: count, dtype: int64

Modus (kategori paling sering): Iris-setosa
```
## Penjelasan Mengukur Jarak dengan Tipe Data Campuran
### Latar Belakang
Dalam praktik nyata, database yang digunakan untuk analisis data sering kali tidak hanya mengandung satu jenis tipe data saja, melainkan berbagai tipe data yang tercampur menjadi satu kesatuan. Sebagai contoh, sebuah dataset dapat memuat atribut nominal seperti warna atau jenis produk, atribut binary simetris seperti jenis kelamin, atribut binary asimetris seperti hasil tes medis yang bernilai Y/N, atribut numerik berupa data interval atau rasio seperti suhu atau pendapatan, serta atribut ordinal yang memiliki tingkatan atau peringkat seperti level kepuasan atau tingkat pendidikan. Karena setiap tipe data tersebut memiliki karakteristik dan cara pengukuran yang berbeda-beda, kita tidak dapat menerapkan satu rumus jarak secara langsung untuk menghitung kemiripan atau perbedaan antar objek. Sebagai solusi, pendekatan yang dapat digunakan adalah metode pembobotan, yaitu dengan menghitung jarak untuk setiap atribut secara terpisah sesuai dengan tipe datanya, kemudian menggabungkan seluruh hasil perhitungan tersebut menggunakan rumus jarak campuran yang memperhitungkan indikator validitas setiap atribut. Dengan pendekatan ini, seluruh jenis atribut dapat berkontribusi secara proporsional dalam perhitungan jarak akhir, sehingga hasil analisis menjadi lebih akurat dan mencerminkan karakteristik data yang sebenarnya.
<br>

### Rumus Mengukur Jarak Data Campuran
![Rumus Jarak](image-1.png)
<br>
Keterangan:

| Simbol | Penjelasan |
|--------|------------|
| $d(i,j)$ | Jarak antara objek i dan j |
| $p$ | Jumlah total atribut |
| $\delta_{ij}^{(f)}$ | Indikator keberadaan atribut ke-f pada objek i dan j |
| $d_{ij}^{(f)}$ | Jarak atribut ke-f antara objek i dan j |
​