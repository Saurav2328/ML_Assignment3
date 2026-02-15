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
| Logistic Regression |0.9012|0.9056|0.6445|0.3478|0.4518|0.4261|
| Decision Tree       |0.8746|0.7015|0.4649|0.4754|0.4701|0.399 |
| KNN |0.8986|0.85  |0.6257 |0.3318|0.4336|0.407|
| Naive Bayes |0.8548|0.8101|0.4059|0.5198|0.4559|0.3774|
| Random Forest |0.8977|0.9205|0.7195|0.206|0.3204|0.349 |
| XGBoost |0.9108|0.9344|0.6649|0.4783|0.5563|0.5167|


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
