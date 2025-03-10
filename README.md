# Customer Churn Prediction Project

## Research Question

Can machine learning accurately predict customer churn in a telecom company using customer demographic, service usage and billing data, and what key factors contribute most to customer retention?

## Project Overview

This project aims to build a machine learning model that predicts customer churn for a telecom company. The model will analyze factors contributing to churn and provide insights for developing effective customer retention strategies.

## Dataset

Source: Kaggle - Telecom Customer Churn Dataset

## Data Description: The dataset includes customer demographics, account information and service usage data.

## Tools and Technologies

* Python

* Matplotlib & Seaborn: Data visualization

* Scikit-learn: Machine learning modeling and evaluation

* SMOTE: Handling class imbalance

* Gradient Boosting Classifier: Model building

## Methodology

### Data Collection: Downloaded the dataset using KaggleHub

### Data Preprocessing:

* Handled missing values and data types

* Encoded categorical variables

* Scaled numerical features

### Model Building:

* Utilized a Gradient Boosting Classifier with SMOTE to handle class imbalance

* Applied GridSearchCV for hyperparameter tuning

### Evaluation Metrics:

* Accuracy: 85%

* ROC AUC Score: 0.85

* Precision, Recall, F1 Score: Analyzed through a classification report

### Visualization:

* ROC Curve: Showed the model's classification performance

* Feature Importance: Highlighted the top features contributing to churn

### Key Findings

* The model achieved a strong Accuracy of 85% and a high ROC AUC Score of 0.85.

* Balanced Performance: Precision and recall for both churn and non-churn classes were equally strong (0.85).

### Key Features Influencing Churn:

* Contract Type: The most significant predictor of churn.

* Monthly Charges: High charges are associated with higher churn.

* Total Charges: Important, but less than monthly charges and contract type.

## Recommendations

## Business Strategies:

* Develop incentives for long-term contracts to reduce churn.

* Create personalized offers for customers with high monthly charges.

* Implement targeted campaigns based on contract type and payment behaviors.

## Model Enhancement:

* Experiment with advanced models such as XGBoost or LightGBM.

* Apply more complex feature engineering techniques.

## Future Improvements:

* Additional hyperparameter tuning to further enhance model performance.

* Integrate the model into a Streamlit or Flask dashboard for better business usage.


### Conclusion

This project demonstrates a practical approach to customer churn prediction using machine learning. The enhanced model performance provides actionable insights for reducing churn and improving customer retention strategies.

