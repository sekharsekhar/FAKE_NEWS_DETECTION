# Fake News Detection

## Overview
This project is a **Fake News Detection** system built using **Python** and **Machine Learning**.  
It allows users to input a news article and predicts whether it is **real** or **fake**.

The project uses:
- **Streamlit** for the frontend interface
- **Joblib** to load pre-trained models
- **Scikit-learn** for machine learning and text vectorization

---

## Features
- User-friendly interface to input news articles
- Real-time prediction of fake vs. real news
- Shows a clear success message for real news and error message for fake news
- Easy to deploy using Streamlit

---

## Installation
1. Clone the repository:
```bash
git clone https://github.com/sekharsekhar/FAKE_NEWS_DETECTION.git

Install required libraries:

pip install streamlit scikit-learn joblib


Make sure the model files model.jb and vectorizer.jb are in the project folder.


Usage

Run the Streamlit app:

streamlit run demo.py


Enter a news article in the text area.

Click "Check News".

The app will predict whether the news is Real or Fake.

##File Structure
FAKE_NEWS_DETECTION/
│
├─ demo.py             # Streamlit frontend code
├─ model.jb            # Pre-trained ML model
├─ vectorizer.jb       # Text vectorizer
└─ README.md           # Project documentation

##Technologies Used
Python
Streamlit
Scikit-learn
Joblib

Author
Telukala Sekhar
Email: telukulasekhar1319@gmail.com
