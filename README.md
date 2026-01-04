# 🧠 Sentiment Analysis Study of Human Thoughts using Machine Learning Techniques

This project focuses on analyzing human thoughts and opinions expressed in text form and classifying them into different sentiment categories using Machine Learning and Natural Language Processing (NLP) techniques.

---

## 📌 Project Overview

Sentiment Analysis is the process of determining the emotional tone behind a series of words.  
In this project, user input text is analyzed and classified as **Positive**, **Negative**, or **Neutral** sentiment.

The system is implemented as a **Django web application** integrated with **Machine Learning models** for real-time sentiment prediction.

---

## 🎯 Objectives

- To analyze human thoughts using text data  
- To apply NLP preprocessing techniques  
- To build a Machine Learning model for sentiment classification  
- To provide sentiment results through a web interface  

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Web Framework:** Django  
- **Machine Learning:** Scikit-learn  
- **NLP Libraries:** NLTK  
- **Database:** SQLite  
- **Frontend:** HTML, CSS  
- **Visualization:** WordCloud  

---

## ⚙️ System Architecture

1. User enters text input  
2. Text preprocessing using NLP techniques  
3. Machine Learning model predicts sentiment  
4. Result displayed on the web interface  

---

## 🔍 NLP Techniques Used

- Tokenization  
- Stopword Removal  
- Lemmatization  
- Text Vectorization  

---

## 📊 Machine Learning Algorithms

- Naive Bayes / Logistic Regression (based on implementation)
- Trained on labeled sentiment datasets

---

## 📁 Project Structure
CODE/
│── manage.py
│── db.sqlite3
│── README.md
│── requirement.txt
│── requirements.txt
│
├── SentimentAnalysis/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── users/
│   ├── migrations/
│   ├── __init__.py
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
│
├── admins/
│   └── Admin related functionalities
│
├── code/
│   └── Machine Learning & NLP logic
│
├── assets/
│   └── Static files (CSS, JS, Images)
│
├── media/
│   └── Uploaded files
│
└── venv/
    └── Virtual environment


---

## ▶️ How to Run the Project

1. Clone the repository  
```bash
git clone https://github.com/Vinathi-Karumuri/CODE.git

2.Navigate to project directory

cd CODE

3.Install required packages

pip install -r requirements.txt

4.Run migrations

python manage.py makemigrations

python manage.py migrate

5.Start the server

python manage.py runserver

6.Open browser and visit

http://127.0.0.1:8000/


✅ Features

-->User-friendly web interface

-->Real-time sentiment analysis

-->Supports multiple text inputs

-->WordCloud visualization

-->Accurate sentiment prediction


🎓 Use Case

-->Academic projects

-->Opinion mining

-->Social media analysis

-->Product review analysis


👨‍💻 Developed By

Vinathi Karumuri
Final Year Project
Sentiment Analysis using Machine Learning