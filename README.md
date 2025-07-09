# 📰 Fake News Classifier using NLP & Logistic Regression

This project uses Natural Language Processing (NLP) techniques and Logistic Regression to classify news as **real or fake**. 
It processes raw text data, vectorizes it using TF-IDF, and builds a binary classifier.

---


---

## 📥 Dataset

Due to GitHub file size limits, the full dataset is not included.  
Please **download `train.csv` manually** from Google Drive:

🔗 [Download Dataset from Google Drive](https://drive.google.com/file/d/17csyfuNGXEtfd4Ocf5uwHtbySiE-4VyJ/view?usp=sharing)


---

## 🧠 Features

- Combines `author` and `title` fields to create a new `content` column.
- Preprocesses text: cleaning, lowercasing, tokenizing, stopword removal, stemming.
- Converts text to numerical vectors using **TF-IDF**.
- Trains a **Logistic Regression** model to classify news as Real or Fake.
- Evaluates accuracy on training and test datasets.

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- NLTK (for stopwords and stemming)
- Scikit-learn (for vectorization, model training & evaluation)

---

## 📊 Model Accuracy

| Dataset      | Accuracy   |
|--------------|------------|
| Training     | ~98%       |
| Testing      | ~98%       |
