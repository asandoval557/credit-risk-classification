# credit-risk-classification

CREDIT RISK ANALYSIS REPORT
**Provide an overview that explains the purpose of this analysis. **
The purpose of the analysis is to predict is a customer will repay or potentially default on a loan based multiple factors to determine healthly and unhealthy loans.

Below is a bulleted list of accuracy, precision, and recall scores of the model:

**precision    recall  f1-score   support**

           **0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384
**

Based on the classification report I would recommend piloting the model in different markets to measure the accuracy based on new data. While the model did perform well overall, there is a 12 point delta when comparing healthy to unhealthy loans. This is due in part to the data the model was trained on and I would like the accuracy of unhealthy loans to increase to a minimum of 95% prior to expanding beyond the pilot markets
