# Obesity Prediction App

Aplikasi ini dibuat untuk memprediksi tingkat obesitas berdasarkan data gaya hidup dan kondisi fisik seseorang. Proyek ini merupakan bagian dari Capstone Project mata kuliah _Bengkel Koding - Data Science_ di Universitas Dian Nuswantoro.

## 🎯 Fitur

- Prediksi tingkat obesitas dengan model Machine Learning
- Input mencakup usia, tinggi, berat, kebiasaan makan, aktivitas fisik, dan lainnya
- Tampilan interaktif dengan Streamlit
- Hasil prediksi dengan penjelasan tingkat obesitas

## 🧠 Model

Model dilatih menggunakan:

- Preprocessing (missing value, encoding, scaling)
- Penyeimbangan data dengan SMOTE
- Hyperparameter Tuning (GridSearchCV)
- Model akhir: Random Forest

## 🚀 Cara Menjalankan Aplikasi

1. Clone repositori:

   ```
   git clone https://github.com/username/obesity-predictor-ds2025.git
   cd obesity-predictor-ds2025
   ```

2. Install dependensi:

   ```
   pip install -r requirements.txt
   ```

3. Jalankan aplikasi:
   ```
   streamlit run app.py
   ```

## 🌐 Deployment

Aplikasi ini dideploy menggunakan [Streamlit Cloud](https://streamlit.io/cloud).  
🔗 Link aplikasi: [(https://username-obesity-app.streamlit.app)](https://bengkel-coding.streamlit.app/)

## 🗂️ Struktur Folder

```
├── app.py                  # File utama aplikasi Streamlit
├── model.pkl               # Model machine learning yang disimpan
├── requirements.txt        # Daftar dependensi Python
└── README.md               # Dokumentasi proyek
```

## 👨‍🎓 Developer

Capstone Project  
Adi Perwira Perdana | A11.2022.14799 - Data Science  
Universitas Dian Nuswantoro

---

© 2025 Universitas Dian Nuswantoro
