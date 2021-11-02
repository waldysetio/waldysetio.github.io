# Project 1: [Customer Churn Analysis](https://github.com/waldysetio/customer-churn-analysis)


### 1. **Business Problem Understanding**<br />
There has been a significant customer churn in an energy company that provides corporates with gas and electricity utility particularly in its SME (Small and Medium Entreprise) segment due to new power liberalization of the energy market. The company wants to know whether it's possible to predict customers likely to churn using predictive model and what factors that drive the churn. <br />


### 2. **Getting the Data**<br />
The data used in this project is from Boston Consulting Group (BCG Gamma). There are three data sets that are provided which consist of:
- Historical customer data: Customer data such as usage, sign up date, forecasted usage, etc.
- Historical pricing data: variable and fixed pricing data, etc.
- Churn indicator: whether each customer has churned or not. <br />


### 3. **Exploratory Data Analysis and Data Cleaning**<br />
- Loading and Merging Data
- Descriptive Statistical Analysis
  - Data types
  - Correlation
  - Count, mean, std, min, max, etc.
- Finding Missing Data
- Data Visualization
- Data Cleaning
- Data Formatting
  - Subtituting missing data with median
  - Formatting dates
  - Replacing negative data with median <br />


### 4. **Feature Engineering**<br />
New features have been created using the existing features in order to fit better in modelling. For example, in this project a feature called "tenure" was created by substracting "sign up date" from "end date" because churning rate might not be related to any specific date when customers signed up for a service but it could be related to the length of customers in using a service. 
- Creating new features using existing features
- Creating dummy variables/one-hot encoding for categorical data
- Removing the null column in dummy columns to avoid multicollinearity or dummy variable trap
- Doing log transformation to address right skewed data
- Plotting new features correlation
- Removing outliers



# Project 2: [Credit Risk Prediction](https://github.com/waldysetio/credit-risk)

