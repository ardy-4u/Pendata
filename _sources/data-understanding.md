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
### Cara Menghitung $d_{ij}^{(f)}$ per Tipe Atribut

#### 1. Atribut Nominal atau Binary

$d_{ij}^{(f)} = 0$, jika $x_{if} = x_{jf}$ (nilai sama)

$d_{ij}^{(f)} = 1$, jika $x_{if} \ne x_{jf}$ (nilai berbeda)

Cara penghitungannya menggunakan metode *simple matching*.

#### 2. Atribut Numerik

Lakukan normalisasi terlebih dahulu agar skala seragam, misalnya dengan:

Z-score:  
$z_{if} = \frac{x_{if} - \mu_f}{\sigma_f}$

Mean Absolute Deviation: lebih robust terhadap outlier.

Setelah dinormalisasi, hitung jarak dengan metode numerik (Euclidean, Manhattan, dll).

#### 3. Atribut Ordinal

Langkah-langkah:

Ganti nilai dengan ranking $r_{if}$ (misal: rendah = 1, sedang = 2, tinggi = 3)

Normalisasi ke rentang [0,1]:

$$
z_{if} = \frac{r_{if} - 1}{M_f - 1}
$$

di mana $M_f$ = jumlah tingkat/kategori pada atribut ke-f

Hitung jarak menggunakan metode numerik pada nilai $z_{if}$.

## Analisis Menggunakan Orange Data Mining untuk Data yg Campuran
![alt text](image-13.png)
![alt text](image-9.png)
Widget Distances dipakai untuk menghasilkan matriks dissimilarity, yaitu matriks yang berisi nilai jarak antar setiap pasangan objek dalam dataset. Pada pengaturan Compare, opsi yang dipilih adalah Rows, sehingga perhitungan dilakukan antar baris data (antar objek), bukan antar kolom atau atribut. Pengaturan ini sesuai dengan tujuan analisis klaster dan visualisasi jarak, di mana matriks yang terbentuk merepresentasikan kedekatan atau perbedaan antar n data point.

Metode jarak yang digunakan adalah Manhattan (normalized). Pemilihan metrik ini dilakukan karena dataset yang digunakan mengandung atribut dengan skala berbeda, sehingga diperlukan normalisasi agar setiap atribut memiliki kontribusi yang seimbang terhadap perhitungan jarak. Manhattan dipilih karena lebih stabil terhadap perbedaan skala dan tidak terlalu sensitif terhadap nilai ekstrem dibandingkan Euclidean dalam konteks data campuran.
![alt text](image-10.png)
Gambar tersebut memperlihatkan Distance Matrix yang dihasilkan dari widget **Distance Matrix** pada Orange Data Mining. Matriks ini merepresentasikan nilai dissimilarity atau jarak antar setiap pasangan objek dalam dataset. Bentuknya simetris, sehingga jarak antara objek i dan j sama dengan jarak antara objek j dan i, atau $d(i,j) = d(j,i)$. Elemen pada diagonal utama bernilai nol karena setiap objek memiliki jarak nol terhadap dirinya sendiri.

Setiap nilai dalam matriks menunjukkan tingkat perbedaan numerik antar dua objek. Semakin kecil nilainya, semakin tinggi tingkat kemiripan antar objek tersebut. Sebaliknya, semakin besar nilainya, semakin besar pula perbedaan karakteristik di antara keduanya.

Sebagai ilustrasi, jarak antara customer 7590-VHVEG dan 5575-GNVDE sebesar 2,074 menunjukkan tingkat perbedaan yang cukup moderat. Sementara itu, jarak antara 7590-VHVEG dan 3668-QPYBK sebesar 0,554 menunjukkan bahwa kedua customer tersebut memiliki karakteristik yang relatif mirip. Perbedaan yang jauh lebih signifikan terlihat pada pasangan 8091-TTVAX dan 3668-QPYBK dengan nilai jarak sebesar 4,519, yang menunjukkan bahwa keduanya sangat berbeda secara karakteristik.

