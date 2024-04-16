# ANN

Repository ini dibuat untuk menyelesaikan tugas INF540 Pembelajaran Mesin dengan menerapkan Jaringan Saraf Tiruan (ANN) pada dataset Iris dan data bank churn untuk dilakukan klasifikasi.

## *Introduction*
### Tentang Dataset

#### *- Data-Bank-Churn Classification using ANN:* 

Data-Bank-Churn adalah dataset yang digunakan untuk klasifikasi pelanggan bank yang akan membatalkan layanan atau tidak. Dataset ini berisi informasi tentang pelanggan bank, seperti nomor customer, nama, skor kredit, geografi, jenis kelamin, umur, jumlah bulan menjadi member, saldo, jumlah produk, kartu kredit, aktif member, gaji yang diprediksi, dan status keluar. Dataset dapat diunduh melalui link berikut: https://www.megabagus.id/download/data-ann/#

Berikut adalah penjelasan dari beberapa kolom pada dataset data-bank-churn:

- **RowNumber**: Nomor urut dari data, dimulai dari 1
- **CustomerId**: ID unik dari setiap pelanggan.
- **Surname**: Nama belakang dari pelanggan.
- **CreditScore**: Skor kredit dari pelanggan.
- **Geography**: Wilayah geografis dari pelanggan
- **Gender**: Jenis kelamin dari pelanggan
- **Age**: Usia dari pelanggan.
- **Tenure**: Jumlah bulan yang pelanggan telah menjadi anggota bank.
- **Balance**: Saldo rata-rata dari akun pelanggan.
- **NumOfProducts**: Jumlah produk yang dimiliki oleh pelanggan.
- **HasCrCard**: Indikator apakah pelanggan memiliki kartu kredit, yaitu: "Yes", "No".
- **IsActiveMember**: Indikator apakah pelanggan masih aktif atau tidak, yaitu: "Yes", "No".
- **EstimatedSalary**: Gaji yang diprediksi dari pelanggan.
- **Exited**: Indikator apakah pelanggan telah membatalkan layanan atau tidak, yaitu: "Yes", "No".

Penjelasan lebih lanjut terkait file main.ipynb dapat dilihat pada link berikut: https://www.megabagus.id/deep-learning-artificial-neural-networks-aplikasi

#### *- Iris-Flowers Classification using ANN*
Dataset yang digunakan untuk permasalahan klasifikasi ini dapat didowload melalui link berikut: https://www.kaggle.com/datasets/arshid/iris-flower-dataset

Dataset tersebut terdiri dari 150 sampel, 4 fitur dan 3 kelas dengan detail sebagai berikut:

- panjang sepal (dalam cm)
- lebar sepal (dalam cm)
- panjang kelopak (dalam cm)
- lebar kelopak (dalam cm)
- kelas:
    - Iris Setosa
    - Iris Versicolour
    - Iris Virginica

### *Latar Belakang*
Dalam dunia pembelajaran mesin, salah satu tugas yang umum adalah klasifikasi, yaitu mengklasifikasikan entitas ke dalam kategori atau kelas yang sesuai berdasarkan fitur atau atribut yang ada. Salah satu dataset yang sering digunakan untuk latihan dalam klasifikasi adalah dataset Iris.

**Dataset Iris** merupakan dataset yang terdiri dari tiga spesies iris (Iris setosa, Iris virginica, dan Iris versicolor) dengan empat fitur numerik (panjang dan lebar kelopak, serta panjang dan lebar mahkota bunga). Tujuan dari proyek ini adalah untuk menggunakan Jaringan Saraf Tiruan (ANN) untuk melakukan klasifikasi spesies berdasarkan fitur-fitur ini.

### *Permasalahan*
Dalam dataset Iris, tujuan utamanya adalah melakukan klasifikasi spesies bunga berdasarkan empat fitur: panjang dan lebar kelopak serta panjang dan lebar mahkota. Tantangan utama adalah mengembangkan model yang dapat mengklasifikasikan spesies bunga dengan tingkat akurasi yang tinggi berdasarkan fitur-fitur tersebut.

### *Langkah*
Untuk menyelesaikan permasalahan diatas, digunakan langkah-langkah berikut:
#### 1. Import Libraries
Dalam langkah pertama, kita mengimpor semua library yang diperlukan untuk analisis dan pemodelan data yang sudah disertakan dalam file requirement.txt

#### 2. Collecting Data
#### 3. EDA
#### 4. Preprosesing Data
Ada beberapa proses yang dilakukan dalam tahapan ini, yaitu:
- *One-Hot Encoding*
Proses ini dilakukan untuk mengonversi variabel kategorikal (kelas) menjadi bentuk numerik.
- *StandardScaller* 
Proses ini dilakukan untuk menormalisasi fitur-fitur yang akan digunakan dalam proses training

#### 5. Splitting model
#### 6. Bangun model ANN
#### 7. Perhitungan Akurasi
Menggunakan algorima ANN didapatkan bahwa akurasi dari model yang dibangun adalah 0.966667 sedangkan 0.069982


## *Conclusion*
Berdasarkan proses yang telah dilakukan, didapatkan bahwa akurasi yang diperoleh dari proses klasifikasi menggunakan model ANN (0.966667) lebih rendah dibandingkan dengan model SVM (1.00),dapat dilihat pada repositori https://github.com/Nuzulurrahmah/SVM. Menurut analisis saya, hal ini terjadi karena dalam proses Preprosesing data dalam pembangunan model menggunakan SVM, saya melewatkan tahapan normalisasi.


### *How to Run*

Untuk menjalankan kode di repositori GitHub https://github.com/Nuzulurrahmah/2108107010012_Pertemuan_11_ANN.git, Anda dapat mengikuti langkah-langkah berikut:

1. Clone Repository

```bash
git clone https://github.com/Nuzulurrahmah/2108107010012_Pertemuan_11_ANN.git
```
2. Setup env
```
conda create --name python=Python 3.9.12
conda activate --name
pip install -r requirement.txt
```

3. Jalankan source code pada env Python

## Authors

- [@Nuzulurrahmah](https://github.com/Nuzulurrahmah)
