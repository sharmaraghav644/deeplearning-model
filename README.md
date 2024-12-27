# Loan Default Prediction using Deep Learning

## Description

In this project, we build a deep learning model to predict whether or not a loan will default using historical data. The dataset includes loan information from 2007 to 2015 and contains various features that help determine whether a loan will be defaulted. This project is crucial for companies like Lending Club, where accurate prediction of loan defaults is key to minimizing risk.

The dataset is highly imbalanced and contains a large number of features, making it a challenging problem for deep learning models. We perform **exploratory data analysis (EDA)**, **feature engineering**, and **deep learning** techniques to predict loan defaults.

## Table of Contents

1. [Description](#description)
2. [Technology Used](#technology-used)
3. [Dependencies](#dependencies)
4. [Project Insights](#project-insights)

## Technology Used

- **Pandas**: For data manipulation and preprocessing.
- **Numpy**: For numerical computations and data handling.
- **Keras**: For building and training the deep learning model.
- **TensorFlow**: Backend for deep learning computations.
- **Matplotlib** and **Seaborn**: For visualizations and data analysis.
- **Scikit-learn**: For additional machine learning utilities like scaling and splitting the data.

## Dependencies

- `pandas`
- `numpy`
- `keras`
- `tensorflow`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Project Insights

### Key Features in the Dataset:

- **credit.policy**: Indicator of whether the borrower meets the credit underwriting criteria.
- **purpose**: The purpose of the loan (e.g., credit card, debt consolidation, etc.).
- **int.rate**: The interest rate assigned to the loan.
- **installment**: The monthly payment owed by the borrower.
- **log.annual.inc**: The natural log of the borrower’s annual income.
- **dti**: Debt-to-income ratio.
- **fico**: Borrower’s FICO credit score.
- **days.with.cr.line**: The number of days the borrower has had a credit line.
- **revol.bal**: Borrower’s revolving balance (credit balance at month-end).
- **revol.util**: Borrower’s revolving line utilization ratio.
- **inq.last.6mths**: Number of inquiries by creditors in the past 6 months.
- **delinq.2yrs**: Number of times the borrower was 30+ days past due on a payment in the past 2 years.
- **pub.rec**: Number of derogatory public records (bankruptcies, tax liens, etc.).

### Steps Performed:

1. **Exploratory Data Analysis (EDA)**: Performed EDA to understand the data, identify patterns, and detect outliers.
2. **Feature Engineering**: Converted categorical variables into numerical ones and transformed data as necessary.
3. **Correlation Analysis**: Removed highly correlated features to reduce redundancy and focus on the most relevant data.
4. **Modeling**: Built a deep learning model using Keras and TensorFlow to predict loan defaults.

### Tasks and Techniques:

- **Feature Transformation**: Categorical data such as `purpose` is transformed into numerical format using encoding techniques.
- **Exploratory Data Analysis**: Investigated trends, distributions, and relationships between features and loan default status.
- **Additional Feature Engineering**: Applied techniques like feature scaling and dimensionality reduction to enhance model performance.
- **Modeling**: After preprocessing and feature selection, we built and trained a deep learning model using Keras with TensorFlow backend.

### Model Details:

- **Model Type**: Deep learning using a feed-forward neural network.
- **Activation Function**: Relu for hidden layers, sigmoid for the output layer to predict binary defaults (0: no default, 1: default).
- **Loss Function**: Binary cross-entropy.
- **Optimizer**: Adam optimizer for efficient training.

---

This **`README.md`** contains the essential project details, technology stack, and insights about the loan default prediction task. Let me know if any further modifications are needed!

