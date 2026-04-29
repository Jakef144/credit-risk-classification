# Credit Risk Classification Model

## Overview
This project builds a machine learning model to classify loan applications as high-risk or low-risk based on financial features. The goal is to support better lending decisions by identifying applicants with a higher likelihood of default.

## Business Problem
Financial institutions need reliable methods to assess borrower risk. Misclassifying high-risk applicants can lead to significant financial losses, while being overly strict can reduce approval rates. This project focuses on improving risk identification, with an emphasis on accurately detecting high-risk loans.

## Tools & Technologies
- Python (Pandas, NumPy)
- scikit-learn
- Logistic Regression
- Data Preprocessing & Scaling
- Model Evaluation (Confusion Matrix, Classification Report)

## Approach

### 1. Data Preparation
- Loaded and explored loan dataset  
- Cleaned and prepared features for modeling  
- Split data into training and testing sets  

### 2. Model Development
- Implemented a logistic regression model to classify loan risk  
- Trained model using structured financial features  

### 3. Evaluation
- Evaluated performance using classification metrics  
- Focused on recall for high-risk loans to minimize false negatives  

## Key Results
- Achieved ~99% overall accuracy  
- Achieved ~94% recall for high-risk loans  
- Successfully identified the majority of risky loan applications  

## Why It Matters
Accurately identifying high-risk borrowers helps reduce default rates and financial losses. This model demonstrates how data-driven approaches can support better lending decisions.

## Project Structure
/data → dataset used for modeling
/notebooks → model development and evaluation
/scripts → preprocessing and modeling code

## Future Improvements
- Test additional models (Random Forest, Gradient Boosting)  
- Perform feature engineering to improve recall  
- Address potential class imbalance more explicitly  


## Author
Jacob Farley
