# Credit-Card-Consumption 🏦 
A leading bank aims to estimate credit card spending to determine appropriate credit limits for its customers. In this project, I applied machine learning techniques to address this challenge.


#### OBJECTIVE
Predict credit card spending for a particular customers(5000 customers) for the next three months (July, August and September) to determine an appropriate credit limit.


#### DATA AVAILABILITY
- The client provided the data related to:
  
    - Customer demographics
  
    - Customer behaviour (information on liabilities, assets and history of transactions with the bank for each customer)
  
    - Credit consumption for a particular set of customers(15000 customers) in the previous 3 months (April, May & June)


#### TOOL USED 
- EDA & predictive modeling: Python (numpy, pandas,sklearn), Excel 
- For Documentation : Microsoft Word


#### TECHNIQUES USED
-	Modeling Techniques: Linear Regression, Decision Tree Regressor, Random Forest Regressor, Xgboost, KNN, SVM


#### STEPS PERFORMED
-	Acquired data in CSV format
-	Analyzed variables and referenced the data dictionary
-	Identified the problem statement
-	Merged three dataset into a single unified dataset
- Dropped unique variable like ID
- Conducted data preparation, including handling missing values for numerical and categorical variables and removing duplicates
- Converted categorical values to numerical format
- Standardized the data
- Split the data into train and test sets
-	Build the model using various techniques and validated the model by calculating RMSPE(Root Mean Square Percentage Error) between train and test sets
-	Finalized the best-performing model and documented the findings



#### TUNING PARAMETERS
- Tuned decision tree/random forest using parameters like n_estimators, max depth, min sample split, max features etc using Grid Search CV and Randomized Search CV
- Used different kernel in SVM


#### OUTPUT
The model is best performing with Linear regression with RMSPE - 28%


#### IMPACT 🚀  
Understanding the consumption pattern for credit cards at an individual consumer level is important for customer relationship management. This understanding allows banks to customize for consumers and make strategic marketing plans. 

