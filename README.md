
# Project Title

Loan Repayment Prediction



# Hi, I'm Deepak! 👋


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/deepakvdesale)



## Acknowledgements

 I appreciate all the help I have got from people at upGrad knowledgehut.


## Steps Involved

## Overview
This project aims to predict loan repayment outcomes using historical banking data. The goal is to identify patterns that indicate whether a borrower will repay or default on a loan, which is a valuable insight for financial institutions.

## Data Preprocessing
- Missing values were handled by imputation or filling with a placeholder.
- Outliers were treated by capping based on the interquartile range (IQR) method.

## Feature Engineering
New features created include:
- `income_to_loan_ratio`: The ratio of the borrower's income to the loan amount.
- `credit_history_length`: The length of the borrower's credit history.
- `fico_score_average`: The average FICO score.

## Model Development
The XGBoost algorithm was chosen for its performance with imbalanced datasets. Class imbalance was addressed using the `scale_pos_weight` parameter.

## Model Optimization
Hyperparameter tuning was performed using RandomizedSearchCV, focusing on parameters such as `n_estimators`, `max_depth`, and `learning_rate`.

## Feature Importance Analysis
The model's feature importances were analyzed to understand the most predictive factors in loan repayment.

## Results
The final XGBoost model achieved an AUC-ROC score of 0.702, indicating a good predictive ability.

## Conclusion
Interest rate, FICO score, and home ownership status were found to be significant predictors of loan repayment.

## How to Use
1. Clone the repository.
2. Install required packages using `pip install -r requirements.txt`.
3. Run the Jupyter notebooks to see the analysis and modeling steps.

## Requirements
- Python 3.8+
- pandas
- numpy
- scikit-learn
- xgboost
- matplotlib

## Contributions
Contributions are welcome. Please open an issue to discuss proposed changes or open a pull request with your contributions.

## Contact
For any questions, contact me directly at [evergreendeepakdesale@gmail.com].
