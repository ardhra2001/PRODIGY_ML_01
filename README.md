# PRODIGY_ML_01
### Prodigy Infotech Internship Task 1

### House Price Prediction using Multiple Linear Regression
This project demonstrates how to predict the house prices [SalePrice] using **Multiple Linear Regression Model** trained on the Kaggle data House Prices: Advanced Regression Techniques dataset . The main focus of the project is to predict the prices based on three features such as square footage , number of bedrooms and bathrooms.

### About the Data 
Dataset : https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data
The data set consist of 
1.train.csv - training set 
2.test.csv - testing set
3.data_description.txt - full description of 81 features 
4.sample_submission.csv - a submission from a linear regression on year and month of sale, lot square footage, and number of bedrooms

### Steps
1.Understanding the Problem 
2.Loading the data set
3.Feature Engineering
4.Feature Selection 
5.Data Cleaning 
6.Exploratory Data Analysis
7.Train-Test Split 
8.Training the Model 
9.Evaluating the Model - Metrics used:-Mean Squared Error (MSE) -Root Mean Squared Error (RMSE) -R² Score 
10.Data Visualization - Pair plots for correlation -Heatmap of numeric feature correlation with SalePrice -Bar plot of feature coefficients


### Features used 
Grouped into three 
1.Square Footage 
- 'GrLivArea' 
- 'TotalBsmtSF' 
- '1stFlrSF' 
- '2ndFlrSF'
- 'LotArea'
2.Bedrooms
- 'BedroomAbvGr'
- 'TotRmsAbvGrd'
3.Bathrooms
- 'FullBath'
- 'HalfBath'
- 'BsmtFullBath'
- 'BsmtHalfBath'
Target Variable - SalePrice

### Notes 
Data cleaning includes dropping features with high missing values , dropping duplicate values  and handling missing numeric entries.
No train-test split was required as Kaggle already provides separate train and test datasets.Eventhough added the code to understand .
Pipeline is used for scaling and model training.
All the tools and libraries are provided in requirements.txt

### How to run 
-Clone the repository 
-Install the requirements.txt
-Run the jupyter notebook

