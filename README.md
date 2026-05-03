# 📊 Analisis Sentimen Gojek vs Grab Menggunakan IndoBERT

Proyek ini bertujuan untuk menganalisis sentimen pengguna terhadap layanan **Gojek** dan **Grab** berdasarkan ulasan di Google Play Store menggunakan model **IndoBERT** dengan pendekatan **fine-grained sentiment classification**.

---

## 🎯 Tujuan Proyek

* Membandingkan persepsi pengguna terhadap layanan Gojek dan Grab
* Menganalisis sentimen secara detail (5 level sentimen)
* Mengidentifikasi aspek layanan yang paling berpengaruh terhadap kepuasan pengguna
* Menerapkan model deep learning berbasis **IndoBERT**

---

## 🧠 Metodologi

Proyek ini menggunakan pendekatan:

* **Natural Language Processing (NLP)**
* **Pretrained Language Model: IndoBERT**
* **Fine-Grained Sentiment Classification**
* **Aspect-Based Sentiment Analysis (ABSA)**

---

## 📌 Aspek yang Dianalisis

Analisis dilakukan berdasarkan 5 aspek utama:

1. 📱 Aplikasi / UI
2. 🚗 Pengemudi
3. 🛎️ Layanan
4. 💰 Harga / Biaya
5. 💳 Pembayaran

---

## ⭐ Kategori Sentimen (Fine-Grained)

| Skor  | Label          |
| ----- | -------------- |
| ⭐⭐⭐⭐⭐ | Sangat Positif |
| ⭐⭐⭐⭐  | Positif        |
| ⭐⭐⭐   | Netral         |
| ⭐⭐    | Negatif        |
| ⭐     | Sangat Negatif |

---

## 🔄 Alur Proyek

### 1. 🕷️ Data Collection

* Scraping data ulasan dari Google Play Store:

  * Aplikasi Gojek
  * Aplikasi Grab

### 2. 🧹 Data Preprocessing

Tahapan preprocessing meliputi:

* Case Folding
* Data Cleaning
* Tokenisasi
* Stopword Removal
* Stemming
* Normalisasi kata (kamus alay)

### 3. 🏷️ Labeling Data

* Label sentimen berdasarkan rating
* Label aspek menggunakan keyword-based classification
* Data balancing untuk tiap aspek

### 4. 🤖 Modeling

* Menggunakan **IndoBERT**
* Fine-tuning model untuk klasifikasi sentimen

### 5. 📊 Evaluasi & Analisis

* Perbandingan performa model
* Distribusi sentimen per aspek
* Insight terhadap layanan Gojek vs Grab

---

## 🛠️ Teknologi yang Digunakan

* Python
* Jupyter Notebook
* Pandas & NumPy
* Scikit-learn
* Sastrawi (stemming Bahasa Indonesia)
* Transformers (Hugging Face)
* IndoBERT

---

## 📁 Struktur Project

```
📦 Analisis-Sentimen-Gojek-Grab
 ┣ 📜 v3_Analisis_Sentimen_Gojek_Grab_IndoBERT.ipynb
 ┣ 📊 dataset (hasil scraping)
 ┣ 📄 README.md
 ┗ 📦 requirements.txt
```

---

## ▶️ Cara Menjalankan Project

1. Clone repository:

```bash
git clone https://github.com/username/repository-name.git
```

2. Masuk ke folder project:

```bash
cd repository-name
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Jalankan Jupyter Notebook: 

```bash
jupyter notebook
```

---

## 📈 Output yang Dihasilkan

* Dataset hasil preprocessing
* Model IndoBERT yang telah dilatih
* Visualisasi distribusi sentimen
* Analisis perbandingan Gojek vs Grab

---

## 📚 Kontribusi

Kontribusi sangat terbuka untuk:

* Improvement model
* Optimasi preprocessing
* Penambahan dataset
* Visualisasi yang lebih advanced

---

## 📌 Catatan

* Data diambil dari ulasan publik Google Play Store
* Model dilatih khusus untuk Bahasa Indonesia
* Hasil dapat berbeda tergantung jumlah data dan preprocessing

---

## 👨‍💻 Author

**Nama:** Muhammad Riyan Maulana
**Project:** Penelitian Analisis Sentimen
**Collab Link:** https://colab.research.google.com/drive/1DW6J849_xbPCcWhCQX2NECxiixEiBvzK?usp=sharing

