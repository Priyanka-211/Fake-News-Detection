# 📰 Fake News Detection using Machine Learning (NLP)

This project demonstrates how to build a machine learning model to detect fake news articles using Natural Language Processing (NLP) techniques. It includes data cleaning, vectorization (TF-IDF), model building using Naive Bayes, and evaluation metrics to measure accuracy.

---

## 📌 Project Objective

The goal is to classify news articles as **"Fake"** or **"Real"** using supervised learning algorithms and NLP techniques.

---

## 📁 Dataset

- Source: Kaggle or other public datasets
- Columns: `title`, `text`, `label` (1 = Real, 0 = Fake)

---

## 🧰 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- NLTK
- TF-IDF Vectorizer

---

## 🔍 Project Workflow

1. **Data Loading & Preprocessing**
   - Handling missing values
   - Combining title & text
   - Label encoding

2. **Text Cleaning**
   - Lowercasing, removing punctuation, stopwords, etc.
   - Tokenization and lemmatization using NLTK

3. **Feature Extraction**
   - TF-IDF Vectorization

4. **Model Building**
   - Naive Bayes classifier
   - (Optional: Add Logistic Regression, Random Forest, etc.)

5. **Evaluation**
   - Accuracy score
   - Confusion Matrix
   - Classification report

6. **Manual Testing**
   - Test your own input text to check if it's fake or real

---

## 🧪 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/fake-news-detection.git
