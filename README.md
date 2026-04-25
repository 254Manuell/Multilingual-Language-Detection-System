🌍 Multilingual Language Detection System
📌 Overview

A machine learning system that detects English, Kiswahili, Sheng, and Kamba in text, designed for code-mixed conversations common in Kenya.

⚠️ Problem

Traditional language detectors struggle with:

Code-switching
Sheng (slang)
Local dialects

This leads to poor performance in real-world Kenyan text.

🎯 Objectives
Build a multilingual classifier
Apply NLP preprocessing
Train & evaluate models
Deploy a working interface
📊 Dataset
600 samples (balanced):
English (150)
Kiswahili (150)
Sheng (150)
Kamba (150)

Sources: Local conversations, manual collection, X (Twitter), lughayangu.com

⚙️ Methodology

Preprocessing

Lowercasing, punctuation removal
Tokenization & stopword removal
Sheng normalization

Feature Extraction

TF-IDF

Models

Naive Bayes
Logistic Regression

Split

80% Train / 20% Test
📈 Evaluation
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
🌐 Deployment

Built with Streamlit

Text input
Real-time prediction
Confidence score
▶️ Usage
from model import predict_language

text = "Nafika kejani later"
prediction, confidence = predict_language(text)
print(prediction, confidence)
🔥 Key Features
Supports Kenyan languages
Handles slang & code-switching
Lightweight and fast
Real-time predictions
🌱 Future Work
Add more African languages
Improve Sheng dictionary
Use deep learning models
Deploy as API
👤 Author

Emmanuel Baraka Ngunnzi
Data Analyst | NLP Enthusiast 🌍
