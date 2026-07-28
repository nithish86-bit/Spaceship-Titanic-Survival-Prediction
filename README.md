# 🚀 Spaceship Titanic Survival Prediction

## 📌 Project Overview

This project predicts whether passengers were transported to an alternate dimension using the Spaceship Titanic dataset from Kaggle.

The project demonstrates a complete Machine Learning workflow including data preprocessing, exploratory data analysis, feature engineering, model building, evaluation, and prediction.

---

## 📊 Dataset

Dataset Source:
https://www.kaggle.com/competitions/spaceship-titanic

Files Used:
- train.csv
- test.csv
- submission.csv

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🤖 Machine Learning Model

- Logistic Regression

---

## 📈 Workflow

- Data Cleaning
- Missing Value Treatment
- Encoding Categorical Variables
- Feature Engineering
- Train-Test Split
- Model Training
- Model Evaluation
- Prediction on Test Dataset

---

## 📈 Model Performance

### Accuracy
- **Accuracy:** **77.69%**

### ROC-AUC Score
- **ROC-AUC Score:** **0.8620**

### Confusion Matrix

```text
[[649 212]
 [176 702]]
```

| Actual \ Predicted | Predicted: False | Predicted: True |
|--------------------|-----------------:|----------------:|
| **False**          | 649 (True Negative) | 212 (False Positive) |
| **True**           | 176 (False Negative) | 702 (True Positive) |

### Classification Report

| Class | Precision | Recall | F1-Score | Support |
|------|----------:|--------:|---------:|--------:|
| False | 0.79 | 0.75 | 0.77 | 861 |
| True | 0.77 | 0.80 | 0.78 | 878 |

**Overall Accuracy:** **77.69%**

**Macro Average**
- Precision: **0.78**
- Recall: **0.78**
- F1-Score: **0.78**

**Weighted Average**
- Precision: **0.78**
- Recall: **0.78**
- F1-Score: **0.78**

---

## 📂 Repository Structure

```
Spaceship-Titanic-Survival-Prediction/
│
├── Spaceship_Titanic.ipynb
├── train.csv
├── test.csv
├── submission.csv
└── README.md
```

---

## 🎯 Future Improvements

- Random Forest
- XGBoost
- Hyperparameter Tuning
- Feature Selection

---

## 👨‍💻 Author

Nithish Ramesh
