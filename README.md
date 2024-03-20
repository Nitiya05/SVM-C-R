# SVM-C-R
Nama : Nitiya Rihadatul 'Aisy
Npm : 2108107010003

# Untuk menjalankan kode anda perlu memerhatikan beberapa hal :

Jika anda ingin jalan kode di **Di Google Colab**, Anda dapat mengunggah dataset langsung ke sesi Colab menggunakan tombol "Upload to session storage". Setelah diunggah, Anda dapat membaca dataset menggunakan kode Python seperti yang biasa Anda lakukan.

Atau jika di **Visual Studio Code (VSCode)** , Anda perlu memastikan bahwa dataset berada di direktori yang sama dengan skrip Python Anda atau Anda perlu menentukan jalur lengkap ke dataset dalam kode Anda. Anda juga dapat menggunakan ekstensi seperti "Python: Run Python File in Terminal" di VSCode untuk menjalankan skrip Anda dan membaca dataset dari lokasi yang ditentukan.
Atau berikut langkah-langkah umum untuk menggunakan dataset di VSCode:
1. Pastikan Dataset Ada di Direktori yang Tepat: Letakkan dataset di direktori yang sama dengan file skrip Python Anda atau tentukan jalur lengkap ke dataset dalam kode Anda.
2. Baca Dataset: Gunakan kode Python untuk membaca dataset dari lokasi yang ditentukan. Anda dapat menggunakan fungsi seperti pd.read_csv() untuk membaca file CSV atau fungsi yang sesuai untuk format file lainnya.
3. Jalankan Kode: Gunakan VSCode untuk menjalankan skrip Python Anda. Anda dapat menggunakan ekstensi VSCode seperti "Python: Run Python File in Terminal" untuk melakukan ini.
4. Periksa Output: Periksa output di terminal VSCode untuk memastikan bahwa dataset telah dibaca dengan benar dan tidak ada kesalahan.

# Tentang Dataset
1. untuk dataset yang digunakan pada klasifikasi adalah data.csv atau bisa di akses pada  _https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data_
  Dataset ini merupakan kumpulan data yang digunakan untuk menganalisis kanker payudara. Data tersebut diperoleh dari gambar-gambar digital fine needle aspirate (FNA) dari massa payudara. Fitur-fitur dalam dataset ini menggambarkan karakteristik inti sel yang terdapat dalam gambar-gambar tersebut.

  Setiap inti sel direpresentasikan oleh sepuluh fitur yang diukur dalam tiga dimensi. Fitur-fitur ini mencakup berbagai ukuran dan sifat-sifat inti sel, seperti ukuran, tekstur, keliling, luas, kehalusan, kekompakan, kecembungan, titik cekung, simetri, dan dimensi fraktal.

  Dataset ini terdiri dari 30 fitur yang dihitung berdasarkan rata-rata, standar error, dan nilai "terburuk" dari fitur-fitur tersebut. Sebagai contoh, fitur ke-3 adalah Mean Radius, fitur ke-13 adalah Radius SE (standar error), dan fitur ke-23 adalah Worst Radius.

  Dataset ini tidak memiliki nilai atribut yang hilang, dan distribusi kelasnya terdiri dari 357 kasus jinak dan 212 kasus ganas. **Tujuan dari penggunaan dataset ini adalah untuk menganalisis dan memprediksi apakah sebuah tumor payudara bersifat ganas atau jinak berdasarkan fitur-fitur yang diukur dari gambar FNA.**


2. untuk dataset yang digunakan pada regresi  adalah diamons.csv atau bisa di akses pada  [_https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data_](https://www.kaggle.com/code/heeraldedhia/regression-on-diamonds-dataset-95-score/input)https://www.kaggle.com/code/heeraldedhia/regression-on-diamonds-dataset-95-score/input
   Dataset ini merupakan kumpulan data tentang berlian yang memiliki beberapa kolom sebagai berikut:
   
1. **price**: Harga berlian dalam dolar AS ($326 hingga $18,823).
2. **carat**: Berat dari berlian tersebut dalam karat (0.2 hingga 5.01).
3. **cut**: Kualitas dari potongan berlian (Fair, Good, Very Good, Premium, Ideal).
4. **color**: Warna dari berlian, dari J (terburuk) hingga D (terbaik).
5. **clarity**: Tingkat kejernihan atau seberapa jernih berlian tersebut (I1 (terburuk), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (terbaik)).
6. **x**: Panjang berlian dalam milimeter (0 hingga 10.74).
7. **y**: Lebar berlian dalam milimeter (0 hingga 58.9).
8. **z**: Kedalaman berlian dalam milimeter (0 hingga 31.8).
9. **depth**: Persentase kedalaman total = z / rata-rata(x, y) = 2 * z / (x + y) (43 hingga 79).
10. **table**: Lebar dari bagian atas berlian relatif terhadap titik terlebar (43 hingga 95).
 **Tujuan dar penggunaan dataset ini adalah untuk menganalisis atau memprediksi harga berlian berdasarkan Karat yang dimilikinya.**


