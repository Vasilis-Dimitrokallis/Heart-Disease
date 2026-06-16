# Heart Disease Prediction: A Machine Learning Approach

## 📌 Project Overview
This project focuses on predicting the presence of heart disease in patients based on their medical and biometric data. The goal is to build a reliable classification model that can assist medical professionals in early diagnosis.

## ⚙️ Methodology & Models
Three different machine learning algorithms were trained and evaluated:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**

## 📊 Evaluation Metric Choice: Why F2-Score?
In the medical field, a **False Negative** (predicting a patient is healthy when they actually have heart disease) is far more dangerous than a False Positive. Therefore, standard Accuracy is not enough. 

This project specifically evaluates models using the **F2-Score**, which puts more weight on **Recall** (minimizing False Negatives) while keeping False Positives at an acceptable level.

## 🏆 Key Findings
* **Best Performing Model:** **Logistic Regression** achieved the highest Accuracy and F2-Score.
* **Interpretability:** Beyond raw performance, Logistic Regression was chosen as the optimal model for medical use due to its high interpretability. By analyzing the model's coefficients, doctors can easily identify which symptoms or features are the strongest indicators of heart disease risk.
* Decision Trees provided the lowest performance among the tested models.

## 📂 Repository Structure
```text
├── data/
│   └── heart.csv                   # The dataset containing patient biometrics
├── notebooks/
│   └── heart_disease_prediction.ipynb  # Main analysis and modeling notebook
├── README.md
└── requirements.txt
