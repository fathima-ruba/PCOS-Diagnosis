# Polycystic Ovary Syndrome Diagnosis

This project aimed to develop an AI-driven solution to aid in the diagnosis of Polycystic Ovary Syndrome (PCOS) by analyzing medical data and hormonal profiles. A machine learning model, specifically a Random Forest classifier, was trained and evaluated to achieve this aim. 

## Introduction
Polycystic Ovary Syndrome (PCOS) is a hormonal disorder common among women of reproductive age. Early and accurate diagnosis is crucial for effective treatment and management. This project utilized machine learning to analyze a dataset of medical records and hormonal profiles to predict the likelihood of PCOS.

## Data Preprocessing
The dataset contained 541 samples and 45 features, including age, weight, height, BMI, blood group, and various hormonal levels. The following preprocessing steps were carried out:
Handled missing values by imputing median values
Converted non-numeric entries to numeric values
Removed irrelevant columns

## Feature Engineering
To enhance the model's performance, the following features were engineered:
BMI Categories: Underweight, Normal, Overweight, Obese
Age Groups: Teenager, Young Adult, Adult, Senior
Hormonal Ratios: FSH/LH Ratio
Blood Pressure Categories: Normal, Elevated, Hypertension Stage 1 and 2

## Model Selection and Evaluation
Various machine learning models were evaluated using 5-fold cross-validation:
Logistic Regression: 87.03%
Decision Tree: 80.55%
Random Forest: 90.04%
Support Vector Machines: 66.43%
k-Nearest Neighbors: 66.43%
Gradient Boosting: 89.81%
The Random Forest model achieved the highest average accuracy and was selected for further evaluation. 

## Testing and Inference
The trained Random Forest model was tested with synthetic and real samples from the original dataset. The model correctly identified whether the individual had PCOS or not, confirming its predictive capabilities.

## Conclusion
The AI-driven solution developed in this project demonstrated significant potential for aiding in the diagnosis of PCOS. The Random Forest model achieved good performance and can be further refined for clinical applications.
