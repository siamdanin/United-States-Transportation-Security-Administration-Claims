# Latar Belakang

Dataset TSA Claims adalah kumpulan data yang berisi informasi tentang klaim kerugian yang diajukan ke Transportation Security Administration (TSA) di Amerika Serikat. 

TSA adalah lembaga pemerintah yang bertanggung jawab untuk keamanan transportasi dalam negeri, termasuk keamanan bandara. 

TSA Claims dataset berisi kurang lebih dari 200.000 catatan klaim yang dibuat oleh penumpang yang telah mengalami kerugian atau kehilangan barang pribadi selama proses keamanan di bandara atau selama perjalanan dengan maskapai penerbangan.

# Pernyataan Masalah

Pada project ini, saya memposisikan diri saya sebagai seorang data analyst di lembaga TSA. Tentunya hasil analisa yang saya lakukan, kesimpulan dan rekomendasi yang saya berikan harus memberikan efek yang positif terhadap lembaga dan juga penumpang. Untuk mencapai hal tersebut ada pertanyaan yang perlu kita jawab seperti :

Bagaimana agar tingkat claim bisa diminimalisir dengan mencegah insiden, sehingga juga dapat mengurangi kerugian baik yang dialami penumpang, maskapai penerbangan, dan TSA ?

# Data

Sebelum masuk ke analisa untuk menjawab masalah tadi, kita memerlukan data yang memiliki kualitas baik atau paling tidak cukup layak untuk dibuat analisa. Dataset ini memiliki kualitas yang sangat buruk dan kacau, jadi kita akan coba melakukan beberapa tahap seperi :

## Overview
Melihat gambaran dataset secara umum.

## Data Preparation (Data Understanding & Data Cleansing)

### Data Understanding
Tahap ini melibatkan pengumpulan informasi tentang data yang akan digunakan untuk analisis. Hal ini dilakukan untuk memahami karakteristik data dan menemukan anomali pada data, seperti tipe data, nilai yang tidak valid/obeservasi yang tidak masuk akal, data duplikat,format pada data, dan nilai yang hilang.

### Data Cleansing
Berdasarkan informasi yang kita peroleh ketika memahami data. Selanjutnya pada tahap ini kita akan menyelesaikan permasalahan yang ada pada data kita.

1. Perlakuan terhadap tipe data.
2. Perlakuan terhadap data/observasi yang tidak valid atau tidak masuk akal.
3. Perlakuan terhadap data duplikat.
4. Perlakuan terhadap data kosong.
5. Perlakuan terhadap outliers.
6. Perlakuan terhadap format data.

## Pengurangan dan Penambahan Fitur/Kolom
Untuk memperkaya analisa.

# Analisa Data
Untuk menjawab pernyataan masalah 'Bagaimana agar tingkat claim bisa diminimalisir dengan mencegah insiden, sehingga juga dapat mengurangi kerugian baik yang dialami penumpang, maskapai, dan TSA?', analisis yang akan kita lakukan adalah sebagai berikut :

1. Analisis Tren Insiden
   Dilakukan untuk mengetahui apakah jumlah insiden mengalami peningkatan atau penurunan dari waktu ke waktu. Jika terdapat tren peningkatan, maka dapat dilakukan evaluasi terhadap kebijakan dan praktik keamanan di bandara untuk memastikan efektivitas dan efisiensinya dalam mencegah insiden dan mengurangi kerugian. Pada tahap ini, kita akan melihat secara umum jumlah biaya yang diajukan untuk ganti rugi claim dan jumlah pembayaran yang dibuat oleh TSA sebagai ganti rugi dari waktu ke waktu.

2. Analisis Faktor Risiko
   Dilakukan untuk mengidentifikasi faktor-faktor yang berkaitan dengan insiden dalam dataset TSA Claims. Analisis ini bertujuan untuk mengidentifikasi pola dan tren insiden yang berkaitan dengan faktor-faktor tersebut, sehingga dapat diambil tindakan pencegahan yang lebih efektif untuk mencegah insiden di masa depan.
   
## Analisis Tren Insiden

1. Jumlah kasus per tahun.
2. Menemukan pola/tren insiden berdasarkan waktu-waktu tertentu.
3. Analisa claim amount dan close amount berdasarkan tahun.
4. Amount Differences

## Analisis Faktor Risiko
- Airport
- Airline
- Claim Type
- Claim Site<br>
  Visualisasi dengan plotly tidak muncul untuk Claim Site di preview github. Jadi saya lampirkan gambar hasil visualisasinya.
- Item
- Status dan Disposition
- Day Differences

# Kesimpulan dan Rekomendasi
Menarik kesimpulan dari informasi yang didapat dari hasil analisa dan membuat rekomendasi berdasarkan kesimpulan tersebut untuk menjawab dan memberikan solusi atas permasalahan yang ingin diselesaikan.
