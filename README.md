## 🌍 Multilingual Language Detection System

A machine learning system that detects **English, Kiswahili, Sheng, and Kamba**, designed for **code-mixed Kenyan conversations**.

---

## ⚠️ Problem

Traditional detectors struggle with **code-switching, Sheng, and local dialects**, leading to poor real-world performance.

---

## 🎯 Objectives

* Build a multilingual classifier
* Apply NLP preprocessing
* Train & evaluate models
* Deploy a simple interface

---

## 📊 Dataset

* **600 balanced samples** (150 per language)
* Sources: local conversations, manual collection, X, lughayangu.com

---

## ⚙️ Method

* **Preprocessing:** cleaning, tokenization, stopwords, Sheng normalization
* **Features:** TF-IDF
* **Models:** Naive Bayes, Logistic Regression
* **Split:** 80/20

---

## 📈 Evaluation

Accuracy, Precision, Recall, F1 Score, Confusion Matrix

---

## 🌐 Deployment

Streamlit app with **real-time prediction + confidence score**

---

## ▶️ Usage

```python
from model import predict_language

prediction, confidence = predict_language("Nafika kejani later")
print(prediction, confidence)
```

---

## 🔥 Features

* Supports Kenyan languages
* Handles slang & code-mixing
* Fast and lightweight

---

## 🌱 Future Work

Expand languages, improve Sheng dictionary, use deep learning, deploy API

---

## 👤 Author

**Emmanuel Baraka Ngunnzi**
Data Analyst | NLP Enthusiast 🌍


