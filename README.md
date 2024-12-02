# Loan_Default_Preducation
## Context
A major proportion of retail bank profit comes from interests in the form of loans. These loans are borrowed by regular income/high-earning customers. Banks are most fearful of defaulters, as bad loans usually eat up a major chunk of their profits. Therefore, it is important for banks to be judicious while approving loans for their customer base.

The approval process for the loans is multifaceted. Through this process, the bank tries to check the creditworthiness of the applicant on the basis of a manual study of various aspects of the application. The entire process is not only effort-intensive but also prone to wrong judgment/approval owing to human error and biases.

There have been attempts by many banks to automate this process by using heuristics. But with the advent of data science and machine learning, the focus has shifted to building machines that can learn this approval process and make it free of biases and more efficient. At the same time, one important thing to keep in mind is to make sure that the machine does not learn the biases that previously crept in because of the human approval process.

# Problem Statement
The primary goal of this project is to develop a predictive model that can assess the risk of loan default for loan applicants. The objective is to help financial institutions make informed decisions about whether to approve or reject loan applications.

# Objective
Build a classification model to predict clients who are likely to default on their loan 

# Data Dictionary
Age	= Shows the Eligibility age of a customer to provide loan
Gender = To know the Gender of the customer
Income	= Income of a customer is checked for the aproval for the loan
Employment_Status	= Weather the Customer is Employed or unemployed for the repayment of the loan
Location	= Weather the customer is in Urban or Rural
Credit_Score = it will help how much amount can a customer can take loan
Debt_to_Income_Ratio	=   This ratio is a percentage that indicates the proportion of your monthly gross income that goes towards paying off your monthly debts
Existing_Loan_Balance	= It is a outstanding balance, is the amount of money still owed on a loan, including the principal and any interest that has accrued.
Loan_Status	= indicates where your loan is in the process
Loan_Amount	= How much is the Loan Amount is issued by the bank 
Interest_Rate	= Perecentage of Loan Amount interest
Loan_Duration_Months	= How much month should a customer take to repay the loan

# Final results
To solve this project I built 3 machine learning models: logistic regression, decision tree and random forest (baseline and tuned versions). The best performance was obtained by the tuned decision tree model: 0.77 accuracy, 0.97 recall and 0.79 precision.
