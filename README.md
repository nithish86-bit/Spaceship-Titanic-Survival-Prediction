# 🚀 Spaceship Titanic Survival Prediction

## 📌 Project Overview

This project predicts whether passengers were transported to an alternate dimension using the **Spaceship Titanic** dataset from Kaggle.

The project demonstrates a complete Machine Learning workflow, including data preprocessing, feature engineering, model building, evaluation, and prediction using **Logistic Regression**.

---

## 📊 Dataset

**Dataset Source:**  
https://www.kaggle.com/competitions/spaceship-titanic

**Files Used:**
- `train.csv`
- `test.csv`
- `submission.csv`

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

## 📊 Model Performance

### Accuracy
**Accuracy:** **77.69%**

### ROC-AUC Score
**ROC-AUC Score:** **0.8620**

### Confusion Matrix

```
[[649 212]
 [176 702]]
```

| Actual | Predicted: False | Predicted: True |
|---------|-----------------:|----------------:|
| **False** | 649 (True Negative) | 212 (False Positive) |
| **True** | 176 (False Negative) | 702 (True Positive) |

### Classification Report

| Class | Precision | Recall | F1-Score | Support |
|------|----------:|--------:|---------:|--------:|
| False | 0.79 | 0.75 | 0.77 | 861 |
| True | 0.77 | 0.80 | 0.78 | 878 |

**Overall Accuracy:** **77.69%**

### Macro Average

| Metric | Score |
|--------|------:|
| Precision | 0.78 |
| Recall | 0.78 |
| F1-Score | 0.78 |

### Weighted Average

| Metric | Score |
|--------|------:|
| Precision | 0.78 |
| Recall | 0.78 |
| F1-Score | 0.78 |

---
# 📷 Project Screenshots

## 1. Dataset Preview (`train.head()`)

Displays the first five rows of the Spaceship Titanic dataset.

![Dataset Preview](images/dataset_preview.png)

---

## 2. Dataset Information (`train.info()`)

Displays column names, data types, and missing values.

![Dataset Information](images/dataset_info.png)

---

## 3. Model Accuracy (`accuracy_score`)

Shows the validation accuracy.

![Accuracy](images/accuracy.png)

---

## 4. Confusion Matrix (`ConfusionMatrixDisplay`)

Shows model predictions versus actual values.

![Confusion Matrix](images/confusion_matrix.png)

---

## 5. Classification Report (`classification_report`)

Shows Precision, Recall, F1-Score, and Support.

![Classification Report](images/classification_report.png)

---

## 6. ROC-AUC Score (`roc_auc_score`)

Shows the ROC-AUC score of the model.

![ROC-AUC Score](images/roc_auc.png)

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

- Random Forest Classifier
- XGBoost Classifier
- Hyperparameter Tuning
- Feature Selection
- Cross Validation
- Model Deployment using Streamlit or Flask

---

## 👨‍💻 Author

**Nithish Ramesh**
