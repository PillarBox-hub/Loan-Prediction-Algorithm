# Loan-Prediction-Algorithm
Use of Supervised Machine Learning techniques to predict who qualifies for loans or not. 


This loan prediction Algorithm employs the use of supervised Machine Learning ensembles i.e. LogisticRegression, KNeighborsClassifier, Support Vector Machine(SVC), DecisionTreeClassifier, RandomForestClassifier to help predict whether loans will be approved or not using the loan_data_set. 


These train models were passed though GridsearchCV to help fine tune the hyperparameters for a better model performance. precision_score, recall_score, f1_score, log_loss, accuracy_score were used to evaluate the performance of each model. 

<img width="314" alt="image" src="https://user-images.githubusercontent.com/110098621/216682526-603298c7-a879-4b21-8160-4a2c39975e1f.png">







# Data Description

| Columns       | Description |
| ------------- | ------------- |
| Loan_ID       | Unique ID of loan Application |
| Gender        | Gender of Loan Applicant |
| Married       | Marital Status of the Applicant |
| Dependents    | Number of Children of Applicant |
| Education     | Education Status of the Applicant|
| Self_Employed | Employment status of the Applican|
|ApplicantIncome| Income earned by the Applicant   |
|CoapplicantIncome| Income of Coapplicant          |
|LoanAmount|   Amount of loan Applied for          |
|Loan_Amount_Term| Loan Repayment Duration         |
|Credit_History|   Applicants Credit History       |
|Property_Area|    Area of Applicants Property     |
|Loan_Status|   Status of loan applicant           | 
