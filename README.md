📰 Fake News Detection

🔹 Overview

This project classifies news articles as Fake or Real using Machine Learning and NLP techniques. It helps detect misinformation and unreliable news content automatically.

🔹 Features

Clean and preprocess news text

Label news as fake (0) or real (1)

Train ML models for classification

Evaluate using Accuracy, Precision, Recall, and F1-score

🔹 Dataset

Fake.csv – Fake news articles (label = 0)

True.csv – Real news articles (label = 1)

Columns include: title, text, subject, date.

🔹 Quick Start
# Clone repo
git clone <repository_url>
cd fake-news-detection

# Install dependencies
pip install -r requirements.txt

# Run project
python main.py

🔹 Model

Algorithm: Logistic Regression / Naive Bayes / Random Forest

Preprocessing: Text cleaning, tokenization, TF-IDF

Train/Test Split: 80% train, 20% test

🔹 Evaluation Example
Metric	Score
Accuracy	95%
Precision	94%
Recall	96%
F1-Score	95%
🔹 Future Work

Deploy as a web application

Use deep learning for better accuracy

Support multilingual news

Integrate news source credibility scores
