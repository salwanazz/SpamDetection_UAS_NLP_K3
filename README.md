# 📧 Deteksi Spam Email
![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-UI-red?logo=streamlit)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Sastrawi](https://img.shields.io/badge/Sastrawi-NLP-brightgreen)
![NLTK](https://img.shields.io/badge/NLTK-NLP-yellow)

Deteksi Spam Email merupakan aplikasi berbasis web untuk mengklasifikasikan email ke dalam kategori spam dan non-spam (ham) secara otomatis. Sistem dibangun menggunakan pendekatan *Natural Language Processing* (NLP) dan algoritma *machine learning* untuk membantu pengguna menghindari email berbahaya seperti spam, penipuan, dan phishing.

---

# 🚀 Fitur Utama

1. Klasifikasi email secara otomatis ke dalam kategori spam dan non-spam.
2. Pemrosesan teks menggunakan *Natural Language Processing* (NLP).
3. Ekstraksi fitur teks menggunakan metode TF-IDF.
4. Penerapan model *machine learning* untuk mendukung proses deteksi spam.
5. Antarmuka sederhana berbasis Streamlit untuk pengujian email secara langsung.

---

# 🛠️ Teknologi yang Digunakan

1. Python
2. Streamlit
3. Scikit-learn
4. Sastrawi
5. Natural Language Processing (NLP)
6. TF-IDF

---

📦 Instalasi & Menjalankan

```bash
git clone https://github.com/salwanazz/SpamDetection_UAS_NLP_K3.git
cd SpamDetection_UAS_NLP_K3
pip install -r requirements.txt
streamlit run app.py
```
---
# 📨 Contoh Pesan Email Spam

1. “Selamat! Anda memenangkan hadiah undian jutaan rupiah. Klik link berikut untuk klaim sekarang.”
2. “Promo besar-besaran! Dapatkan diskon 90% hanya hari ini. Daftar melalui link di bawah.”
3. “Akun Anda terdeteksi bermasalah. Verifikasi segera dengan mengisi data melalui tautan ini.”
4. “Lowongan kerja online gaji besar tanpa syarat. Daftar sekarang juga!”
5. “Anda terpilih sebagai pemenang hadiah. Kirim data pribadi Anda untuk proses pencairan.”
   
# 📩 Contoh Pesan Email Non-Spam (Ham)
1. “Bu, saya izin tidak masuk kuliah hari ini karena sedang sakit.”
2. “Terima kasih atas informasi yang telah disampaikan sebelumnya.”
3. “Rapat akan dilaksanakan besok pukul 09.00 WIB di ruang meeting utama.”
4. “Mohon dikirimkan kembali file laporan yang telah direvisi.”
5. “Selamat pagi, berikut saya lampirkan hasil tugas yang diminta.”
   
---

# 📁 Struktur Folder

```text
SpamDetection_UAS_NLP_K3/
├── data/
│   └── dataset.csv       # Dataset email spam dan non-spam yang digunakan untuk pelatihan
├── models/
│   ├── models.pkl        # Model klasifikasi hasil training (Logistic Regression & SVM)
│   └── tfidf.pkl         # TF-IDF Vectorizer untuk mengubah teks email menjadi fitur numerik
├── app.py                # Aplikasi utama Streamlit untuk deteksi spam email
├── TubesNLP_Kel3.ipynb   # Notebook training, evaluasi, dan analisis model
├── requirements.txt     
└── README.md             
```

---

# 🧾 Catatan

* Model dan vectorizer dimuat dari folder `models/` saat aplikasi berjalan.
* Email diproses melalui tahap NLP sebelum dilakukan prediksi.
* Sistem siap digunakan untuk demo dan pengujian manual.
