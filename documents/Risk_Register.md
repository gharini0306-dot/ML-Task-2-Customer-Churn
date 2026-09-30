# Risk Register

| Risk | Description | Mitigation |
|------|-------------|------------|
| Data Leakage | Future information may be included in the training data. | Review features before training. |
| Missing Data | Missing values can affect model performance. | Check and handle missing values appropriately. |
| Class Imbalance | Churn and non-churn classes may not be equally distributed. | Use precision, recall and F1-score along with accuracy. |
| Small Dataset | A small dataset may not represent the real customer population. | Treat the model as a baseline and avoid overgeneralizing results. |
| Bias | Model performance may differ across relevant customer groups. | Evaluate performance across appropriate groups when data permits. |
| Privacy | Customer information may be sensitive. | Avoid exposing unnecessary personal information. |
| Over-reliance | Users may depend too heavily on model predictions. | Keep human review in the decision process. |
| Model Drift | Customer behaviour may change over time. | Monitor model performance and data distribution regularly. |

## Human Review

Important customer-related decisions should not be made using the model
prediction alone. A human should review relevant cases.

## Abstention

If the model confidence is too low, the prediction can be sent for
manual review instead of triggering an automatic action.

## Monitoring

Monitor model performance, prediction distribution, and relevant data
changes regularly.

## Rollback

If the model shows unexpected behaviour or significant performance
degradation, stop using the affected version and restore the previous
validated model.