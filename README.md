# Loan Eligibility Status Prediction using SVM

## Overview
This project implements a *Support Vector Machine (SVM)* model to predict whether an applicant is *eligible for a loan* based on financial and demographic features.

## Dataset
The dataset contains key attributes such as:
- *Applicant Income & Co-Applicant Income*
- *Loan Amount & Loan Term*
- *Credit History*
- *Employment & Marital Status*
- *Property Area*
- *Dependents & Education Level*

## Model & Approach
- *Exploratory Data Analysis (EDA)*:
  - Used *Seaborn (sns)* for data visualization to identify trends and correlations.
  - Checked for missing values and handled them appropriately.
- *Feature Engineering*:
  - Encoded categorical variables and normalized numerical features.
- *Algorithm*:  
  - Used *Support Vector Machine (SVM)* for classification.
- *Evaluation*:  
  - Accuracy, Precision, Recall, F1-score, and Confusion Matrix.

## Installation & Requirements
To run this project, install the necessary dependencies:

```bash
pip install numpy pandas scikit-learn seaborn
