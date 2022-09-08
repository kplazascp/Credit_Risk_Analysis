# Credit_Risk_Analysis

## Overview of the analysis
Personal loans are very important for the individuals and for banks as they have high demand and are a very profitable product.
One of the important keys to this analysis in personal loans, is the high risks that involves an individual not paying back the loan, this is why in this analysis, we are evaluating different factors to determine if an individual will or will not pay the credit with Supervised Machine Learning.

## Results
Balanced accuracy scores and precision scores of all six machine learning models: 

### Naive Random Oversampling
- Balanced Accuracy Score: 64.38%
- Avg/Total Precision:0.99
- Avg/Total Recall:0.60

![Native](https://github.com/kplazascp/Credit_Risk_Analysis/blob/main/Resources/Oversampling.PNG)

### SMOTE Oversampling
- Balanced Accuracy Score: 66.28%
- Avg/Total Precision:0.99
- Avg/Total Recall:0.69

![SMOTE](https://github.com/kplazascp/Credit_Risk_Analysis/blob/main/Resources/SMOTE.PNG)

### Undersampling
- Balanced Accuracy Score: 55.47%
- Avg/Total Precision:0.99
- Avg/Total Recall:0.40

![Undersampling](https://github.com/kplazascp/Credit_Risk_Analysis/blob/main/Resources/Undersampling.PNG)

### Combination (Over and Under) Sampling
- Balanced Accuracy Score: 63.86%
- Avg/Total Precision:0.99
- Avg/Total Recall:0.58

![Combination](https://github.com/kplazascp/Credit_Risk_Analysis/blob/main/Resources/Over%20and%20Undersampling.PNG)

### Balanced Random Forest Classifier
- Balanced Accuracy Score: 78.85%
- Avg/Total Precision:0.99
- Avg/Total Recall:0.87

![BRF](https://github.com/kplazascp/Credit_Risk_Analysis/blob/main/Resources/BRF.PNG)

### Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score: 93.16%
- Avg/Total Precision:0.99
- Avg/Total Recall:0.94

![EEA](https://github.com/kplazascp/Credit_Risk_Analysis/blob/main/Resources/EEA.PNG)

## Summary
| Model  | Balanced Accuracy Score | Avg/Total Precision  | Avg/Total Recall  |
| ------------- | ------------- | ------------- | ------------- |  
| Native Random Oversampling  | 64.38%  | 0.99  | 0.60  |
| SMOTE Oversampling  | 66.28%  | 0.99  | 0.69  |
|  Undersampling  | 55.47%  | 0.99  | 0.40  |
| Combination Over and Undersamppling  | 63.86%  | 0.99  | 0.58  |
|  Balanced Random Forest Classifier  | 78.85%  | 0.99  | 0.87  |
|  Easy Ensemble AdaBoost Classifier  | 93.16% | 0.99  | 0.94  |

Reccomendation on the model:
The Easy Ensemble AdaBoost Classifier will be my recommendation because it has the highest Balance Accuracy Score (Over 90%) which means that it has a good match to make predictions, also the Avg/Total Recall is the highest with 0.94.
Something to evaluate would be not only to use one model, so that we can have two models that if they get the same result towards the same individual it is more trustworthy.
