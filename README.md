# Credit Card Fraud Detection using Machine Learning

This project applies machine learning techniques to detect fraudulent credit card transactions. It includes data preprocessing, handling class imbalance, model training, evaluation, and comparison of multiple classification algorithms.

## 📁 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Description: The dataset contains transactions made by European cardholders in September 2013. It includes 284,807 transactions, out of which 492 are fraudulent.

## 🧠 Algorithms Used

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

## ⚙️ Techniques Applied

- Feature Scaling (StandardScaler)
- Random Oversampling to address class imbalance
- Evaluation using Accuracy, Precision, Recall, F1-Score, and ROC AUC
- Visualization using Confusion Matrices and ROC Curves

## 🏆 Best Model

- **XGBoost Classifier** showed the highest ROC AUC (0.9862) with balanced precision and recall.
- It was selected as the most effective model for fraud detection in this project.

## 📊 Results Summary

| Model               | Precision | Recall | F1-Score | ROC AUC |
|---------------------|-----------|--------|----------|---------|
| Logistic Regression | 0.33      | 0.89   | 0.48     | 0.9679  |
| XGBoost             | 0.80      | 0.84   | 0.82     | 0.9862  |
| Random Forest       | 0.84      | 0.84   | 0.84     | 0.9710  |
| Decision Tree       | 0.72      | 0.68   | 0.70     | 0.8417  |

## 📁 Project Structure

