# Credit Card Fraud Detection

This project implements machine learning models to detect fraudulent credit card transactions. Using a dataset of European credit card transactions, we developed and compared multiple classification models to identify potentially fraudulent activities.

## Dataset Overview

[Dataset Link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

- Dataset contains credit card transactions from September 2013
- Total transactions: 284,807
- Fraudulent cases: 492 (0.172% of total)
- Features: 28 PCA-transformed variables (V1-V28), Time, Amount, and Class
- Binary classification: Class 1 = Fraud, Class 0 = Normal

## Models Implemented

- Random Forest Classifier
- XGBoost
- Logistic Regression

## Requirements

```
pandas
numpy
scikit-learn
imbalanced-learn
xgboost
matplotlib
seaborn
```

## Key Features

- Data preprocessing and scaling
- Handling class imbalance using SMOTE
- Model training and evaluation
- Performance metrics including:
  - Confusion Matrix
  - Classification Report
  - ROC Curve
  - Precision-Recall Curve


## Performance Evaluation

Due to the highly imbalanced nature of the dataset, we focus on the Area Under the Precision-Recall Curve (AUPRC) as the primary evaluation metric.

## License

This project is licensed under the **```APACHE 2.0```** License - see the LICENSE file for details.

## Acknowledgments

The dataset was obtained from [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). Due to confidentiality, the original features have been transformed using PCA.
