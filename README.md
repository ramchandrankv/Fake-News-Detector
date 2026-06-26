# 📰 AI-Powered Fake News Detector

An AI-powered web application that predicts whether a news article is **Real** or **Fake** using Machine Learning. Users can enter any news text, and the model classifies it instantly through a simple Streamlit interface.

---

## 🚀 Features

- Detects Fake or Real news articles
- Simple and user-friendly web interface
- Machine Learning based prediction
- Text preprocessing using TF-IDF
- Fast predictions
- Easy to deploy on Streamlit Community Cloud

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Streamlit
- Git & GitHub

---

## 📂 Project Structure

```
fake-news-detector/
│
├── app.py                  # Streamlit application
├── train_model.py          # Model training script
├── model.pkl               # Trained ML model
├── vectorizer.pkl          # TF-IDF Vectorizer
├── requirements.txt
├── README.md
│
├── data/
│   ├── Fake.csv
│   └── True.csv
│
└── notebooks/
    └── FakeNewsDetector.ipynb
```

---

## 📊 Dataset

This project uses the Fake and Real News Dataset from Kaggle.

Dataset Link:

https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

The dataset contains:

- Fake news articles
- Real news articles

---

## 🤖 Machine Learning Pipeline

1. Load Dataset
2. Merge Fake and Real datasets
3. Clean the data
4. Convert text into numerical vectors using TF-IDF
5. Train Logistic Regression model
6. Save trained model
7. Predict user input through Streamlit

---

## 📈 Model Used

- Logistic Regression

Vectorization:

- TF-IDF Vectorizer

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/fake-news-detector.git
```

Move into the project

```bash
cd fake-news-detector
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

## 💻 Usage

1. Open the Streamlit application.
2. Paste a news article.
3. Click **Predict**.
4. The application displays:

- ✅ Real News
- ❌ Fake News


---

## 🌐 Deployment

The application can be deployed using:

- Streamlit Community Cloud
- Hugging Face Spaces

---

## 📌 Future Improvements

- Deep Learning models
- BERT-based classification
- News URL prediction
- Explainable AI (SHAP/LIME)
- News source credibility analysis
- Multi-language support

---

## 👨‍💻 Author

Ramachandran K V

GitHub:
https://github.com/ramchandrankv

LinkedIn:
https://linkedin.com/in/ramchandrankv

---



This project is created for educational purposes as part of the IBM SkillsBuild - Edunet Foundation AI & ML Virtual Internship.
