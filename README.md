# \# Supervised Machine Learning: Cross-Validation \& Hyperparameter Tuning

# 

# \## Project Overview

# This project focuses on evaluating and optimizing supervised machine learning models for residential loan application prediction. It utilizes a leak-free preprocessing pipeline alongside 5-fold cross-validation and `GridSearchCV` to tune hyperparameters and mitigate overfitting.

# 

# \## Dataset

# \- \*\*Name:\*\* Kaggle Loan Prediction Problem Dataset (`loan\\\_data.csv`)

# \- \*\*Details:\*\* 614 rows, 13 columns. The target variable is `Loan\\\_Status` (Approved/Rejected).

# 

# \## Models Evaluated

# \- K-Nearest Neighbors (KNN)

# \- Decision Tree Classifier

# \- Random Forest Classifier

# \- Gradient Boosting Classifier

# 

# \## Best Tuned Model

# \- \*\*Tuned Random Forest:\*\* `max\\\_depth=3`, `n\\\_estimators=100`

# \- \*\*5-Fold CV Accuracy:\*\* 79.84%

# \- \*\*Holdout Test Accuracy:\*\* 85.37% (F1-Score: 0.9032)

# \- Overfitting was successfully reduced to a 0.41% gap between train and validation scores.

