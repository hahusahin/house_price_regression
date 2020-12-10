# House Price Prediction Using Regression Techniques

### Goal
The goal of this analysis is to predict the sales price of houses in the city of Ames Iowa by using machine learning algorithms.

### Data Description
* The training dataset has a total of 1460 observations with 81 variables while the test dataset has one less variable - the target variable of SalePrice. 

* Total number of features are 79, of which 34 is quantitative and 43 categorical.

* Target variable is the Sale Price.

### Exploratory Data Analysis
* Target variable's distribution is examined, log transformation is applied

* Target variable's correlation with the features are examined

* Outliers are detected and removed

* Missing values are detected and filled, unnecesarry features are deleted (Both datasets are combined together to ensure consistency in pre-processing)

* Transformation applied to the highly skewed features

### Modeling
* Ridge - Lasso - Elasticnet Regression, Random Forest Regressor, Support Vector Regressor, XGBoost, Light GBM models are trained

* Cross validation score of each individual model obtained, then stacking is applied according to the scores.

* The results are submitted to Kaggle and obtained a RMSE score of **0.12595**.

### Files
* train.csv - Training set
* test.csv - Test set
* data_description.txt - Full Description of each column
* house_price_regression.ipynb - Project Notebook

### Libraries Used
* pandas, numpy
* matplotlib, seaborn
* sklearn
* scipy
* xgboost, lightgbm
* mlxtend.regressor
