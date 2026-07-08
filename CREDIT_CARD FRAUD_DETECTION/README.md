# Credit Card Fraud Detection

This project is part of the **CodSoft Machine Learning Internship (Task 3)**.

## Objective

The objective of this project is to build a machine learning model that identifies fraudulent credit card transactions. The project includes data preprocessing, handling class imbalance, model training, and evaluation using classification metrics.

## Dataset

The dataset contains anonymized credit card transaction data with the following features:

- Time
- V1 to V28 (anonymized features)
- Amount
- Class (Target Variable)

`Class = 0` → Genuine Transaction

`Class = 1` → Fraudulent Transaction

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

## Machine Learning Algorithm

- Logistic Regression

## Project Workflow

1. Loaded the dataset.
2. Explored and analyzed the data.
3. Normalized the Amount feature.
4. Split the dataset into training and testing sets.
5. Handled class imbalance using Random Oversampling.
6. Trained a Logistic Regression model.
7. Predicted fraudulent transactions.
8. Evaluated the model using Precision, Recall, F1-Score, and Confusion Matrix.

## Evaluation Metrics

- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

## Repository Contents

- `Credit_Card_Fraud_Detection.ipynb`
- `creditcard.csv`
- `README.md`

## Future Improvements

- Compare multiple classification algorithms.
- Use SMOTE for synthetic oversampling.
- Perform hyperparameter tuning.
- Deploy the model using Streamlit or Flask.

---

**CodSoft Machine Learning Internship – Task 3**
