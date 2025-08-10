# PCOS-Prediction-using-Feature-Selection-and-Ensemble-Learning

This project implements a machine learning framework for predicting PCOS (Polycystic Ovary Syndrome) using multiple feature selection techniques and ensemble learning models.

## 🚀 Features
- Applied **GA**, **Mutual Information**, **Boruta**, and **Hybrid (Union)** feature selection.
- Trained **baseline models** (Random Forest, Logistic Regression, SVM, KNN, Naive Bayes, MLP) and **ensemble models** (Voting, Stacking, RSBE, XGBoost, LightGBM).
- Achieved **92.02% accuracy** using Boruta + RSBE and **95.45% precision** with Union + Random Forest.
- Implemented hyperparameter tuning, normalization, and model evaluation with ROC, AUC, confusion matrices.

## 📊 Results Summary
| Feature Selection | Best Model        | Accuracy | F1 Score | Precision | Specificity |
|-------------------|------------------|----------|----------|-----------|-------------|
| Boruta            | RSBE             | 92.02%   | 87.62    | 88.46%    | 94.55%      |
| Union             | Random Forest    | 92.02%   | 86.60    | 95.45%    | 98.18%      |
| MI                | Random Forest    | 91.41%   | 86.00    | 91.49%    | 96.36%      |
