# 📧 Spam Mail Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-success)

A Machine Learning project that classifies emails as **Spam** or **Ham** using **TF-IDF Vectorization** and **Logistic Regression**.

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Project Workflow](#-project-workflow)
- [Dataset](#-dataset)
- [Machine Learning Pipeline](#-machine-learning-pipeline)
- [Model Used](#-model-used)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Running the Project](#-running-the-project)
- [Sample Prediction](#-sample-prediction)
- [Future Improvements](#-future-improvements)
- [Learning Outcomes](#-learning-outcomes)
- [Author](#-author)
- [License](#-license)

## 📌 Overview
This project demonstrates spam email classification using Natural Language Processing (NLP) and Machine Learning. It preprocesses text, extracts TF‑IDF features, trains a Logistic Regression model, evaluates performance, and predicts whether new messages are spam.

## ✨ Features
- Spam/Ham classification
- TF‑IDF feature extraction
- Logistic Regression model
- Data preprocessing
- Model evaluation
- Custom email prediction

## 🛠 Technologies Used
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## 🔄 Project Workflow
```text
Dataset → Cleaning → Label Encoding → Train/Test Split → TF‑IDF → Logistic Regression → Evaluation → Prediction
```

## 📂 Dataset
The dataset contains two columns:
- **Category**: Spam or Ham
- **Message**: Email/SMS content

## 🤖 Machine Learning Pipeline
1. Load dataset with Pandas.
2. Handle missing values.
3. Encode labels (HAM=1, SPAM=0).
4. Split data into training/testing sets.
5. Convert text to TF‑IDF vectors.
6. Train Logistic Regression.
7. Evaluate accuracy.
8. Predict custom messages.

## 🧠 Model Used
**Logistic Regression**
- Fast and efficient
- Suitable for binary classification
- Performs well with TF‑IDF features

## 📁 Project Structure
```text
spam-mail-detection/
├── JL1955_MINOR.ipynb
├── mail_data.csv
├── README.md
└── requirements.txt
```

## ⚙ Installation
```bash
git clone https://github.com/Abhishek-09-Tomar/spam-mail-detection.git
cd spam-mail-detection
pip install -r requirements.txt
```

## ▶ Running the Project
```bash
jupyter notebook
```
Open `JL1955_MINOR.ipynb` and run all cells.

## 💻 Sample Prediction

Input:
```text
Congratulations! You won a FREE iPhone.
```
Output:
```text
Spam
```

Input:
```text
Hi, can we meet tomorrow?
```
Output:
```text
Ham
```

## 🚀 Future Improvements
- SVM and Naive Bayes comparison
- Hyperparameter tuning
- Flask/Streamlit deployment
- Deep Learning (LSTM/BERT)

## 📚 Learning Outcomes
- NLP basics
- TF‑IDF Vectorization
- Logistic Regression
- Text Classification
- Model Evaluation

## 👨‍💻 Author

**Abhishek Tomar**

B.Tech Computer Science Engineering

Aspiring Software Engineer | AI & Machine Learning Enthusiast | Backend Developer

**GitHub Repository:** https://github.com/Abhishek-09-Tomar/spam-mail-detection

## 📄 License
This project is intended for educational and learning purposes.

⭐ If you found this project useful, consider giving it a Star!
