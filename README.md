# 🛡️ ReviewIN

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Flask](https://img.shields.io/badge/Flask-Web_App-black)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-orange)
![Model](https://img.shields.io/badge/Model-Linear%20SVM-success)

### Fake Review Detection Web Application using Machine Learning

ReviewIN is a web-based Fake Review Detection application that utilizes **Natural Language Processing (NLP)** and **Classical Machine Learning** to identify whether a product review is **Original Review (OR)** or **Computer Generated Review (CG)**.

The application enables users to analyze reviews either by entering text manually or by scraping reviews directly from an e-commerce product URL. ReviewIN applies **TF-IDF** feature extraction and a **Linear Support Vector Machine (Linear SVM)** classifier to provide fast and accurate predictions.

---

# 🚀 Live Demo

🌐 **Deployment**

https://machine-learning-project-group4.vercel.app/

---

# 🚀 Features

- 🔍 Fake Review Detection
- ✍️ Manual Review Prediction
- 🌐 Product Review Scraping via URL
- 📊 Exploratory Data Analysis (EDA)
- 📝 TF-IDF Feature Extraction
- 🤖 Multiple Machine Learning Model Comparison
- ⚙️ Hyperparameter Tuning using GridSearchCV
- 📈 Performance Evaluation
- ⚡ Fast Inference Time
- 📊 Interactive Dashboard
- 📉 Review Statistics Visualization

---

# 📂 Dataset

- **Dataset:** Fake Reviews Dataset
- **Total Reviews:** 40,432
- **Classes**
  - OR (Original Review)
  - CG (Computer Generated Review)

The dataset is balanced, containing an equal number of Original Reviews and Computer Generated Reviews.

---

# 🧠 Machine Learning Pipeline

```text
Dataset
   │
   ▼
Exploratory Data Analysis (EDA)
   │
   ▼
Text Preprocessing
(Lowercase & Cleaning)
   │
   ▼
Train-Test Split
   │
   ▼
TF-IDF Vectorization
   │
   ▼
Model Comparison
(Logistic Regression
Linear SVM
Naive Bayes
Random Forest)
   │
   ▼
Hyperparameter Tuning
(GridSearchCV)
   │
   ▼
Best Model
(Linear SVM)
   │
   ▼
Deployment using Flask
```

---

# 🌐 Web Application Workflow

```text                 User Input
                      │
        ┌─────────────┴─────────────┐
        │                           │
        ▼                           ▼
 Manual Review                Product URL
        │                           │
        │                 Selenium Web Scraper
        │                   (Next Feature)
        │                           │
        │                    Extract Reviews
        └─────────────┬─────────────┘
                      │
                      ▼
         Text Preprocessing
         (Regex & Cleaning)
                      │
                      ▼
            TF-IDF Vectorizer
                      │
                      ▼
             Linear SVM Model
                      │
                      ▼
             Prediction Result
```

---

# 🤖 Machine Learning Models

The following models were evaluated:

- Logistic Regression
- Linear Support Vector Machine (Linear SVM)
- Multinomial Naive Bayes
- Random Forest

After hyperparameter tuning and model comparison, **Linear SVM** achieved the best performance and was selected as the final model.

---

# 📊 Model Evaluation

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|---------:|----------:|--------:|---------:|
| **Linear SVM** | **0.9406** | **0.9408** | **0.9406** | **0.9406** |
| Logistic Regression | 0.9387 | 0.9389 | 0.9387 | 0.9387 |
| Random Forest | 0.8979 | 0.8998 | 0.8979 | 0.8978 |
| Naive Bayes | 0.8390 | 0.8671 | 0.8390 | 0.8360 |

---

# ⚡ Final Model Performance

**Linear SVM (After Hyperparameter Tuning)**

| Metric | Value |
|---------|------:|
| Accuracy | **0.9403** |
| Precision | **0.9403** |
| Recall | **0.9403** |
| F1-Score | **0.9403** |
| Training Time | **3.299 s** |
| Inference Time | **4.223 ms** |
| Latency | **0.000522 ms/review** |

---

# 🛠️ Tech Stack

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

# 📁 Project Structure

```text
ReviewIN/
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
│   ├── js/
│   │   └── script.js
│   └── assets/
│
├── dataset/
│   └── fake_reviews_dataset.csv
│
└── README.md
```

---

# ▶️ Installation

Clone this repository

```bash
git clone https://github.com/alifagil/Machine-Learning-Project-group4
```

Go to project directory

```bash
cd ReviewIN
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

```text
http://127.0.0.1:5000
```

---

# 📸 Application Screenshots

### 🏠 Home Page

> *<img width="1890" height="862" alt="image" src="https://github.com/user-attachments/assets/0eb71303-4063-4314-b446-188d51f3312b" />
*

---

### 🔍 Manual Prediction

> *<img width="1901" height="407" alt="image" src="https://github.com/user-attachments/assets/6267cffe-5d9b-4547-bbb4-b6e8c559cf13" />
*

---

---

### 📊 Dashboard & Analysis Result

> *<img width="1890" height="865" alt="image" src="https://github.com/user-attachments/assets/f4918db4-08a6-4f03-aa5e-2f186135e65d" />
*

---

# 👥 Project Team

This project was developed by:

- Alif Agil
- Ahmad Rizki Wardana
- Andrew Benjamin Pugar
- Savero Aurelio Armanto

---

# 🎯 Course Information

**Course:** Machine Learning

**Institution:** BINUS University

**Academic Year:** 2025/2026

---

# 📄 License

This project was developed for academic purposes as the Final Project for the Machine Learning course at BINUS University.
