# Deteksi Toileting untuk Anak Cerebral Palsy

## Deskripsi Proyek
Proyek ini adalah implementasi perangkat lunak berbasis machine learning untuk mendeteksi aktivitas toileting pada anak dengan Cerebral Palsy. Proyek menggunakan model **Convolutional Neural Network (CNN)** dan **Logistic Regression (LR)** untuk menganalisis video dan data landmark tubuh.

## Fitur Utama
1. **Deteksi dan Plot Landmark:**
   - Menggunakan MediaPipe untuk mendeteksi pose manusia.
   - Landmark tubuh diplot untuk analisis visual.
   
2. **Model Machine Learning:**
   - **CNN:** Menganalisis citra landmark untuk klasifikasi.
   - **Logistic Regression:** Menggunakan fitur jarak, sudut, dan kemiringan tubuh untuk analisis berbasis data landmark.

## Struktur Proyek
- **Home Page:** Informasi dasar dan fungsi visualisasi.
- **CNN Page:** Implementasi model CNN untuk klasifikasi citra.
- **Logistic Regression Page:** Implementasi Logistic Regression menggunakan data landmark.

## Teknologi yang Digunakan
- **Library Utama:**
  - OpenCV
  - MediaPipe
  - TensorFlow/Keras
  - Scikit-learn
  - Streamlit
  - Plotly
  
- **Platform:** Streamlit digunakan untuk UI berbasis web.

## Cara Penggunaan
1. **Home:** Pilih video masukan, dan aplikasi akan mendeteksi serta memvisualisasikan landmark tubuh.
2. **CNN:** Jalankan model CNN untuk mengevaluasi performa menggunakan data landmark gambar.
3. **Logistic Regression:** Evaluasi model Logistic Regression dan tampilkan metrik evaluasi seperti Precision, Recall, F1-Score, dan Akurasi.

## Hasil
- **Model CNN:** Evaluasi dilakukan terhadap citra landmark menggunakan dataset khusus.
- **Model Logistic Regression:** Menggunakan fitur geometris seperti jarak, sudut, dan kemiringan dari pose tubuh.

## Catatan Penting
- **Kerahasian Data:** Data yang digunakan dalam proyek ini bersifat rahasia dan tidak dapat dibagikan untuk melindungi privasi subjek.
