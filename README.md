# Credit Card Fraud Detection Project

## Project Description
This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset used is highly imbalanced, with very few fraudulent cases.

## Dataset
- Source: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- ~284,000 transactions, 30 features + target (fraud or not).

## Model
- Algorithm: Random Forest Classifier
- Libraries: Scikit-learn, Pandas, NumPy, Seaborn, Matplotlib

## Results
- Accuracy: ~99% (due to class imbalance)
- Precision and Recall: Focus on Recall for Fraud class (minimize false negatives)
- ROC-AUC Score: > 0.95

## Visualizations
- Class distribution plot
- Confusion matrix
- Feature importance
- ROC-AUC curve

## Conclusion
The model effectively detects fraudulent transactions with high ROC-AUC score. Further improvements can include balancing techniques like SMOTE, tuning hyperparameters, and using ensemble models.

---

Made as part of AI/ML Internship Project - 2025.
