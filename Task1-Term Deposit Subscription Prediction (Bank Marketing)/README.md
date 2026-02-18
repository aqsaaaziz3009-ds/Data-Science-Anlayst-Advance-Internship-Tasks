
# 📊 Term Deposit Subscription Prediction (Bank Marketing)

## Overview

This project focuses on predicting whether a bank customer will subscribe to a term deposit based on historical marketing campaign data. The goal is to help banks identify high-potential customers and improve the efficiency of marketing campaigns.

This task was completed as part of a Data Science Internship assignment.

---

## Objective

* Explore and understand the Bank Marketing dataset
* Perform data cleaning and preprocessing
* Encode categorical features
* Train classification models (Logistic Regression & Random Forest)
* Evaluate models using F1-score, confusion matrix, and ROC curve
* Apply SHAP for explainable AI and model interpretability

---

##  Dataset

**Bank Marketing Dataset**
Source: UCI Machine Learning Repository

The dataset contains customer demographics, financial information, and campaign-related features.

### Target Variable

* **y**

  * 1 → Subscribed
  * 0 → Not Subscribed

---

##  Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* SHAP (Explainable AI)

---

## Workflow

### 1️.Data Preprocessing

* Loaded dataset using pandas
* Handled categorical encoding
* Converted target variable into binary format
* Train-test split (80/20)

---

### 2️.Exploratory Data Analysis (EDA)

* Subscription distribution analysis
* Age distribution visualization
* Job vs subscription comparison
* Data imbalance observations

---

### 3️.Model Building

Two classification models were trained:

* Logistic Regression (baseline model)
* Random Forest (advanced model)

---

### 4️.Model Evaluation

Models were evaluated using:

* Confusion Matrix
* Precision, Recall, F1-score
* ROC Curve comparison

Random Forest performed better overall in predictive performance.

---

###  Explainable AI (SHAP)

SHAP was used to interpret model predictions:

* Feature importance visualization
* Explanation of individual predictions
* Improved model transparency

Key Insight:

* Call duration and previous campaign outcomes were strong predictors of subscription.

---

## Results

* Random Forest achieved higher F1-score compared to Logistic Regression
* SHAP analysis provided meaningful insights into feature impact
* Model can help banks optimize marketing strategies and reduce campaign costs

---

## Key Learnings

* End-to-end classification workflow
* Feature encoding techniques
* Model comparison and evaluation
* Importance of explainable AI in real-world applications

---

## Future Improvements

* Hyperparameter tuning
* Handling class imbalance (SMOTE)
* Testing advanced models like XGBoost
* Deploying model using Streamlit

---

## Project Structure

```
├── Task1.ipynb
├── README.md
└── dataset/
```

---

## Author

**Aqsa Aziz**
Data Science Intern

