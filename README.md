# ISB-Project-Machine-Learning
ML tool for "Financial Inclusion for The Poor: Do Technological Failures Deter Financial Inclusion"
Machine Learning
Project: Predicting whether customer remains in the system or not
Install
This project requires Python and the following Python libraries installed:
•	NumPy
•	Pandas
•	matplotlib
•	scikit-learn
•	Xgboost
•	Catboost
•	Bayes_opt

You will also need to have software installed to run and execute a Jupyter Notebook
If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.
Code

Code with hyperparametrs optimized  is provided in the Final_Model notebook file. You will also be required to use the data1_failure_ef.csv dataset file to run the model. If you are interested to know how the model has been created in the notebook, please feel free to explore this Python file.

Data set description

Variables:
Trans_id: Transaction ID 
trn_count: Transaction count 
trn_ct1,trn_ct2,trn_ct3,trn_ct4: Quartile of Transaction count
deposit_amount: Deposit Amount
dep_amt: Quartile of Deposit amount
withdrawal_amount: Withdrawal Amount 
with_amt : Quartile of withdrawal amount
hour_day: Hour of the day of Transaction
bco_retailoutletdetails: 
age_customer: Number of days since first transaction
ag_cust: Quartile of age_customer
years_experience: Years of experience of BCs
yrs_exp1: Quartile of years_experience


Requirements

certifi==2019.3.9
cycler==0.10.0
joblib==0.13.2
kiwisolver==1.1.0
llvmlite==0.29.0
matplotlib==3.1.0
numba==0.44.0
numpy==1.16.4
pandas==0.24.2
pyod==0.7.2
pyparsing==2.4.0
python-dateutil==2.8.0
pytz==2019.1
scikit-learn==0.21.2
scipy==1.3.0
six==1.12.0
sklearn==0.0

month: months of Transactions
dow: Day of the week of transactions
dummy_failure: Binary variable with 1 denoting transaction failure
dummy_balanceinquiry: Binary variable with 1 denoting balance inquiry 
dummy_ministatement: Binary variable with 1 denoting ministatement activity
dummy_working_hours: Binary variable with 1 denoting transaction has been done in non-working hours
dummy_biometric: Binary variable with 1 denoting biometric failure
dummy_technical_fail: Binary variable with 1 denoting technical failure
dummy_non_technical_fail: Binary variable with 1 denoting non technical failure
town_village: Names of various towns





Target Variable “dummy_activity_3” is the response variable and it takes value 1 when customer comes back in the system in next 3 months and 0 otherwise.

Models 
Catboost and XGBoost with parameter tuning using Bayesian optimization
Random Forrest 	
