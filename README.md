# Credit Scoring Model

## CodeAlpha Machine Learning Internship

A Machine Learning project that predicts whether a loan is likely to be fully paid or not.

## Project Overview

Credit scoring helps financial institutions assess the risk associated with lending money to borrowers.

In this project, machine learning classification algorithms are used to predict loan repayment behavior based on financial and credit-related features.

## Dataset

The project uses a loan dataset containing financial and credit-related information about borrowers.

The target variable is:

- `0` - Fully Paid
- `1` - Not Fully Paid

The dataset contains features such as:

- Interest Rate
- Installment
- Annual Income
- Debt-to-Income Ratio
- FICO Score
- Revolving Balance
- Revolving Utilization
- Recent Credit Inquiries
- Public Records
- Delinquencies

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab

## Machine Learning Models

The following classification models were implemented:

1. Logistic Regression
2. Random Forest Classifier

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- ROC Curve

## Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Check for missing values
5. Analyze the target variable
6. Preprocess the data
7. Encode categorical features
8. Split data into training and testing sets
9. Train Logistic Regression
10. Train Random Forest
11. Evaluate both models
12. Compare model performance
13. Select the best model
14. Save the trained model
15. Make sample predictions

## Project Files

- `CodeAlpha_CreditScoringModel.ipynb` - Complete Google Colab notebook
- `credit_scoring_model.pkl` - Trained machine learning model

## Conclusion

This project demonstrates how machine learning can be applied to credit risk and loan repayment prediction.

Logistic Regression and Random Forest were trained and evaluated using multiple performance metrics, and the better-performing model was selected as the final model.

## Internship

This project was completed as part of the **CodeAlpha Machine Learning Internship**.
