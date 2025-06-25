# 1. Project Overview
This project develops and evaluates machine learning models to predict loan eligibility for applicants based on demographic and financial features. The goal is to help financial institutions make data-driven decisions in loan approvals, balancing risk control and customer acquisition.

---
# 2.Dataset
- **Source**: Public loan eligibility dataset (or specify source if known)
- **Size**: ~600 records
- **Features**:
Gender:	Applicant gender<br>
Married:	Marital status<br>
Dependents:	Number of dependents<br>
Education:	Education level<br>
Self_Employed:	Self-employment status<br>
ApplicantIncome:	Applicant's income<br>
CoapplicantIncome:	Coapplicant's income<br>
LoanAmount:	Loan amount<br>
Loan_Amount_Term:	Loan term (months)<br>
Credit_History:	Credit history flag<br>
Property_Area:	Urban/Semiurban/Rural<br>
Loan_Status	Target: Approved (1) / Not Approved (0)<br>

---
# 3.Technologies & Methods
- **Python**：pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn
- **Machine Learning models**:Logistic Regression, Random Forest, SVM, KNN 
- **Methods**:
Data cleaning, preprocessing, standardization，<br>
Pipeline construction to integrate SMOTE, scaling, and modeling, <br>
Hyperparameter tuning via GridSearchCV,<br>
Model evaluation with confusion matrix, classification report，<br>
Feature importance

---
# 4.Conclusion
The Random Forest model achieved the best balance between accuracy (approximately 80%) and interpretability.
The most influential features in predicting loan approval were Credit_History and LoanAmount, indicating that applicants with positive credit history and manageable loan amounts were more likely to receive approval.

