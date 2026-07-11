# 🛡️ AI JobShield

## Intelligent Fake Job Detection and Verification System

AI JobShield is a Machine Learning-based web application that detects whether a job posting is **Genuine** or **Fake**. The system uses **Natural Language Processing (NLP)** and **TF-IDF Vectorization** with a **Logistic Regression** classifier to analyze job descriptions and help job seekers avoid recruitment scams.

---

## 📌 Project Overview

Fake job postings have become a major problem across online job portals. Many fraudulent recruiters trick applicants by demanding registration fees, requesting personal documents, or promising unrealistic salaries.

AI JobShield automatically analyzes the text of a job posting and predicts whether it is genuine or fraudulent with high accuracy.

---

## 🎯 Objectives

- Detect fake job postings automatically.
- Help job seekers identify recruitment scams.
- Reduce financial fraud and identity theft.
- Provide an easy-to-use web application.

---

## ✨ Features

- Detects Genuine or Fake job postings
- Uses Machine Learning for prediction
- Displays prediction confidence score
- Provides safety recommendations
- User-friendly Streamlit interface
- Fast real-time prediction

---

## 🧠 Machine Learning Model

| Item | Details |
|------|---------|
| Algorithm | Logistic Regression |
| Feature Extraction | TF-IDF Vectorization |
| Accuracy | **96.6%** |
| Dataset | Fake Job Postings Dataset (Kaggle) |

---

## 📊 Dataset

**Source:** Kaggle Fake Job Postings Dataset

Dataset Statistics

- Total Job Posts: **17,880**
- Genuine Jobs: **17,014**
- Fake Jobs: **866**

Important Features

- Job Title
- Company Profile
- Description
- Requirements
- Benefits
- Employment Type
- Industry
- Fraudulent Label

---

## ⚙️ Technologies Used

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-learn
- Joblib
- Streamlit

### Development Tools

- Google Colab
- Visual Studio Code

---

## 🏗 Project Workflow

```
Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Text Preprocessing
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Logistic Regression
      │
      ▼
Prediction
      │
      ▼
Streamlit Web Application
```

---

## 📂 Project Structure

```
AI-JobShield/
│
├── app.py
├── jobshield_model.pkl
├── tfidf_vectorizer.pkl
├── README.md
├── requirements.txt
└── screenshots/
      ├── Homepage.png
      └── final_output(genuine and fake prediction).png
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/syed-modhinbi/AI-JobShield.git
```

Move into the project folder

```bash
cd AI-JobShield
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 💻 Application Demo

### Genuine Job Prediction

- Predicts genuine job postings
- Displays confidence score
- Recommends applying through official company portals

### Fake Job Prediction

- Detects suspicious job postings
- Displays confidence score
- Warns users about registration fees, WhatsApp-only recruiters, and sharing personal information

---

## 📈 Results

- Model Accuracy: **96.6%**
- Fast prediction using TF-IDF + Logistic Regression
- Easy-to-use Streamlit interface
- Reliable classification of fake job postings

---

## 🔮 Future Enhancements

- Browser Extension
- Multi-language Support
- BERT/RoBERTa Integration
- Company Verification API
- Email Scam Detection
- Resume–Job Matching
- Mobile Application
- Real-time Job Portal Integration

---

## 👨‍💻 Developed By

**Syed Modhinbi**

B.Tech Computer Science & Engineering

KKR & KSR Institute of Technology & Sciences

Engineering Internship Project

---

## 📜 License

This project is developed for educational and internship purposes.
