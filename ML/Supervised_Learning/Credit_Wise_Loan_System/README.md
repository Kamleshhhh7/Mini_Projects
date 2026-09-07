# Credit Wise Loan System

## About the Project

This is a supervised learning project I created while learning how machine learning can be applied to loan approval classification problems.

The goal of this project is to predict whether a loan application is likely to be approved based on information about the applicant, such as income, credit score, financial details, and other application-related features.

I worked through the complete machine learning workflow, including data cleaning, exploratory data analysis, categorical encoding, feature scaling, model training, evaluation, and feature engineering.

## What I Practiced

- Loading and exploring data using Pandas
- Checking and handling missing values
- Exploratory Data Analysis (EDA)
- Understanding class distribution
- Analyzing numerical and categorical features
- Removing unnecessary features
- Encoding categorical variables
- Correlation analysis
- Train-test splitting
- Feature scaling
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Model evaluation
- Feature engineering
- Comparing model performance

## Project Workflow

Loan Approval Dataset
        ↓
Load Dataset
        ↓
Data Exploration
        ↓
Handle Missing Values
        ↓
Exploratory Data Analysis
        ↓
Remove Unnecessary Features
        ↓
Encode Categorical Variables
        ↓
Correlation Analysis
        ↓
Train-Test Split
        ↓
Feature Scaling
        ↓
Train Classification Models
        ↓
Evaluate Models
        ↓
Feature Engineering
        ↓
Train Models Again
        ↓
Compare Results

## Models Used

### Logistic Regression

Logistic Regression was used as one of the classification models to predict whether a loan application would be approved.

### K-Nearest Neighbors (KNN)

KNN was used to classify loan applications based on the similarity between their feature values and nearby data points.

### Gaussian Naive Bayes

Gaussian Naive Bayes was used as another classification approach, and its performance was compared with Logistic Regression and KNN.

## Feature Engineering

As part of the project, I experimented with creating additional features from existing numerical variables.

The following features were created:

- `DTI_Ratio_sq`
- `Credit_Score_sq`

The models were then trained and evaluated again to understand whether these engineered features affected their performance.

## Exploratory Data Analysis

The project includes several EDA steps to better understand the dataset, including:

- Loan approval class distribution
- Education-level distribution
- Applicant income distribution
- Co-applicant income distribution
- Outlier analysis
- Credit score analysis
- Relationship between features and loan approval
- Correlation analysis

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics were used to compare the classification performance of the different models.

## Dataset

The project uses the loan approval dataset loaded in the notebook.

The dataset contains information about loan applicants and includes the `Loan_Approved` variable as the target.

Some of the features include:

- Applicant Income
- Coapplicant Income
- Credit Score
- DTI Ratio
- Savings
- Education Level
- Employment Status
- Marital Status
- Loan Purpose
- Property Area
- Gender
- Employer Category

## Files

- `credit_wise_loan_system.ipynb` — Main Jupyter Notebook
- `README.md` — Project documentation

## What I Learned

This project helped me understand how a machine learning classification problem can be approached from the beginning.

I practiced handling missing data, exploring relationships between variables, encoding categorical features, scaling numerical data, training multiple classification models, and evaluating their performance.

The feature engineering part also helped me understand how transforming existing features can be used as another step in the machine learning workflow.

## Future Improvements

As I learn more about machine learning, I would like to:

- Experiment with additional classification algorithms
- Perform more systematic hyperparameter tuning
- Explore additional feature engineering techniques
- Compare models using additional evaluation metrics
- Improve the overall model performance

---

**Project Type:** Mini Project  
**Category:** Supervised Learning — Classification  
**Models:** Logistic Regression, KNN, Gaussian Naive Bayes  
**Status:** Learning Project