# 📘 Bank Customer Churn Prediction

## 🎯 Objective
The purpose of this project is to predict whether a bank customer will churn using machine learning techniques.  
The model helps identify high-risk customers early so that the bank can take corrective actions and improve customer retention.

## 📁 Dataset Used
- **Dataset Name:** Churn Modelling Dataset  
- **Source:** Kaggle  
- **Link:** [Churn Modelling Dataset](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling)  

The dataset contains customer demographic details, account information, credit scores, balances, salary, activity features, and a label indicating whether the customer exited the bank.

## 🤖 Models Used
The following machine learning models were implemented:

- 🔹 **Logistic Regression** – Baseline classification model  
- 🔹 **Decision Tree Classifier** – Captures non-linear patterns  
- 🔹 **Random Forest Classifier** – Ensemble method for higher robustness  
- 🔹 **K-Nearest Neighbors (KNN)** – Distance-based classification  
- 🔹 **Support Vector Machine (SVM)** – Effective for complex boundaries  

These models were chosen to compare linear, tree-based, ensemble, and similarity-based algorithms.

## 📊 Key Results
- **SMOTE oversampling** was used to handle the imbalanced churn dataset.  
- Models were evaluated **before and after hyperparameter tuning**.  
- Evaluation metrics included **Accuracy, Precision, Recall, F1-Score, and AUC**.  
- The **Random Forest model (after tuning)** delivered the best overall performance.  
- SMOTE significantly improved recall and helped models learn minority-class patterns.
