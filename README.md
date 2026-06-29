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

After evaluation, **Linear SVM** achieved the best overall performance and was selected as the final model.

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
│   └── index.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
│
├── dataset/
│   └── fake_reviews_dataset.csv
│
└── README.md
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Fake-Review-Detection.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

Open your browser

```
http://127.0.0.1:5000
```

---

## 📊 Model Evaluation

The project evaluates models using:

- Accuracy
- Precision
- Recall
- F1-Score
- Training Time
- Inference Time
- Latency per Review

---

## 👨‍💻 Author

**Alif Agil**

Machine Learning Final Project
