# Project: Bank Market Segmentation using Unsupervised Machine Learning

# Project overview
* In this project, I learned how to perform a customer segmentation analysis ij order 
* Accurately customer segmentation, allows marketing team to know the customers better, identify their needs and launch targeted ad marketing campaign.
* The data used was about 8950 active credit card holders during 6 months and is at a customer level with 17 behavioural variables.

# Code and resources used:
* Python Version: 3.7
* Packages: Pandas | numpy | matplotlib | sklearn | Seaborn
* Data Source: https://www.kaggle.com/arjunbhasin2013/ccdata
* Data Source: https://www.udemy.com/course/ml-and-python-in-finance-real-cases-and-practical-solutions/

# Data Collection
* The data used was about 8950 active credit card holders during 6 months and is at a customer level with 17 behavioural variables and was collected from Kaggle

# Data Cleaning
* After importing the data to a Jupiter notebook, I explored the descriptive statistics of the variables
* Checked for missing and null values
* Filled up the missing values of the variable ‘MINIMUM_PAYMENTS’ with its mean value.
* Dropped the missing value of the variable ‘CREDIT_LIMIT as there was only one observation missing
* Dropped the variable ‘CUST_ID’

# Exploratory Data Analysis (EDA)
* Checked the probability density of the variables and also the correlation between them in order to get a better understanding of patterns and trends 

![](https://github.com/LeonardoGiroldo/Bank_Marketing_Segmentation/blob/main/Image1.png)

# Model Building
* First, I standardized the data due to the magnitude
* Found the optimal number of clusters by using the elbow method

![](https://github.com/LeonardoGiroldo/Bank_Marketing_Segmentation/blob/main/Image2-Elbow.png)

* Applied the K-means method
* Applied Principal Component Analysis (PCA) to get a different insight from the data

![](https://github.com/LeonardoGiroldo/Bank_Marketing_Segmentation/blob/main/Image3-PCA.png)




