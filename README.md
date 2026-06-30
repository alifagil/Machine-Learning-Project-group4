```markdown
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
| **Linear SVM** | 86.86% | 86.72% | 86.86% | 86.78% |
| Logistic Regression | 86.01% | 85.88% | 86.01% | 85.94% |
| Multinomial Naive Bayes | 85.16% | 85.34% | 85.16% | 85.20% |
| Random Forest | 84.18% | 85.00% | 84.18% | 84.34% |

### 2. Performa Linear SVM (Setelah Hyperparameter Tuning)
| Model | Accuracy | Precision | Recall | F1-Score |
| :--- | :---: | :---: | :---: | :---: |
| **Linear SVM (Tuned)** | **88.63%** | **88.58%** | **88.63%** | **88.59%** |

- **Inference Time / Latency:** Real-time / Low latency per review.

---

## 🌐 Live Deployment

Aplikasi ini telah didistribusikan secara online dan dapat diakses melalui tautan berikut:
🔗 **[Live Demo Aplikasi Web](https://machine-learning-project-group4.vercel.app/)**

---


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
Akses aplikasi lokal melalui URL berikut:
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

```
