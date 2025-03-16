# Loan_prediction

## Overview

This project focuses on analyzing loan applicants to predict loan approvals, assess risk factors, and perform customer segmentation. The dataset includes various financial and personal attributes of applicants. The goal is to build predictive models for loan default prediction and customer segmentation for targeted marketing and risk management.

## Objectives

1. **Customer Segmentation**: Segment applicants based on their financial and personal profiles to enable targeted marketing and risk assessment.
2. **Risk Assessment**: Analyze key factors contributing to loan default risk to help lenders make informed decisions.
3. **Loan Default Prediction**: Build machine learning models to predict whether an applicant is likely to default on a loan.

## Dataset

The dataset consists of 252,000 records with the following features:

- **Id**: Unique identifier for each applicant
- **Income**: Applicant's annual income
- **Age**: Applicant's age in years
- **Experience**: Applicant's years of work experience
- **Married/Single**: Applicant's marital status
- **House Ownership**: Type of house ownership (Rented, Owned, etc.)
- **Car Ownership**: Whether the applicant owns a car (Yes/No)
- **Profession**: Applicant's profession
- **CITY**: City where the applicant resides
- **STATE**: State where the applicant resides
- **Current Job Years**: Number of years in the current job
- **Current House Years**: Number of years living in the current house
- **Risk Flag**: Target variable (1 indicates high risk, 0 indicates low risk)

## Installation

To run this project, ensure you have Python installed along with the required dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

Run the Jupyter Notebook to execute the analysis and prediction steps. Use the following command to start Jupyter Notebook:

```bash
jupyter notebook
```

Open the `Loan_prediction.ipynb` file and run the cells sequentially.

## Methodology

The project follows these steps:

1. Data Preprocessing:
   - Handling missing values (if any)
   - Encoding categorical variables (e.g., converting "Married/Single" to binary values)
   - Feature scaling where necessary

2. Exploratory Data Analysis (EDA):
   - Understanding the distribution of income, age, experience, etc.
   - Identifying correlations between features and loan default risk
   - Visualizing data using plots and charts

3. Customer Segmentation:
   - Clustering applicants based on their financial and personal profiles
   - Using techniques like K-Means or Hierarchical Clustering to segment customers
   - Identifying high-risk vs. low-risk applicants for targeted marketing and risk mitigation

4. Risk Assessment & Loan Default Prediction:
   - Splitting the dataset into training and testing sets
   - Training models such as Logistic Regression, Decision Trees, Random Forest, and others
   - Evaluating models using accuracy, precision, recall, and F1-score
   - Identifying key factors that contribute to loan defaults

5. Predictions & Conclusion:
   - Using the best-performing model to predict loan default risk
   - Analyzing the impact of key features on predictions
   - Suggesting risk mitigation strategies based on the findings

## Results

The model performance is evaluated based on accuracy and other metrics. The insights help in identifying key factors influencing loan defaults and enable better decision-making for lenders.



