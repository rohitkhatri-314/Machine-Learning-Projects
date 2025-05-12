# Diabetes Check for Females - Machine Learning Model

## Overview
This repository contains a machine learning model designed to assess diabetes risk in Indian females based on the PIMA diabetes dataset. The model uses logistic regression to predict the likelihood of diabetes based on various health parameters.

## Dataset
The data used in this project comes from the **PIMA Indian Diabetes Dataset**, which contains health information from female patients of Pima Indian heritage. Key features include:
- Number of pregnancies
- Glucose level
- Blood pressure
- Skin thickness
- Insulin level
- BMI (Body Mass Index)
- Diabetes pedigree function
- Age

## Features
- Data preprocessing to handle missing values (imputed with mean)
- Standard scaling for feature normalization
- Logistic regression model with 85.7% accuracy
- Interactive input system to get user health parameters
- Gender verification (only accepts female users)
- Clear risk assessment output with medical disclaimer

## Requirements
- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib (for potential visualization)

## How to Use
1. Run the Jupyter notebook `diabetes check for females.ipynb`
2. The program will prompt you for:
   - Gender verification (only accepts female users)
   - Number of pregnancies
   - Glucose level
   - Blood pressure
   - Skin thickness
   - Insulin level
   - BMI
   - Diabetes pedigree function
   - Age
3. The model will output either:
   - "Not vulnerable to diabetes" recommendation, or
   - Suggestion to get tested for diabetes

## Important Notes
- This model is specifically designed for **female users** over age 21
- The program includes automatic gender verification
- Results should not be considered medical diagnosis
- Always consult healthcare professionals for actual diabetes testing

## Accuracy
The model achieves **85.7% accuracy** on the test set, though real-world performance may vary.

## Future Improvements
- Expand to include male users with appropriate dataset
- Add more sophisticated models (Random Forest, SVM, etc.)
- Include feature importance visualization
- Develop web/mobile interface for easier access

## Disclaimer
This program is not a medical diagnostic tool. It serves only as an indicator for whether further professional testing might be advisable. Final diagnosis should always come from qualified medical professionals.