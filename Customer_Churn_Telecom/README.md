## Telecom Churn Prediction
### Overview
This project aims to predict customer churn for a telecommunications service provider and devise a retention strategy that involves offering promotional codes and special incentives to customers who are at risk of terminating their contracts.
### Task
Classification

### Dataset
The project utilizes data from different sources, including:

- `contract_new.csv`: Contract information, 7043 entries, 8 variables (customerID, BeginDate, EndDate, Type, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges)
- `personal_new.csv`: Customer personal data, 7043 entries, 5 variables
- `internet_new.csv`: Internet service information, 5516 entries, 8 variables
- `phone_new.csv`: Phone service information, 6361 entries, 2 variables

In all these files, the `customerID` column contains unique customer identifiers.

### Libraries
Pandas  
Matplotlib  
Scikit-learn  
Optuna  
CatBoost  
LGBM  


### Conclusion
The LightGBM model excelled, achieving:

ROC-AUC: 0.9319
Accuracy: 0.9296
Сalibration and threshold tuning were made, it's recommended for deployment, enabling effective customer retention and cost reduction.



