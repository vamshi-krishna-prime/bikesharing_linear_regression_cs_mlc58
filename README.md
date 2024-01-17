# Bike Case Study || Muliple Linear Regression model building exercise

> This assignment is a programming assignment wherein we are building a multiple linear regression model for the prediction of demand for shared bikes. The model will be a good way for management to understand the demand dynamics of a new market.


## Table of Contents
* [General Info](#general-info)
* [Dataset Used](#dataset-used)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Case Study exploits information provided in a dataset where Bike Rental information is mentioned for registered and casual users in different seasons, weather conditions for following years - 2018 and 2019.
- Refering to the dataset Business wants a multiple linear regression model developed to predict the demand of users in future. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Dataset Used
> Files used in this Case Study are provided from Upgrad team
 - day.csv --> this file contains Bike Rental information is mentioned for registered and casual users in different seasons, weather conditions for following years - 2018 and 2019.
 - Readme.txt --> data dictionary file has description of all columns i.e. meaning of these variables and their related values referred in day.csv


## Technologies Used
- Python Library - version 3.0
- Jupyter Notebook
- CSV file
- Excel file


## Conclusions
- Based on the final model, following are the 3 features contributing significantly towards the demand of shared bikes:
	- “temp” (Positive correlation)
	- “yr” (Positive correlation)
	- “Weathersit” as “Thunder” (declared as 'Thunder' with value '3') is negatively correlated


## Software requirements
This case study uses `Python 3.10` version and is designed to be compatible with versions greater than '3.6'. It is highly recommended that you use the `Anaconda` distribution to install Python, since the distribution includes all necessary Python libraries as well as Jupyter Notebooks. The following libraries are expected to be used in this project:

+ NumPy
+ Pandas
+ Matplotlib
+ Seaborn
+ Math
+ Conda
+ Git
+ Jupyter Notebook
+ Statsmodels
+ Scikit learn

**NOTE:**
`environment.yaml` file is provided to install all the necessary libraries in the environment to replicate the same work flow.
