
# PREDICTION OF POPULATION GROWTH AND AIDS INFECTION BASED ON US HEALTH STATS DATA

Machine Learning (ML) is transforming the world with research breakthroughs that are leading to the
progress of every field. Therefore, prediction algorithms are now capable of solving many of the complex
problems by leveraging the power of data. The models are capable of correlating a dataset and its features
with an accuracy that humans fail to achieve. To carry out this project, Health Statistics provided the
statistics of key health, nutrition and population gathered from a variety of international sources. Some of
the parameters include population dynamics, nutrition, reproductive health, health financing, medical
resources. This project focuses on the prediction of the population growth and AIDS related deaths with a
holistic approach including Data Preparation, Feature Analysis, Modelling Techniques, Visualization and
Insights. This report will be showcasing a detailed analysis of the procedure for predicting population
growth and AIDS related deaths.


Key Words: Feature Analysis, Prediction, Clustering, Population Growth Prediction, AIDS-Related
prediction

# Resource Requirement
| S.No 	| Item                        	| Description                                                                                                                                                                                                                                                                                   	|
|------	|-----------------------------	|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------	|
| 1    	| Operating System            	| Windows 10/ Mac                                                                                                                                                                                                                                                                               	|
| 2    	| Hardware                    	| Processor Core i7; RAM 8 GB                                                                                                                                                                                                                                                                   	|
| 3    	| GUI Development Environment 	| Jupyter Notebook (Anaconda)                                                                                                                                                                                                                                                                   	|
| 4    	| Programming Language        	| Python                                                                                                                                                                                                                                                                                        	|
| 5    	| Libraries                   	| Numpy, Pandas, Matplotlib, Seaborn,, Lightgbm, Sklearn, Missingno, Plotly, Scipy, DBSCAN, Kmeans, LinearRegression, RandomForest, Regressor, XGBRegressor, AdaBoostRegressor, SVR, statsmodels.api, StandardScaler, train_test_split, LSTM, Sequential, Dense, mean_squared_error, math, sqrt 	|

# DataSet

The given dataset is a time series data which has inputs from 1960-2015 for various countries and
health indicators. This dataset appears to be a collection from different types of sources such as the World
Bank, World Health Organization etc. The data set contains 345 health indicators from countries around
the world. The health indicators include information such as immunization rates, malnutrition prevalence,
and vitamin A supplementation rates across 258 countries around the world.

The data set is a time series data set containing different data types such as strings, categorical values,
decimals and negative values. 
All the health Indicators are continuous variables. 
The total record count in the given dataset is 89010. 
Data across variables are on different scales. Country name, country code,health indicator name and Health indicator code are categorical variables.
There are various types of health indicators in the data set, to name some, population dynamics, nutrition,
reproductive health, health financing, medical resources and usage, immunization, infectious diseases,
HIV/AIDS, population projections and lending


# File Execution

Feed the input file to program "data.csv" and then the python file will start executing the program.

**Note: input file must be placed in the correct directory**

We have multiple models in our project namely,

* Linear Regression 

* Random Forest 

* XGBoost

* AdaBoost

* SVM

* Neural Network (LSTM)

**Note: This file might take longer time to run based on model execution**

# Output

Output will be in the form of accuracies and visulisation.




