# Data science Capstone project : Richter's Predictor. Modeling Earthquake Damage 

# Overview

Based on aspects of building location and construction, your goal is to predict the level of damage to buildings caused by the 2015 Gorkha earthquake in Nepal. The data was collected through surveys by Kathmandu Living Labs and the Central Bureau of Statistics, which works under the National Planning Commission Secretariat of Nepal. 

This survey is one of the largest post-disaster datasets ever collected, containing valuable information on earthquake impacts, household conditions, and socio-economic-demographic statistics.

# Problem description

We're trying to predict the ordinal variable damage_grade, which represents a level of damage to the building that was hit by the earthquake. There are 3 grades of the damage:

•	1 represents low damage 

•	2 represents a medium amount of damage 

•	3 represents almost complete destruction 

# project Flow


•	merge the two dataset

•	Few vizualizations to discover the data we have to work with

•	change the object type columns to int

•	Train Test Split

•	We will start with RandomForestClassifier

•	F1 score is used for model accuracy

•	We will look at the confusion matrix

•	Look at the features importance: Top 10 Random Forest importance

•	fit the train data to common classifiers to see which one of these performs better on a first approach

• Dealing with outliers

•	Saving the final model using Joblib¶


 



