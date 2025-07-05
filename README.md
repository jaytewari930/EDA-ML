# 🩺 Diabetes Prediction using Machine Learning

This project aims to predict whether a person has diabetes based on various medical parameters using different machine learning models, including Logistic Regression, Random Forest, and LightGBM.

---

## 📁 Dataset

- **Source**: [Plotly Dataset - Diabetes](https://raw.githubusercontent.com/plotly/datasets/master/diabetes.csv)
- The dataset contains 768 records and 9 columns:
  - `Pregnancies`, `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`, `DiabetesPedigreeFunction`, `Age`, `Outcome`

---

## 🧠 Models Used

- Logistic Regression
- Random Forest Classifier (with GridSearchCV)
- LightGBM Classifier (with Hyperparameter tuning)

---

## 📊 Evaluation Metrics

- **Accuracy**
- **Confusion Matrix**
- **Precision, Recall, F1-score**
- **Heatmap Visualization**

---

## 📈 Performance Summary

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression (normalized) | ~75.3%   |
| Random Forest (tuned)           | ~75.9%   |
| LightGBM                        | ~77-78%  |

> Note: Performance may vary slightly due to dataset imbalance and randomness in model training.

---

## 📉 Data Preprocessing

- Missing/zero values replaced with column mean
- Normalization using `StandardScaler`
- Train-test split (80/20)

---

## 📌 Visualizations

- Confusion Matrix Heatmaps (seaborn)
- 3D Scatter plot for `Glucose`, `Insulin`, `Age` vs `Outcome`
- Boxplots to visualize distribution by Outcome

---
