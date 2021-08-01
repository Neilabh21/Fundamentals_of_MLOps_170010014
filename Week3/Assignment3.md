# Week 3
## Assignment 3
---
### Part I

[Link to ```MLOps_Assignment``` repo](https://github.com/Neilabh21/MLOps_Assignment/tree/pycaret_expt1)

List of pre-processing and feature engineering techniques -
- numeric_imputation = "median"
- categorical_imputation = "mode"
- normalize = True,
- fix_imbalance = True
- test_data = data_unseen

Fine tuning -

Model | F1 before tuning | F1 after tuning
--- | --- | ---
Extra Trees Clasifier | 0.7894 | 0.7560
Light GBM Classifier | 0.4847 | 0.5492
Ridge Classifier | 0.1855 | 0.7949
LDA Classifier | 0.1855 | 0.7878
SVM Classifier | 0.1007 | 0.2043
Logistic Classifier | 0.1107 | 0.1152

Blended Model -

Model	 | Accuracy	| AUC	| Recall	| Prec.	 | F1	 | Kappa	| MCC
--- | --- | --- | --- | --- | --- | --- | --- 
Voting Classifier Blended Model |	0.9994	| 0.8803	| 0.7609	| 0.875	| 0.814	| 0.8136	| 0.8156
