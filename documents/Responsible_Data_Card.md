# Responsible Data Card

## 1. Dataset Purpose

The dataset is used to build a machine learning model for predicting
customer churn.

## 2. Data Provenance

The dataset was provided as part of the RabTech Academy internship task
and is used for educational machine learning experimentation.

## 3. Intended Use

The dataset is intended for learning, experimentation, and developing a
baseline customer churn prediction model.

## 4. Consent and Privacy

Customer information should be handled responsibly. Personal or sensitive
information should not be publicly exposed or shared unnecessarily.

## 5. Sensitive Attributes

Sensitive attributes should not be used for prediction unless there is a
clear and justified purpose.

## 6. Missing Data

The dataset was checked for missing values during data analysis. Missing
values, if present in future datasets, should be handled appropriately
before model training.

## 7. Data Leakage Risk

Features that contain information available only after a customer has
already churned should not be used for prediction.

## 8. Class Imbalance

The distribution of churned and non-churned customers should be checked.
If the classes are imbalanced, suitable evaluation metrics should be used.

## 9. Model Limitations

The dataset is small and may not represent all real-world customers.
Therefore, the model results should not be treated as universally
applicable.

## 10. Human Oversight

Model predictions should support human decision-making. Important customer
actions should not be based only on automated predictions.

## 11. Monitoring

Model performance should be monitored regularly for changes in data
distribution and prediction performance.

## 12. Rollback

If the model shows unexpected behaviour or significant performance
degradation, the model should be reviewed and the previous validated
version should be restored.