# 📩 SpamClassifierSMS - Intelligent SMS Spam Detector

## 💡 About the Project
This project brings machine learning to life by building a **real-time SMS Spam Classifier** powered by Flask. Users can input any text message, and the app will instantly predict whether it's *Spam* or *Not Spam*. 

Under the hood, the model uses a **Bernoulli Naive Bayes classifier** combined with a **CountVectorizer** to detect spam patterns with impressive accuracy.

---

## ⚙️ Features

✅ Text Preprocessing  
- Lowercasing  
- Tokenization  
- Removal of stopwords and punctuation  
- Stemming (word normalization)  

✅ Real-Time Prediction  
- Predicts spam or not spam instantly through a simple web interface  

✅ Machine Learning Pipeline  
- Pre-trained `Bernoulli Naive Bayes` classifier (`BernouliClassifier.pkl`)  
- Pre-trained `CountVectorizer` (`vectorizer.pkl`)  
- Integrated seamlessly with Flask  

✅ User-Friendly Web Interface  
- Clean and simple form for text input  
- Instant spam classification feedback

---

## 🚦 Routes Overview

| Route | Description |
|-------|-------------|
| `/` | Displays the HTML form for message input |
| `/predict` | Handles form submission and returns the prediction result |

---

## 💼 Tech Stack

- Python
- Flask
- Scikit-learn
- NLTK
- HTML/CSS

---

## 📂 Project Structure

