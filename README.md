# 🧠 Sentiment Analysis on Twitter-like Text

<p align="center">
  <img src=<img width="438" alt="Image" src="https://github.com/user-attachments/assets/3f359197-4928-4e0b-856a-109e86f883ca" />
</p>

> 🎯 This project performs sentiment analysis on Twitter-style short texts using a machine learning model built with scikit-learn. It predicts whether a given sentence expresses a **positive** or **negative** sentiment.

---

## 🚀 Features

- ✅ **Real-time Sentiment Prediction**  
  Accepts custom user input via terminal and outputs predicted sentiment instantly.

- ✅ **Text Preprocessing**  
  Cleans raw text by removing punctuation, stopwords, and applies lemmatization for better modeling.

- ✅ **TF-IDF Vectorization**  
  Converts text data into numerical features using `TfidfVectorizer` to prepare input for training and prediction.

- ✅ **Naive Bayes Model**  
  Uses `MultinomialNB`, a powerful and efficient algorithm for text classification tasks.

- ✅ **Model Persistence**  
  Trained model is saved and loaded using `joblib`, ensuring quick access without retraining.

---

## 💡 How It Works

1. User inputs a sentence (e.g., *"I love this product!"*).
2. Text is preprocessed and vectorized.
3. The model classifies the sentiment as either:
   - `Positive 😊`
   - `Negative 😞`
   - `Neutral 😐`
4. The result is displayed immediately.

## 🧪 Sample Input

```bash
Enter a sentence: I absolutely loved the movie!
Predicted Sentiment: Positive 😊
