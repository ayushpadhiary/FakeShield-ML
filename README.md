# 🛡️ FakeShield - Fake News Detection using Machine Learning

## 📌 Overview

FakeShield is a Machine Learning project that detects whether a news article is **Real** or **Fake** using Natural Language Processing (NLP) techniques and multiple classification algorithms.

The project preprocesses news articles, converts text into numerical features using **TF-IDF Vectorization**, trains multiple machine learning models, and compares their performance.

---

## ✨ Features

- Data Cleaning and Preprocessing
- Stopword Removal
- Stemming using NLTK
- TF-IDF Vectorization
- Multiple Machine Learning Models
- Accuracy Comparison
- Classification Report
- Confusion Matrix
- Fake News Prediction

---

## 🧠 Machine Learning Models Used

- Logistic Regression
- Multinomial Naive Bayes
- Random Forest Classifier
- Passive Aggressive Classifier

---

## 📂 Dataset

The project uses two datasets:

- Fake.csv
- True.csv

These datasets are merged, shuffled, and preprocessed before training.

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

```
FakeShield-ML
│
├── dataset/
│   ├── Fake.csv
│   └── True.csv
│
├── notebook/
│   └── FakeShield.ipynb
│
├── models/
│
├── images/
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/ayushpadhiary/FakeShield-ML.git
```

Go to the project directory

```bash
cd FakeShield-ML
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open the notebook and run all cells.

---

## 📊 Workflow

1. Load Dataset
2. Data Cleaning
3. Text Preprocessing
4. TF-IDF Vectorization
5. Train Machine Learning Models
6. Evaluate Performance
7. Predict News Authenticity

---

## 🔮 Future Improvements

- Deep Learning models (LSTM/BERT)
- Web Application using Flask or Streamlit
- Real-time News Detection
- Model Deployment
- API Integration

---

## 👨‍💻 Author

**Ayush Kumar Padhiary**

GitHub: https://github.com/ayushpadhiary

---

## 📜 License

This project is licensed under the MIT License.