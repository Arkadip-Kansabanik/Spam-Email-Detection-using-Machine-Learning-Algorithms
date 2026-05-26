# 📧 Spam Email Detection using Machine Learning & NLP

A Machine Learning and Natural Language Processing (NLP) based project for detecting whether an email/SMS message is **Spam** or **Ham (Not Spam)**.

This project applies various supervised machine learning algorithms along with TF-IDF feature extraction to build an efficient spam classifier.

---

## 🚀 Project Overview

Spam emails and SMS messages are one of the major challenges in digital communication. This project aims to automatically classify incoming messages into:

- ✅ Ham (Legitimate Message)
- ❌ Spam (Unwanted/Malicious Message)

The project includes:
- Text preprocessing using NLP
- Exploratory Data Analysis (EDA)
- Feature extraction using TF-IDF
- Training multiple ML models
- Comparative performance analysis
- Real-time prediction system

---

## 📂 Dataset Information

Dataset used: **Spam Email Dataset (`spam.csv`)**

### Dataset Summary

| Attribute | Details |
|---|---|
| Total Messages | 5572 |
| Ham Messages | 4825 |
| Spam Messages | 747 |
| Features | Message Text, Label |
| File Format | CSV |

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn

---

## ⚙️ NLP Preprocessing Steps

The following preprocessing techniques were applied:

- Lowercasing
- Tokenization
- Stopword Removal
- Punctuation Removal
- Stemming using Porter Stemmer

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to analyze:
- Spam vs Ham distribution
- Word count patterns
- Character count patterns
- Sentence count patterns
- Correlation between features

Visualizations include:
- Pie Charts
- Histograms
- Heatmaps
- Performance Comparison Graphs

---

## 🔍 Feature Extraction

TF-IDF (Term Frequency–Inverse Document Frequency) was used to convert text into numerical vectors suitable for machine learning models.

---

## 🤖 Machine Learning Models Used

The following models were trained and evaluated:

1. Multinomial Naive Bayes
2. Bernoulli Naive Bayes
3. Logistic Regression
4. Support Vector Machine (SVM)
5. Decision Tree Classifier
6. Random Forest Classifier
7. K-Nearest Neighbors (KNN)
8. Gradient Boosting Classifier

---

## 📈 Model Performance Comparison

| Model | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| Multinomial Naive Bayes | 96.2% | 1.0 | 0.717 | 0.835 |
| Bernoulli Naive Bayes | **97.7%** | 0.991 | 0.84 | 0.909 |
| Logistic Regression | 95.2% | 0.949 | 0.681 | 0.793 |
| Support Vector Machine | 97.5% | 0.974 | 0.833 | 0.898 |
| Random Forest Classifier | 97.0% | 0.991 | 0.782 | 0.874 |
| Decision Tree Classifier | 93.4% | 0.843 | 0.623 | 0.716 |
| K-Nearest Neighbors | 90.2% | 1.0 | 0.268 | 0.423 |
| Gradient Boosting Classifier | 95.2% | 0.908 | 0.717 | 0.801 |

### 🏆 Best Performing Model
**Bernoulli Naive Bayes** achieved the best overall performance with:
- Highest Accuracy
- Excellent Precision
- Strong Recall balance

---

## 📷 Project Visualizations

The notebook contains:
- Spam vs Ham Pie Chart
- Word Count Histogram
- Character Count Histogram
- Sentence Count Histogram
- Correlation Heatmap
- Model Comparison Plot

---

## 📁 Project Structure

```bash
Spam-Email-Detection/
│
├── spam_email_detection.ipynb
├── Spam_Email_Detection.pdf
├── spam.csv
├── README.md
│
└── requirements.txt
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Spam-Email-Detection.git
```

### 2️⃣ Navigate to Project Directory

```bash
cd Spam-Email-Detection
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

Open:
```bash
spam_email_detection.ipynb
```

---

## 📦 Requirements

Example `requirements.txt`

```txt
pandas
numpy
matplotlib
seaborn
nltk
scikit-learn
```

---

## 🎯 Future Improvements

- Deploy using Streamlit or Flask
- Add Deep Learning models (LSTM/BERT)
- Improve handling of imbalanced datasets
- Real-time email integration
- Multilingual spam detection

---

