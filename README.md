# Hate Speech Detection 

Klasifikasi Ujaran Kebencian (Hate Speech) dalam Bahasa Indonesia menggunakan **Naive Bayes** dan **TF-IDF**. Proyek ini merupakan implementasi dari tugas UTS Kecerdasan Buatan untuk mendeteksi konten berbahaya di media sosial.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0+-orange.svg)](https://scikit-learn.org/)

---

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk **mendeteksi ujaran kebencian** dalam tweet berbahasa Indonesia menggunakan pendekatan Machine Learning. Dataset yang digunakan adalah **ID Hate Speech Dataset** yang terdiri dari 713 tweet dengan label:
- **Non_HS** (Non Hate Speech): Tweet yang tidak mengandung ujaran kebencian
- **HS** (Hate Speech): Tweet yang mengandung ujaran kebencian

Model yang dibangun mampu mengklasifikasikan teks dengan akurasi **~88%** menggunakan algoritma **Multinomial Naive Bayes** dan representasi fitur **TF-IDF**.

---

## 🎯 Fitur Utama

- ✅ **Preprocessing Teks Lengkap** (Case folding, Cleaning, Tokenisasi, Stopword Removal, Stemming)
- ✅ **Handling Imbalanced Data** dengan Under-Sampling
- ✅ **TF-IDF Feature Extraction** (Unigram + Bigram)
- ✅ **Model Training** dengan Naive Bayes
- ✅ **Evaluasi Komprehensif** (Confusion Matrix, Accuracy, Precision, Recall, F1-Score)
- ✅ **Visualisasi Data** (Word Cloud, Charts, Heatmap)

---

## 📊 Dataset

**Catatan:** Dataset tidak seimbang (imbalanced), sehingga dilakukan **Random Under-Sampling** untuk menciptakan distribusi 50%-50%.

---

## 🚀 Instalasi & Penggunaan
## ✅ Langkah 1 – Import Library
<img width="848" height="239" alt="1" src="https://github.com/user-attachments/assets/06a5673a-80ad-4a74-b639-cadec081d29c" />

## Load Dataset & batasi 50 kolom pertama
<img width="524" height="161" alt="2" src="https://github.com/user-attachments/assets/7f5b739e-83a6-46cc-b9e7-45732d9b67d4" />

---
<img width="1212" height="551" alt="16" src="https://github.com/user-attachments/assets/fe827ced-2685-4a20-b97d-7f4f37faffab" />

---
<img width="827" height="571" alt="17" src="https://github.com/user-attachments/assets/75afc40c-d0c5-4f2f-abcf-6741df256fb6" />

## Membuat dua label untuk Dataset
<img width="374" height="93" alt="4" src="https://github.com/user-attachments/assets/d3efe96f-e48d-494f-9c17-effc08c40fd0" />

---
<img width="492" height="365" alt="5" src="https://github.com/user-attachments/assets/22aeb97b-e8c7-4fb1-965f-59cf93a05b7e" />

## ✅ Langkah 2 – Preprocessing Teks
<img width="522" height="577" alt="6" src="https://github.com/user-attachments/assets/5a69d93a-c2b5-49e9-bb50-9f37e071b42b" />

---
<img width="647" height="228" alt="7" src="https://github.com/user-attachments/assets/30593fa9-653a-4d1b-820a-f4065a8a3c29" />

## ✅ Langkah 3 – Representasi Fitur (Bag of Words)
<img width="450" height="114" alt="8" src="https://github.com/user-attachments/assets/8940f0c5-0a9f-4f10-9e44-832ee5510552" />

##  ✅ Langkah 4 – Train Model Naive Bayes
<img width="463" height="215" alt="9" src="https://github.com/user-attachments/assets/0f2e764e-bae6-4b6c-84d7-dc774d3f3a5d" />

## ✅ Langkah 5 – Evaluasi Model
<img width="535" height="128" alt="10" src="https://github.com/user-attachments/assets/c70a778a-ecdb-46c1-aa13-7e41d1dab199" />

---
<img width="1261" height="321" alt="11" src="https://github.com/user-attachments/assets/2a5be13e-2e3f-4571-9742-9885bb29d8fb" />

## ✅ Langkah 6 – Visualisasi Distribusi Label & Word Cloud
<img width="447" height="130" alt="12" src="https://github.com/user-attachments/assets/469aab97-611c-414e-a87a-7fa6c67ceba4" />

---
<img width="467" height="374" alt="13" src="https://github.com/user-attachments/assets/d5354c4b-dd17-49f6-857c-1d63bfae25c4" />

---
<img width="496" height="183" alt="14" src="https://github.com/user-attachments/assets/758b4d94-6c66-4ece-9e3d-8d29fa8990bd" />


## Hasil
<img width="1197" height="436" alt="15" src="https://github.com/user-attachments/assets/89811864-90fe-4620-a3b9-2ae825fb2ab5" />


---

## 📌 Catatan

**Disclaimer:** Model ini dibuat untuk tujuan edukatif. Penggunaan untuk deteksi ujaran kebencian di dunia nyata memerlukan pengembangan lebih lanjut dengan dataset yang lebih besar dan diverse.

---
