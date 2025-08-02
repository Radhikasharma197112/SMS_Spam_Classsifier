# 📩 SMS Spam Classifier

A machine learning project that classifies SMS messages as **Spam** or **Ham** (Not Spam) using **Natural Language Processing (NLP)** techniques and two popular algorithms: **Naive Bayes** and **Random Forest Classifier**.

---

## 🧠 Algorithms Used

| Model               | Accuracy |
|--------------------|----------|
| Naive Bayes        | 97.57%   |
| Random Forest      | 97.93%   |

Both models were evaluated using classification reports, confusion matrices, and heatmaps for deeper insight.

---

## 🔧 Tech Stack

- Python 🐍
- Pandas
- scikit-learn
- NLTK (for preprocessing)
- Matplotlib & Seaborn (for visualization)

---

## 📌 Features

- Text cleaning and preprocessing using NLTK (lowercase, stopwords, punctuation removal)
- Feature extraction using Bag of Words (BoW) and TF-IDF
- Model training with Naive Bayes and Random Forest
- Evaluation using:
  - **Accuracy**
  - **Classification Report** (Precision, Recall, F1-score)
  - **Confusion Matrix**
  - **Heatmap Visualization**

---

## 📊 Evaluation Metrics

### ✅ Naive Bayes Classifier:
- **Accuracy**: 97.57%
- Strong performance on both spam and ham messages
- Lightweight and fast

### ✅ Random Forest Classifier:
- **Accuracy**: 97.93%
- Slightly better performance due to ensemble method
- More robust to overfitting

---

## 🖼️ Visual Analysis

- **Confusion Matrix**: Shows how many spam and ham messages were correctly/incorrectly classified.
- **Heatmap**: Makes it easy to spot prediction errors visually.

---
