# 🔍 Fake Job Detector
AI-Powered Scam Job Post Analyzer using NLP & Machine Learning

---
## 🚀 Live Demo

👉 https://your-app-name.streamlit.app](https://fakejobsdetection-jgah5xrk36fhcn9d8gujun.streamlit.app/

## 📌 Overview

Fake Job Detector is a Streamlit-based web application that analyzes job postings and estimates the probability that they are scams.

It combines rule-based red flag detection with a Machine Learning classifier to identify suspicious patterns commonly found in fake job listings such as:

- Unrealistic salary promises  
- Urgent hiring pressure  
- WhatsApp / Telegram contact requests  
- Poor grammar and excessive punctuation  
- “No experience needed” high-income offers  

The goal is to help job seekers make safer decisions before sharing personal information or paying fraudulent fees.

---

## 🧠 How It Works

### 1️⃣ Rule-Based Analysis
Regular expressions and keyword detection identify common scam indicators:
- Urgency language (e.g., “urgent hiring”, “start immediately”)
- Unrealistic salary claims
- Informal communication channels
- Too-good-to-be-true promises
- Lack of professional terminology

### 2️⃣ Machine Learning Model
- Text is converted into numerical features using TF-IDF Vectorization
- A Logistic Regression classifier predicts scam probability
- The ML output is combined with rule-based indicators

### 3️⃣ Scam Probability Score
A weighted scoring system generates a final risk percentage (0–100%) categorized as:
- ✅ Low Risk  
- ⚠️ Medium Risk  
- ❌ High Risk  

---

## 🚀 Features

- Paste any job post for instant analysis  
- Scam probability percentage score  
- Visual progress bar indicator  
- Detailed red flag breakdown  
- Clear explanation of detected issues  
- Risk-based recommendations  
- Educational Red Flag Guide  
- Safety checklist for job seekers  

---

## 🛠️ Tech Stack

- Python  
- Streamlit  
- Scikit-learn  
  - TfidfVectorizer  
  - LogisticRegression  
- Regex-based NLP  
- Pandas  
- NumPy  

---
