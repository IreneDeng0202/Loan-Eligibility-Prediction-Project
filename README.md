# 1. Project Overview
This project develops and evaluates machine learning models to predict loan eligibility for applicants based on demographic and financial features. The goal is to help financial institutions make data-driven decisions in loan approvals, balancing risk control and customer acquisition.

---
# 2.Dataset
- **Source**: Public loan eligibility dataset (or specify source if known)
- **Size**: ~600 records
- **Features**:
- Gender:	Applicant gender
- Married:	Marital status
- Dependents:	Number of dependents
- Education:	Education level
- Self_Employed:	Self-employment status
- ApplicantIncome:	Applicant's income
- CoapplicantIncome:	Coapplicant's income
- LoanAmount:	Loan amount
- Loan_Amount_Term:	Loan term (months)
- Credit_History:	Credit history flag
- Property_Area:	Urban/Semiurban/Rural
- Loan_Status	Target: Approved (1) / Not Approved (0)

---
# 3.Technologies & Methods
- **Python**：pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn
- **Machine Learning models**:Logistic Regression, Random Forest, SVM, KNN 
- **Methods**:
- Data cleaning, preprocessing, standardization;
- Pipeline construction to integrate SMOTE, scaling, and modeling, 
- Hyperparameter tuning via GridSearchCV,
- Model evaluation with confusion matrix, classification report
- Feature importance

---
# 4.Conclusion
The Random Forest model achieved the best balance between accuracy (approximately 80%) and interpretability.
The most influential features in predicting loan approval were Credit_History and LoanAmount, indicating that applicants with positive credit history and manageable loan amounts were more likely to receive approval.

