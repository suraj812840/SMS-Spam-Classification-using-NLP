# SMS-Spam-Classification-using-NLP
This project focuses on building a spam detection model to classify SMS messages as either spam or ham (non-spam) using Natural Language Processing (NLP) techniques and machine learning algorithms. SMS-based spam detection is crucial for maintaining the integrity of messaging platforms and preventing unwanted content from reaching users
# 📱 SMS Spam Classification using NLP

## 📌 Project Overview

This project uses **Natural Language Processing (NLP)** techniques and machine learning models to classify SMS messages as either **spam** or **ham** (non-spam). The model is trained on a dataset of SMS messages, and the goal is to create an efficient and accurate classifier that can help in spam detection for messaging platforms.

---

## 🎯 Objective

The objective of this project is to:
- Preprocess and analyze SMS data.
- Apply **NLP techniques** such as text vectorization (TF-IDF) and tokenization.
- Build a **spam detection model** using machine learning algorithms.
- Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.

---

## 🗂️ Dataset Information

- **Dataset**: The dataset contains SMS messages labeled as "spam" or "ham" (non-spam).
- **Source**: The dataset is from the UCI Machine Learning Repository or Kaggle.
- **Features**:
  - `Label`: Spam or Ham
  - `Message`: The text message

---

## 🔧 Workflow

1. **Data Loading**: Import and load the dataset.
2. **Data Preprocessing**:
   - Text cleaning (removing special characters, stop words, etc.)
   - Tokenization and stemming/lemmatization.
   - Text vectorization using **TF-IDF** or **CountVectorizer**.
3. **Model Building**:
   - Train machine learning models such as **Logistic Regression**, **Naive Bayes**, or **Random Forest**.
   - Evaluate the model using **cross-validation**.
4. **Performance Evaluation**: Use metrics like accuracy, confusion matrix, and classification report.

---

## 🧱 Models Used

- **Logistic Regression**
- **Naive Bayes Classifier**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**

---

## 📈 Model Performance

- **Training Accuracy**: ~95%
- **Test Accuracy**: ~93%
- **Precision**: ~94%
- **Recall**: ~92%

---

## 📊 Visualization

- Word cloud to visualize the most common words in spam/ham messages.
- Confusion matrix to evaluate classification performance.
- Bar plots for model comparison.

---

## 🛠️ Tools & Libraries

- Python
- **scikit-learn**: For machine learning models.
- **pandas** and **NumPy**: Data manipulation.
- **nltk** and **spaCy**: NLP preprocessing.
- **matplotlib** and **seaborn**: For visualizations.

