# Predictive Analytics

Anda mengetahui bahwa harga sebuah diamonds dengan karakteristik tertentu bernilai $9000 di pasaran.  Jika ingin mendapatkan profit, 
tentu perusahaan harus mendapatkan harga beli diamond yang lebih rendah dari $9000. Sebut saja misal, harga belinya adalah $5000. 
Sudah pasti ini akan menjadi keuntungan besar bagi perusahaan. Sebaliknya, jika perusahaan membeli diamonds tersebut dengan harga di atas $9000, 
maka perusahaan akan rugi. Tentu saja semua bisnis mengejar profit. Oleh karena itu, 
penting bagi perusahaan untuk mengetahui dan dapat memprediksi harga diamonds di pasar. Prediksi akan digunakan untuk menentukan berapa harga beli yang pantas untuk diamonds dengan 
karakteristik tertentu sehingga perusahaan bisa mendapatkan profit sebesar mungkin. 
Tidak seperti emas yang harga jual dan belinya mengacu pada harga perdagangan emas dunia, harga diamonds dipengaruhi oleh beberapa fitur khusus. 
Fitur tersebut antara lain, karat, ukuran, bentuk potongan, warna, serta tingkat kejernihan diamonds. Tidak adanya acuan harga diamonds seperti acuan harga emas menyebabkan perusahaan memerlukan sistem untuk memprediksi harganya.

![Gambar Diamond](https://github.com/olober76/PredictiveAnalyticsDiamond/blob/main/assets/diamondpic.png)


## Problem Statements dan Goals
Berdasarkan kondisi yang telah diuraikan sebelumnya, perusahaan akan mengembangkan sebuah sistem prediksi harga diamonds untuk menjawab permasalahan berikut.

- Dari serangkaian fitur yang ada, fitur apa yang paling berpengaruh terhadap harga diamonds?
- Berapa harga pasar diamonds dengan karakteristik atau fitur tertentu?  

Untuk  menjawab pertanyaan tersebut, Anda akan membuat predictive modelling dengan tujuan atau goals sebagai berikut:

- Mengetahui fitur yang paling berkorelasi dengan harga diamonds.
- Membuat model machine learning yang dapat memprediksi harga diamonds seakurat mungkin berdasarkan fitur-fitur yang ada.


## Metodologi
Prediksi harga adalah tujuan yang ingin dicapai. Seperti yang kita tahu, harga merupakan variabel kontinu. Dalam predictive analytics, saat membuat prediksi variabel kontinu artinya Anda sedang menyelesaikan permasalahan regresi. Oleh karena itu, metodologi pada proyek ini adalah: membangun model regresi dengan harga diamonds sebagai target.



## Metrik

Metrik digunakan untuk mengevaluasi seberapa baik model Anda dalam memprediksi harga. Untuk kasus regresi, beberapa metrik yang biasanya digunakan adalah Mean Squared Error (MSE) atau Root Mean Square Error (RMSE). Secara umum, metrik ini mengukur seberapa jauh hasil prediksi dengan nilai yang sebenarnya. Kita akan bahas lebih detail mengenai metrik ini di modul Evaluasi. Pengembangan model akan menggunakan beberapa algoritma machine learning yaitu K-Nearest Neighbor, Random Forest, dan Boosting Algorithm. Dari ketiga model ini, akan dipilih satu model yang memiliki nilai kesalahan prediksi terkecil. Dengan kata lain, kita akan membuat model seakurat mungkin, yaitu model dengan nilai kesalahan sekecil mungkin.
Membuat model prediktif dengan machine learning tentu memerlukan data. Berita baiknya adalah, perusahaan memiliki data yang dibutuhkan untuk membuat model prediksi. Dataset yang akan kita gunakan pada praktik kali ini adalah Diamond dataset.


-  Sumber dataset : [Diamond Dataset Pricing, Revenue, etc.](https://github.com/tidyverse/ggplot2/tree/main/data-raw)


## Explanatory Data Analytics
EDA yang digunakan meliputi

- Data loading
- Exploratory Data Analysis - Deskripsi Variabel
- Exploratory Data Analysis - Menangani Missing Value dan Outliers
- Exploratory Data Analysis - Univariate Analysis
- Exploratory Data Analysis - Multivariate Analysis

## Model Development
Penggunaan Model Machine Learning akan membandingkan beberapa model yang akan di generate, meliputi: 

- K-Nearest Neighbor
- Random Forest
- Boosting Algorithm

