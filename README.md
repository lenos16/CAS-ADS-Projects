# CAS-ADS-Projects
Projects for CAS Applied Data Science Course
## [M2 Project: Determine Car Price based on car features](https://github.com/lenos16/CAS-ADS-Projects/tree/main/M2%20Project)
* We perform an EDA on the Data Set and determine that we have multiple correlated features in the data set as well as a few errors which we need to cleanup
* For the model we chose an OLS regression model as this allows us to see the feature importance and impact of each one of the features
* Using the RFE function from sklear we do an initial feature selection 
* By calculating the VIF score for the remaining features we eliminate those features with high multicollinearity 
