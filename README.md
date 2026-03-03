# 📰 Fake News Detection using NLP & Machine Learning

## 📌 Overview
This project detects whether a news article is Fake or Real using Natural Language Processing techniques.

## 🚀 Model Details
- Feature Engineering: Title + Text combined
- Vectorization: TF-IDF
- Best Model: LinearSVC
- Accuracy Achieved: 95%

## 🛠 Technologies Used
- Python
- Scikit-learn
- Pandas
- Streamlit

## ▶️ How to Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py

## 📸 App Preview

<img width="1346" height="762" alt="Screenshot 2026-03-03 155226" src="https://github.com/user-attachments/assets/63e7e876-b61b-4843-95c4-416d5dd4e788" />


## 🏗 Project Structure

fake-news-detection/
│
├── app.py
├── model/
│   ├── fake_news_model.pkl
│   └── tfidf_vectorizer.pkl
├── requirements.txt
└── README.md
