# Klasifikasi Hewan
Proyek ini bertujuan untuk mengklasifikasikan gambar ke dalam 10 kelas hewan. Model dibuat dengan menggunakan MobileNetV2 berbasis transfer learning.

---

## Ringkasan Proyek
- Dataset berjumlah 26179 gambar
- Model yang digunakan menggunakan TensorFlow + Keras
- Dataset berasal dari kaggle : https://www.kaggle.com/datasets/alessiocorrado99/animals10/data
- Dataset memiliki 10 kelas label
- Model berhasil mencapai akurasi >95% pada data validasi dan pengujian
- Augmentasi Data dapat meningkatkan variasi dan ketahanan model

---

## Struktur Label Kelas
Dataset animal terdiri dari beberapa kelas hewan yang terdiri dari
"cane": "dog","cavallo": "horse","elefante": "elephant","farfalla": "butterfly","gallina": "chicken","gatto": "cat","mucca": "cow","pecora": "sheep","scoiattolo": "squirrel","ragno": "spider"

---
## Format Model
- **SavedModel**
- **TFLite (TensorFlow Lite)**
- **TFJS (TensorFlow.js)**
