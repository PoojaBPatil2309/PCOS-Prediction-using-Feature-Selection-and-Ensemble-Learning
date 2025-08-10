Project Overview
This project focuses on the prediction of Polycystic Ovary Syndrome (PCOS) using advanced machine learning techniques, supported by optimized feature selection and ensemble learning strategies. The goal is to develop a robust and explainable diagnostic model that assists in early detection of PCOS using clinical and laboratory data.


Key Contributions
Applied Boruta, Mutual Information, and Genetic Algorithm (GA) for feature selection.

Built multiple ML models including XGBoost, LightGBM, CatBoost, and Stacking Ensemble classifiers.

Handled class imbalance using SMOTE and improved model generalization.

Achieved top performance with XGBoost + Boruta (Accuracy: 95.89%, Recall: 95.4%).

Visualized model results using ROC curves, confusion matrices, and feature importance plots.



Tools & Libraries
scikit-learn, xgboost, lightgbm, catboost, boruta_py

pandas, numpy, matplotlib, seaborn, imblearn





Evaluation Metrics
Accuracy, Precision, Recall, F1-Score, AUC, and Specificity were used for evaluation.

Ensemble models outperformed base classifiers, with the best results from stacking and optimized feature sets.




How to Use
Load the dataset and perform preprocessing.

Select features using any of the implemented methods (Boruta, GA, MI).

Train and evaluate ML models.

Review performance metrics and plots to interpret model behavior.