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

```
[[649 212]
 [176 702]]
```

| Actual \ Predicted | Predicted: No Heart Risk | Predicted: Heart Risk |
|--------------------|-------------------------:|----------------------:|
| **No Heart Risk**  | 649 (TN)                 | 212 (FP)              |
| **Heart Risk**     | 176 (FN)                 | 702 (TP)              |

### Classification Report

| Class | Precision | Recall | F1-Score |
|------|----------:|--------:|---------:|
| No Heart Risk | 0.79 | 0.75 | 0.77 |
| Heart Risk | 0.77 | 0.80 | 0.78 |

**Overall Accuracy:** **77.69%**

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
