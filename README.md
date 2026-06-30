
# 🛡️ Fake Review Detection Web Application

A web-based Fake Review Detection system that utilizes **Natural Language Processing (NLP)** and **Machine Learning** to identify whether a product review is **Original (OR)** or **Computer Generated (CG)**. Users can analyze reviews by entering text manually or by scraping reviews directly from a product URL.

---

## 🚀 Features

- 🔍 Fake Review Detection using Machine Learning
- ✍️ Manual Review Prediction
- 🌐 Product Review Scraping via URL
- 📊 Exploratory Data Analysis (EDA)
- 📝 TF-IDF Feature Extraction
- 🤖 Multiple Machine Learning Model Comparison
- ⚙️ Hyperparameter Tuning with GridSearchCV
- 📈 Performance Evaluation
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Training Time
  - Inference Time
  - Latency

---

## 🧠 Machine Learning Pipeline


```

Dataset
│
▼
Exploratory Data Analysis (EDA)
│
▼
Lowercase Preprocessing
│
▼
Train-Test Split
│
▼
TF-IDF Vectorization
│
▼
Model Comparison
(Logistic Regression, Linear SVM,
Naive Bayes, Random Forest)
│
▼
Hyperparameter Tuning
│
▼
Best Model (Linear SVM)
│
▼
Deployment with Flask

```

---

## 🌐 Web Application Workflow


```

User Input
│
├── Manual Review
│
└── Product URL
│
▼
Selenium Web Scraper
│
▼
Extract Reviews
│
▼
TF-IDF Vectorizer
│
▼
Linear SVM Prediction
│
▼
Detection Result

```

---

## 📂 Dataset

- **Dataset:** Fake Reviews Dataset
- **Total Reviews:** 40,432
- **Classes:**
  - OR (Original Review)
  - CG (Computer Generated Review)

The dataset is balanced with an equal number of reviews for each class.

---

## 🤖 Models Evaluated

- Logistic Regression
- Linear Support Vector Machine (Linear SVM)
- Multinomial Naive Bayes
- Random Forest

Setelah melalui proses evaluasi komparatif, **Linear SVM** dipilih sebagai model final karena memberikan performa terbaik dan waktu inferensi yang optimal.

---

## 📊 Model Evaluation

Berikut adalah hasil performa model sebelum dilakukan hyperparameter tuning, serta performa final **Linear SVM** setelah proses tuning menggunakan GridSearchCV:

### 1. Performa Model (Sebelum Tuning)
| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :---: | :---: | :---: | :---: |
| **Linear SVM** | *Isi_%* | *Isi_%* | *Isi_%* | *Isi_%* |
| Logistic Regression | *Isi_%* | *Isi_%* | *Isi_%* | *Isi_%* |
| Multinomial Naive Bayes | *Isi_%* | *Isi_%* | *Isi_%* | *Isi_%* |
| Random Forest | *Isi_%* | *Isi_%* | *Isi_%* | *Isi_%* |

### 2. Performa Linear SVM (Setelah Hyperparameter Tuning)
| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :---: | :---: | :---: | :---: |
| **Linear SVM (Tuned)** | **Isi_%** | **Isi_%** | **Isi_%** | **Isi_%** |

- **Inference Time / Latency:** Real-time / Low latency per review.

*(Catatan: Silakan isi nilai persentase di atas dengan menyalin angka yang tertera pada Gambar 1, Gambar 2, dan hasil tuning SVM yang lo miliki).*

---

## 📸 Screenshots

Berikut adalah tampilan antarmuka (UI) dari aplikasi web Fake Review Detection:

### Halaman Utama & Prediksi Manual
![Dashboard Utama](static/css/screenshot_dashboard.png)

### Hasil Scraping & Deteksi Review URL
![Hasil Deteksi](static/css/screenshot_result.png)

*(Catatan: Simpan screenshot aplikasi lo di folder `static/css/` atau folder lain, lalu sesuaikan nama filenya di atas agar gambarnya muncul).*

---

## 🛠️ Tech Stack

### Backend
- Python
- Flask

### Machine Learning
- Scikit-learn
- Pandas
- NumPy

### Frontend
- HTML5
- CSS3
- JavaScript

### Web Scraping
- Selenium

---

## 📁 Project Structure


```

Fake-Review-Detection/
│
├── app.py
├── svm_model.pkl
├── tfidf_vectorizer.pkl
├── requirements.txt
│
├── templates/
│    └── index.html
│
├── static/
│    ├── css/
│    │    └── style.css
│    └── js/
│         └── script.js
│
├── dataset/
│    └── fake_reviews_dataset.csv
│
└── README.md

```

---

## ▶️ Installation & Running

1. **Clone the repository**
   ```bash
   git clone [https://github.com/your-username/Fake-Review-Detection.git](https://github.com/your-username/Fake-Review-Detection.git)
   cd Fake-Review-Detection

```

2. **Install dependencies**
```bash
pip install -r requirements.txt

```


3. **Run the application**
```bash
python app.py

```


4. **Open your browser**
Akses aplikasi melalui URL berikut:
```
[http://127.0.0.1:5000](http://127.0.0.1:5000)

```



---

## 👥 Anggota Kelompok

Project ini disusun oleh:

1. **Alif Agil**
2. **Ahmad Rizki Wardana**
3. **Andrew Benjamin Pugar**
4. **Savero Aurelio Armanto**
*Machine Learning Final Project*

```

3. **Nama Anggota Kelompok:** Sudah otomatis memasukkan nama lo (**Alif Agil**) dan teman kelompok lo (**Ahmad Rizki Wardana**).

```
