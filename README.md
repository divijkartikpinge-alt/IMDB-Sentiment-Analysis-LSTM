# IMDB Sentiment Analysis using LSTM

## 📌 Project Overview
This project performs sentiment classification on IMDB movie reviews using a Deep Learning LSTM model.

The model predicts whether a movie review is Positive or Negative.

---

## 📊 Dataset
- IMDB Dataset (50,000 reviews)
- 25,000 Training samples
- 25,000 Testing samples
- Binary classification (0 = Negative, 1 = Positive)

---

## 🧠 Model Architecture
- Embedding Layer
- LSTM Layer (128 units)
- Dense Output Layer (Sigmoid activation)

Loss Function: Binary Crossentropy  
Optimizer: Adam  

---

## 📈 Model Performance
- Training Accuracy: ~85–90%
- Validation Accuracy: ~85%
- Evaluated using Confusion Matrix and Classification Report

---

## 🚀 Features
- Text preprocessing (cleaning, stopword removal)
- Tokenization & Padding
- LSTM-based deep learning model
- Accuracy & Loss visualization
- Live prediction demo

---

## ▶️ How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Run the notebook:
   sentiment_analysis.ipynb

---

## 📂 Project Files
- sentiment_analysis.ipynb → Main notebook
- sentiment_model.keras → Trained LSTM model
- tokenizer.pkl → Saved tokenizer
- requirements.txt → Required libraries

---

## 👨‍💻 Author
Divij
