# ML Problem Framing

## 1. Decision

The company wants to identify customers who may churn so that appropriate
customer retention actions can be considered.

## 2. Prediction Target

The model predicts whether a customer will churn or not.

Target variable:

churned

- 0 = Not churned
- 1 = Churned

## 3. Unit of Observation

One customer record represents one unit of observation.

## 4. Action Window

The prediction is intended to identify customers who may be at risk of
churning during the relevant future period so that the business can review
possible retention actions.

## 5. Non-ML Baseline

A simple baseline is to predict the majority class for every customer.
This provides a reference point for evaluating the machine learning model.

## 6. Model Used

A Logistic Regression model was used as the baseline machine learning model.

## 7. Evaluation Metrics

The baseline model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## 8. False Positive Cost

A false positive occurs when the model predicts that a customer will churn,
but the customer does not actually churn. This may lead to unnecessary
retention efforts.

## 9. False Negative Cost

A false negative occurs when the model predicts that a customer will not
churn, but the customer actually churns. This may result in a missed
opportunity to review that customer's situation.

## 10. Human Review

Model predictions should be reviewed by a human before important customer
actions are taken.