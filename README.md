# Classification-with-Logistic-Regression-Task4
# Logistic Regression - Binary Classification Task

This project demonstrates how to apply **Logistic Regression** to a **binary classification problem** using a structured dataset. The goal is to predict whether a sample belongs to class 0 or class 1.

---

# Dataset

- **Source**: Breast Cancer Dataset (or uploaded CSV: `data.csv`)
- **Target Column**: Binary class label (e.g., malignant vs benign)

# Steps Covered

# 1. Data Preprocessing
- Loaded the dataset using `pandas`
- Checked and handled missing values (NaNs) using `SimpleImputer`
- Performed train/test split (80/20)
- Standardized the features using `StandardScaler`

# 2. Logistic Regression Model
- Fitted a logistic regression model using `sklearn.linear_model.LogisticRegression`
- Predicted class labels and class probabilities

# 3. Evaluation
- Evaluated model performance using:
  - Confusion Matrix
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC Score
- Plotted ROC Curve for better visualization


## 📊 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`

