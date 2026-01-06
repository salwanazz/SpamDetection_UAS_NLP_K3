````md
📧 Deteksi Spam Email  
Python • Streamlit • Scikit-learn • NLP • TF-IDF

Deteksi Spam Email adalah aplikasi berbasis web untuk mengklasifikasikan email ke dalam kategori **spam** dan **ham (non-spam)** secara otomatis menggunakan pendekatan *Natural Language Processing (NLP)* dan *machine learning*. Sistem ini memanfaatkan ekstraksi fitur **TF-IDF** serta model klasifikasi yang telah dilatih dan disimpan dalam bentuk file `.pkl`.

Proyek ini dikembangkan sebagai tugas **UAS Mata Kuliah Natural Language Processing (NLP)**.

---

🚀 Fitur Utama
- Deteksi spam email secara otomatis  
- Prapemrosesan teks email berbasis NLP  
- Ekstraksi fitur menggunakan TF-IDF  
- Model klasifikasi machine learning  
- Antarmuka aplikasi interaktif menggunakan Streamlit  

---

🛠️ Teknologi yang Digunakan
Python • Streamlit • Scikit-learn • Sastrawi • Pandas • NumPy

---

📦 Instalasi & Menjalankan Aplikasi
1. Clone repository ini  
```bash
git clone https://github.com/salwanazz/SpamDetection_UAS_NLP_K3.git
cd SpamDetection_UAS_NLP_K3
````

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Jalankan aplikasi

```bash
streamlit run app.py
```

---

💬 Contoh Input Email

* "Selamat! Anda mendapatkan hadiah undian. Klik link berikut."
* "Promo besar-besaran, daftar sekarang!"
* "Bu, saya izin tidak masuk kuliah hari ini."
* "Terima kasih atas informasinya."

---

📁 Struktur Folder

```text
SpamDetection_UAS_NLP_K3/
├── models/
│   ├── models.pkl      # Model klasifikasi hasil training
│   └── tfidf.pkl       # Model TF-IDF vectorizer
├── app.py              # Aplikasi Streamlit
├── TubesNLP_Kel3.ipynb # Notebook training & evaluasi
├── requirement.txt
└── README.md
```

---

📌 Catatan
File `models.pkl` dan `tfidf.pkl` berisi model machine learning dan TF-IDF vectorizer yang telah dilatih sebelumnya dan digunakan langsung oleh aplikasi Streamlit untuk melakukan prediksi email spam dan non-spam.

---

👩‍💻 Tim Pengembang

* Salwa Nurazizah (10222154)
* Tiara Kurniawati (10222155)
* Muhamad Nurul Awalin (10222149)

Program Studi Informatika
Sekolah Tinggi Teknologi Cipasung
2025

```
```
