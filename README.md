# Telco Customer Churn Prediction

This project analyzes customer data from a fictional telecommunications company to predict **churn**  whether a customer is likely to cancel their subscription. The goal is to apply classification models using Python and evaluate their effectiveness using multiple metrics.

## Tools & Libraries

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook

## Workflow

### Data Exploration
- Summary statistics
- Visual analysis (histograms, count plots, etc.)
- Handling missing values

### Preprocessing
- Label Encoding for binary categorical variables
- One-Hot Encoding for multi-category variables
- Feature scaling using `StandardScaler`

### Modeling
- Logistic Regression
- Random Forest Classifier

### Evaluation
- Accuracy and Confusion Matrix
- ROC Curve and AUC Score
- Classification Report
- Feature Importance (Random Forest)

## Files

- `analysis.ipynb`: Full notebook including preprocessing, modeling, and evaluation
- `WA_Fn-UseC_-Telco-Customer-Churn.csv`: Dataset used (Telco Customer Churn)
