# Hate Speech Detection using Machine Learning & NLP

This repository contains a project focused on detecting hate speech in textual data using machine learning and natural language processing (NLP) techniques. The goal is to classify whether a given tweet or text contains hate speech, offensive language, or is clean.

---

## 📌 Features

- Text preprocessing (lowercasing, punctuation removal, stopword filtering, etc.)
- Exploratory Data Analysis (EDA) and visualization
- Feature extraction using TF-IDF
- Multiple classification models: Logistic Regression, Naive Bayes, SVM, etc.
- Model evaluation using accuracy, precision, recall, F1-score
- Confusion matrix visualization

---

## 🧪 Dataset

The dataset used for this project is a publicly available labeled dataset containing tweets annotated as:
- `0` → Hate Speech
- `1` → Offensive Language
- `2` → Neither

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- NLTK

---

## 🔍 Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/hate-speech-detection-ml-nlp.git
   cd hate-speech-detection-ml-nlp

2.Install required packages:
pip install -r requirements.txt

3.Run the notebook:
jupyter notebook Hate_speech_detection.ipynb
