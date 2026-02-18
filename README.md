# ASA-Florida-Chapter---Data-Competition-2026

All the details for this competition can be found here : https://github.com/luminwin/ASASF/

📈 ASA South Florida 2026 Student Data Challenge
Graduate Prediction Track Submission
This repository contains my submission for the 2026 ASA South Florida Student Data Challenge. The goal of this challenge is to predict HDL cholesterol levels (LBDHDD_outcome) using demographic, dietary, and anthropometric data from the 2024 NHANES survey.

📂 Project Structure
Plaintext
├── data/               # Raw and processed datasets (train.csv, test.csv)
├── notebooks/          # Jupyter notebooks
├── src/                # Script files for data cleaning and feature engineering
├── report/             # Final 4-page PDF report
├── pred.csv            # Final predictions for the test set
└── README.md           # Project overview (this file)
🔬 Methodology
My approach focuses on leveraging the NHANES variables to build a robust predictive model. Key steps include:

Data Preprocessing: Used a more data science approach and selected the variables based on the correlation to the variables of interest.

Model Selection: * Baseline: Linear Regression.

Advanced: Exploring XGBoost and Bayesian Regression to optimize RMSE.

Validation: Utilizing 5-fold cross-validation on the training set (1,000 observations) to tune hyperparameters.


📊 Results Summary
Validation for XGBoost RMSE: 4.71
Validatoin for Bayesian Regression: 5.71

👤 Author
Giulianno Gasparato, Juhwan Park

Level: Graduate Student
