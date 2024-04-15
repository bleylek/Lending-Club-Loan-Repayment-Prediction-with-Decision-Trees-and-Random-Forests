Lending Club Loan Prediction

Project Overview:
This project utilizes data from LendingClub to predict whether borrowers will pay back their loans in full. The analysis period spans from 2007 to 2010, providing insights into borrower behaviors before LendingClub went public.

Data

The dataset, loan_data.csv, includes the following key columns:

- credit.policy: Underwriting criteria of LendingClub (1 = meets criteria)
- purpose: Purpose of the loan (e.g., credit_card, debt_consolidation)
- int.rate: Interest rate of the loan
- installment: Monthly installment amount
- log.annual.inc: Logarithm of the borrower's annual income
- dti: Debt-to-income ratio
- fico: FICO credit score
- days.with.cr.line: Number of days the borrower has had a credit line
- revol.bal: Revolving balance
- revol.util: Revolving line utilization rate
- inq.last.6mths: Number of inquiries by creditors in the last 6 months
- delinq.2yrs: Number of times the borrower was 30+ days past due on a payment in the past 2 years
- pub.rec: Number of derogatory public records
- not.fully.paid: Loan not fully paid (1 = no, 0 = yes)

Technologies Used
- Python
- Pandas: For data manipulation
- NumPy: For numerical operations
- Matplotlib & Seaborn: For visualizations
- Scikit-learn: For implementing Random Forest Classifier

Model

The project implements a Decision Tree and a Random Forest model to classify and predict the likelihood of loan repayment. Model training and evaluation steps are detailed within the Jupyter Notebook.