Secara matematis, matriks ini memenuhi sifat dasar fungsi jarak, yaitu bernilai non-negatif untuk objek yang berbeda, bersifat simetris ($d(i,j) = d(j,i)$), serta memenuhi prinsip ketaksamaan segitiga. Matriks dissimilarity ini kemudian digunakan sebagai dasar dalam proses **Hierarchical Clustering** untuk mengelompokkan pelanggan berdasarkan tingkat kemiripan karakteristiknya.
![alt text](image-11.png)
![alt text](image-12.png)
Berdasarkan hasil dendrogram, proses hierarchical clustering dilakukan menggunakan metode linkage Ward dan menghasilkan 4 cluster yang dianggap optimal. Pemotongan dendrogram dilakukan pada ketinggian tertentu sehingga terbentuk empat kelompok data sebagai berikut:

Cluster 1 terdiri dari 3 data.  
Cluster 2 terdiri dari 50 data.  
Cluster 3 terdiri dari 125 data.  
Cluster 4 terdiri dari 713 data.  

Metode Ward linkage dipilih karena bekerja dengan prinsip meminimalkan peningkatan varians dalam cluster (within-cluster variance) pada setiap tahap penggabungan. Dengan pendekatan ini, cluster yang terbentuk cenderung lebih kompak dan homogen dibandingkan metode linkage lainnya.

Distribusi anggota cluster menunjukkan bahwa dua cluster utama (C1 dan C2) memiliki jumlah anggota yang sama besar, sedangkan C3 dan C4 memiliki jumlah yang lebih kecil. Hal ini mengindikasikan adanya dua kelompok data yang dominan serta dua kelompok yang lebih spesifik berdasarkan kemiripan karakteristik atribut numerik yang digunakan dalam perhitungan jarak.

Hasil pengelompokan ini selanjutnya dapat dianalisis lebih lanjut melalui visualisasi seperti Scatter Plot, MDS, maupun evaluasi menggunakan Silhouette Plot untuk melihat kualitas pemisahan antar cluster.

## Implementasikan Data Iris untuk Mengukur Jarak di Orange

![alt text](image-6.png)

Gambar di atas merupakan sebagian data mentah dari dataset Iris yang digunakan untuk diimplementasikan dalam proses perhitungan jarak pada Orange Data Mining. Dataset ini terdiri dari empat atribut numerik, yaitu *sepal_length*, *sepal_width*, *petal_length*, dan *petal_width*, serta satu atribut kategorikal yaitu *species*.

Selanjutnya dilakukan proses perhitungan jarak antar objek sehingga dihasilkan matriks dissimilarity sebagai berikut:

![alt text](image-7.png)

Matriks tersebut menampilkan nilai jarak antar setiap pasangan data dalam dataset. Nilai yang lebih kecil menunjukkan tingkat kemiripan yang lebih tinggi antar objek, sedangkan nilai yang lebih besar menunjukkan perbedaan karakteristik yang semakin signifikan.

Gambar di atas menunjukkan alur implementasi pengukuran jarak dan proses clustering pada dataset Iris menggunakan Orange Data Mining. Proses dimulai dari widget **CSV File Import** untuk memuat dataset, kemudian dilanjutkan ke tahap **Preprocess** guna melakukan normalisasi dan penyesuaian atribut sebelum perhitungan jarak.

![alt text](image-8.png)
Selanjutnya, widget **Distances** digunakan untuk menghitung matriks dissimilarity antar objek berdasarkan metrik jarak yang telah ditentukan. Hasil perhitungan ini kemudian divisualisasikan melalui **Distance Matrix** untuk melihat nilai jarak antar setiap pasangan data.

Matriks jarak tersebut menjadi dasar dalam proses **Hierarchical Clustering**, yang bertujuan mengelompokkan data berdasarkan tingkat kemiripan karakteristiknya. Hasil clustering kemudian dianalisis lebih lanjut menggunakan beberapa visualisasi, seperti **Dendrogram**, **MDS (Multidimensional Scaling)** untuk proyeksi dua dimensi, **Scatter Plot**, serta **Silhouette Plot** untuk mengevaluasi kualitas cluster.

Untuk mengetahui distribusi jumlah anggota setiap cluster, output dari Hierarchical Clustering disalurkan ke widget **Group By**, yang kemudian ditampilkan dalam **Data Table** sebagai ringkasan jumlah data pada masing-masing cluster.

Alur ini menunjukkan tahapan lengkap mulai dari impor data, perhitungan jarak, pembentukan cluster, hingga evaluasi dan interpretasi hasil clustering.