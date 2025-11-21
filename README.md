# Heart-Disease-Classification-Project

## 📌 Project Overview

Proyek ini merupakan eksplorasi data kesehatan untuk memahami pola dan faktor risiko penyakit jantung menggunakan dataset **Personal Key Indicators of Heart Disease**. Melalui pendekatan Exploratory Data Analysis (EDA) dan data storytelling, proyek ini bertujuan mengubah data mentah menjadi insight yang mudah dipahami dan bermakna.

Notebook utama: `Classification_HeartDisease.ipynb`

---

## 🎯 Objective

Menjawab pertanyaan utama:

> Pola apa yang dapat membantu mengidentifikasi individu yang berpotensi memiliki penyakit jantung berdasarkan data kesehatan dan gaya hidup?

---

## 🗂 Dataset Description

* Jumlah data: **319.795 individu**
* Setiap baris merepresentasikan 1 orang
* Target variabel: `HeartDisease`

  * Yes → Memiliki penyakit jantung
  * No → Tidak memiliki penyakit jantung

Dataset mencakup informasi seperti:

* BMI
* Kebiasaan merokok
* Aktivitas fisik
* Kondisi kesehatan mental & fisik
* Riwayat penyakit
* Persepsi kesehatan umum

---

## 🔍 Data Exploration Narrative

### 1. Mengenal Populasi Data

Mayoritas individu dalam dataset tidak memiliki penyakit jantung. Namun, jumlah penderita tetap signifikan, menandakan bahwa penyakit jantung merupakan risiko nyata yang tersebar luas.

Secara umum, responden memiliki persepsi kesehatan yang baik, dengan kategori "Good" menjadi yang paling dominan. Hal ini menciptakan kontras menarik antara persepsi subjektif dan risiko objektif yang terdeteksi melalui data.

---

### 2. Kisah di Balik Angka

Analisis fitur numerik mengungkap pola berikut:

* Rata-rata BMI berada di angka ~28, menunjukkan kecenderungan overweight
* Waktu tidur rata-rata: 7 jam per hari
* Mayoritas tidak mengalami gangguan fisik atau mental yang signifikan dalam 30 hari terakhir

Namun, keberadaan outliers menunjukkan adanya individu dengan kondisi kesehatan yang jauh lebih buruk dari rata-rata, yang membutuhkan perhatian lebih dalam analisis risiko.

---

### 3. Gaya Hidup & Risiko Tersembunyi

Data menunjukkan:

* Riwayat merokok cukup tinggi
* Beberapa individu mengalami kesulitan berjalan
* Terdapat kasus diabetes dan stroke yang signifikan

Hal ini mengindikasikan bahwa risiko penyakit jantung tidak hanya berkaitan dengan usia, tetapi juga akumulasi kebiasaan hidup jangka panjang.

---

### 4. Data Imbalance

Jumlah responden tanpa penyakit jantung jauh lebih besar dibanding yang memiliki penyakit jantung. Ketidakseimbangan ini menjadi pertimbangan penting dalam proses modeling agar hasil prediksi tidak bias.

---

## 📊 Key Insights

* Mayoritas individu merasa sehat, namun sebagian memiliki risiko tersembunyi
* Faktor gaya hidup seperti merokok dan kurang aktivitas fisik berkontribusi terhadap risiko
* Dataset berskala besar dan representatif
* Diperlukan perhatian khusus pada data imbalance saat membangun model

---

## 💡 Project Value

Proyek ini menunjukkan bagaimana data kesehatan dapat dimanfaatkan untuk:

* Mengidentifikasi risiko penyakit jantung lebih dini
* Mendukung pengambilan keputusan berbasis data
* Meningkatkan kesadaran terhadap pola hidup sehat

Ini bukan hanya proyek teknis, tetapi refleksi perjalanan dalam memahami bagaimana data dapat menjadi suara bagi kesehatan manusia.


