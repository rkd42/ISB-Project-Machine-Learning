
# # Fraud Detection Model
* In order to identify fraud Banking correspondets dealing with customers

# # ISB-Project-Machine-Learning

* ML tool for "Financial Inclusion for The Poor: Do Technological Failures Deter Financial Inclusion"
* Binary classification task with the goal of predicting whether customer will remain in the system(denoted by 1) or drop out of the system(denoted by 0).
* Xgboost_Hyperparameter_Tuning_ISB - Code for tuning the parameters for Xgboost to be used in Ensembling model.
* Catboost_Hyperparameter_Tuning_ISB - Code for tuning the parameters for Catboost to be used in Ensembling model.
* Final_Ensembling_model_ISB - Run the code with the tuned Xgboost and catboose parameters.
* RandomForrest- gives decent results in this case and takes less time as compared to Ensembling model.


## Getting Started
This project requires Python and the following Python libraries installed:
* NumPy
*	Pandas
*	matplotlib
*	scikit-learn
*	Xgboost
*	Catboost
*	Bayes_opt

* You will also need to have software installed to run and execute a Jupyter Notebook.If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.
Code

### Prerequisites
* certifi==2019.3.9
* cycler==0.10.0
* joblib==0.13.2
* kiwisolver==1.1.0
* llvmlite==0.29.0
* matplotlib==3.1.0
* numba==0.44.0
* numpy==1.16.4
* pandas==0.24.2
* pyod==0.7.2
* pyparsing==2.4.0
* python-dateutil==2.8.0
* pytz==2019.1
* scikit-learn==0.21.2
* scipy==1.3.0
* six==1.12.0
* sklearn==0.0


### Data set description

Variables:
* Trans_id: Transaction ID 
* trn_count: Transaction count 
* trn_ct1,trn_ct2,trn_ct3,trn_ct4: Quartile of Transaction count
* deposit_amount: Deposit Amount
* dep_amt: Quartile of Deposit amount
* withdrawal_amount: Withdrawal Amount 
* with_amt : Quartile of withdrawal amount
* hour_day: Hour of the day of Transaction
* bco_retailoutletdetails: 
* age_customer: Number of days since first transaction
* ag_cust: Quartile of age_customer
* years_experience: Years of experience of BCs
* yrs_exp1: Quartile of years_experience


## Acknowledgments

* Indian School of Business - Shashank Sinha, Aditya Murlidharan ,Prasanna Tantri
