# PROJECT OVERVIEW
   
   ## PROBLEM STATEMENT: 
   
  Given a dataset containing various residential property features, the challenge is to develop a predictive model that accurately estimates house sale prices, aiding buyers, sellers, and real estate professionals in making informed decisions.

  ## OBJECTIVE:
  To build and evaluate a predictive model for house prices using advanced regression techniques, ensuring high accuracy and reliability in estimating property values based on key features.
  
  ## Important Feature Highlight 
  
  This project focuses more on 6 unique features which MSSUbclass, MSZoning, Utilities Type, Lot Frontage, YearBuilt and Neighborhood in relation to the target feature which is the Sales Price.
  ## Stakeholders: 
  People that are likely to benefit from this project are buyers, sellers and real estate professionals
  
# DATA COLLECTION
  ## DATA SOURCE 
  The dataset was gotten from a [Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data) competition.

  ## DATA DESCRIPTION: 
  The dataset folder contains two dataset which contains the train and test dataset. The train dataset has 81 columns and 1,460 rows including the target variable which is the sales price. The test dataset is an unlabeled data without the target variable, it has 80 columns and 1,459 rows. The aim is to predict the unlabeled data after building the model. 

# TOOLS USED
•	Data Cleaning and EDA: Pandas, NumPy, Matplotlib, Seaborn

•	Feature Engineering and Preprocessing: Scikit-learn (LabelEncoder, OneHotEncoder, StandardScaler, PCA, Pipeline, ColumnTransformer)

•	Model Training and Evaluation: Scikit-learn (Linear Regression, Decision Tree, Random Forest, Gradient Boosting, SVR, RandomizedSearchCV)

# CONCLUSION 
KEY FINDINGS
•	The neighborhood, utilities type, year the house was built influences the price of the house.

•	Random Forest outperformed other models based on lower RMSE, MAE, and higher R² score.

•	The model provides accurate price predictions, useful for stakeholders in the real estate market

