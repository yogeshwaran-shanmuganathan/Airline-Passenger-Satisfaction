# Airline-Passenger-Satisfaction
## Objective
The objective or goal of this project is to guide an airlines company to determine the important factors that influences the customer or passenger satisfaction. <br/>
Customer satisfaction plays a major role in affecting the business of a company therefore analysing and improving the factors that are closely related to customer satisfaction is important for the growth and reputation of a company.
## About Data
The dataset for this project is attained from Kaggle which contains the data sourced from a survey conducted by airlines on the satisfaction level of passengers/customers based on various factors. The dataset consists of 25 columns such as Age, Gender, Travel class, Arrival and Departure delays and also features that affects customer satisfaction such as On-board service, Cleanliness, Baggage handling etc. <br/>
The dataset consists of a column or feature named ***‘satisfaction’*** which describes the overall satisfaction level of the customer. It has two values, ‘neutral or dissatisfied’ and ‘satisfied’. This ***satisfaction*** feature is considered as the label feature since it conveys the overall experience of the customer based on the ratings given for other features. The dataset consists of 103904 and 25976 records in train and test respectively.
## Data Cleaning and Visualisation
Data cleaning plays a key role in deriving the output of a machine learning model. Usually data cleaning consists of processes like determining outliers and removing or imputing outliers, removing or replacing missing values, removing duplicate values, removing values with less or no importance. <br/>
In this project, the *‘Arrival Delay in Minutes’* column has 310 missing values in it. These missing values are imputed with the mean values of the non-missing values of the same column. <br/>
Data Visualisation plays an important role in understanding the data as it gives an overview of the data before the model implementation. Exploratory Data Analysis is done for the dataset using Python.
## Feature Selection
Correlation among the features are found by generating a correlation map. The top ten features are selected using Chi-Square method. The importance of features are determined using Wrapper method and feature permutation importance technique.
## Models
Eight models are used in this project to check for maximum efficiency. They are,
- Logistic Regression
- Naive Bayes
- KNN
- Decision Tree
- Neural Network
- Random Forest
- XGBoost
- AdaBoost
## Conclusion
Random Forest and AdaBoost have performed equally well on producing high ROC_AUC score (90%). But ***Random Forest*** has took lesser amount of time compared to time taken by AdaBoost. Therefore, we can conclude that Random Forest as the best model.
