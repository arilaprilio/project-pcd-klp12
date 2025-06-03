# Klasifikasi Citra Daun Padi Sehat dan Terkena Bakteri dengan Implementasi Preprocessing dan Ekstraksi Fitur GLCM
## Nama Anggota
###  NAYLA ANUGERAH NISA : F1D02310020
###  NABILA ZAHIRANI : F1D02310019
###  L. APRILIO APRIZIANO : F1D02310068
###  YUSRI ABDI : F1D02310098
## Pendahuluan
Padi merupakan merupakan komoditas pangan utama di Indonesia. Namun, produktivitas tanaman padi seringkali terancam oleh serangan berbagai jenis penyakit daun seperti Brown Spot, Hispa, dan Leaf Blast. Serangan penyakit ini tidak hanya menurunkan hasil panen, tetapi juga dapat menyebabkan kerugian ekonomi yang signifikan bagi para petani. Oleh karena itu, upaya deteksi dini terhadap penyakit daun padi menjadi sangat penting agar penanganan bisa dilakukan lebih cepat dan efektif.
## Project Overview
Projek ini dikembangkan sebuah sistem klasifikasi penyakit daun padi berbasis digital image processing untuk membantu deteksi dini penyakit tanaman padi secara otomatis. Dataset yang digunakan berisi 200 citra daun padi dengan 2 kelas utama, yaitu Healthy, dan LeafBlast. Setiap citra akan diproses melalui beberapa tahapan preprocessing seperti grayscale, resizing, normalisasi, equalization, filtering, transformasi wavelet, morfologi, hingga deteksi tepi guna meningkatkan kualitas fitur citra. Selanjutnya, fitur tekstur diekstraksi menggunakan metode Gray Level Co-occurrence Matrix (GLCM), kemudian diklasifikasikan menggunakan algoritma machine learning seperti K-Nearest Neighbor (KNN), Support Vector Machine (SVM), dan Random Forest (RF). Melalui beberapa skenario percobaan dengan kombinasi preprocessing yang berbeda.
## Preprocessing
```
Percobaan 1 : Grayscale, normalisasi, ekualisasi
Percobaan 2 : Grayscale, thresholding, filter mean, operator prewitt, normalisasi
Percobaan 3 : Grayscale, thresholding, highlight, normalisasi
```
