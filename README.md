# Prediksi Harga Rumah Di California

## Context

Dataset yang digunakan berasal dari sensus California tahun 1990, yang meskipun tidak relevan untuk memprediksi harga rumah saat ini, tetap menjadi dataset yang ideal untuk memahami dasar-dasar machine learning. Data ini mencakup informasi seperti lokasi geografis, jumlah kamar, populasi, dan tingkat pendapatan penduduk, yang memengaruhi nilai properti perumahan. Penentuan harga rumah merupakan tantangan penting, di mana pembeli mencari nilai yang adil, dan penjual ingin memastikan harga optimal berdasarkan berbagai faktor.

Dengan menggunakan machine learning, kita dapat mempelajari pola dan hubungan antara fitur yang kompleks secara lebih efisien dibandingkan metode manual. Pendekatan berbasis data ini memungkinkan analisis skala besar, memberikan wawasan akurat, dan membantu mempersiapkan pengaplikasian teknik prediksi untuk data masa kini. Proyek ini dirancang untuk memberikan pemahaman praktis tentang machine learning sambil mengeksplorasi dinamika historis pasar perumahan.

## Problem Statement

Salah satu tantangan utama dalam pasar perumahan adalah menentukan harga rumah yang optimal berdasarkan berbagai faktor seperti lokasi, jumlah kamar, populasi, dan pendapatan median. Harga yang terlalu tinggi dapat mengurangi minat pembeli, sedangkan harga yang terlalu rendah dapat menyebabkan kerugian finansial bagi penjual atau pengembang properti.

Mengingat banyaknya variabel yang memengaruhi nilai properti, pendekatan manual atau berbasis intuisi sering kali tidak cukup akurat untuk mencerminkan nilai sebenarnya. Oleh karena itu, diperlukan model prediksi yang berbasis data untuk membantu berbagai pihak, baik penjual maupun pembeli, dalam menentukan harga rumah yang kompetitif sekaligus menguntungkan.

## Goals

Berdasarkan permasalahan tersebut, tujuan utama dari proyek ini adalah tools yang dapat memprediksi kisaran nilai rumah secara presisi dan akurat. Tool ini diharapkan mampu memanfaatkan berbagai fitur seperti jumlah kamar, lokasi, populasi, dan pendapatan median untuk menghasilkan prediksi yang mendekati nilai sebenarnya. Dengan prediksi yang lebih akurat, penjual dapat menentukan harga yang optimal untuk rumah mereka, sehingga tetap kompetitif di pasar dan menguntungkan.

Bagi pengembang properti dan pembeli, model ini dapat menjadi alat bantu yang sangat berharga untuk memahami faktor-faktor yang memengaruhi nilai properti. Selain itu, model ini diharapkan dapat meningkatkan efisiensi dalam proses penilaian properti, mengurangi ketergantungan pada intuisi atau metode manual, serta mendukung pengambilan keputusan berbasis data yang lebih baik.

## Analytic Approach

Yang perlu kita lakukan adalah menganalisis data untuk menemukan pola dan hubungan antara fitur-fitur seperti lokasi, jumlah kamar, populasi, dan pendapatan median yang memengaruhi nilai rumah. Analisis ini akan membantu kita memahami faktor-faktor utama yang berkontribusi terhadap variasi harga properti.

Selanjutnya, kita akan membangun model regresi menggunakan machine learning untuk memprediksi harga rumah secara akurat. Model ini akan menjadi alat bantu bagi penjual atau pengembang properti dalam menentukan kisaran harga yang optimal, sehingga dapat meningkatkan daya saing di pasar sekaligus memaksimalkan keuntungan.

## Metric Evaluation

Evaluasi metrik yang akan digunakan adalah MAE, MedAE, dan R-squared. MAE (Mean Absolute Error) adalah rata-rata dari nilai absolut error, yang menunjukkan seberapa jauh prediksi model dari nilai sebenarnya. MedAE (Median Absolute Error) adalah nilai tengah dari error absolut, yang memberikan gambaran robust terhadap outlier. Sedangkan R-squared digunakan untuk mengevaluasi seberapa baik model dapat menjelaskan varians dari data. Semakin tinggi nilai R-squared, semakin baik model dalam merepresentasikan data.

Semakin kecil nilai MAE dan MedAE yang dihasilkan oleh model, semakin akurat prediksi harga rumah yang diberikan. Dengan menggunakan metrik-metrik ini, kita dapat mengevaluasi performa model secara menyeluruh dan memilih model terbaik yang mampu memprediksi harga rumah dengan presisi tinggi.
