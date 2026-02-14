# ML Assignment 2 - Classification Models & Streamlit Deployment

## (a) Problem Statement
The objective of this project is to build and compare multiple Machine Learning classification models to predict whether a bank customer will subscribe to a term deposit (yes/no). The project also includes deployment of the trained models using a Streamlit web application.

---

## (b) Dataset Description
**Dataset Name:** UCI Bank Marketing Dataset (bank-full.csv)  
**Total Rows:** 45,211  
**Total Features (Input):** 16  
**Target Column:** y (yes/no)  
**Problem Type:** Binary Classification

---

## (c) Models Used and Performance Metrics

| ML Model | Accuracy | AUC | Precision | Recall | F1 | MCC |
|---------|----------|-----|----------|--------|----|-----|
| Logistic Regression |  |  |  |  |  |  |
| Decision Tree |  |  |  |  |  |  |
| KNN |  |  |  |  |  |  |
| Naive Bayes |  |  |  |  |  |  |
| Random Forest |  |  |  |  |  |  |
| XGBoost |  |  |  |  |  |  |


---

## (d) Model Observations

| Model | Observation |
|------|------------|
| Logistic Regression | Performs well as a baseline model and provides stable results on scaled features. |
| Decision Tree | Can give good results but may overfit depending on tree depth. |
| KNN | Sensitive to feature scaling and value of k, performance may vary. |
| Naive Bayes | Very fast and simple model, but assumes feature independence. |
| Random Forest | Provides robust performance and reduces overfitting compared to single trees. |
| XGBoost | Generally performs very well on structured/tabular datasets due to boosting. |

---

## Streamlit Application Features
- Upload CSV test dataset
- Select a classification model
- Predict outputs
- Display evaluation metrics (Accuracy, AUC, Precision, Recall, F1, MCC)
- Show confusion matrix and classification report
- Download predictions as CSV

---

## How to Run Locally
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
