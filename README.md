# taxi-fare-prediction
This project revolves around the prediction of a taxi fare in New York city. The aim was to build a model which would forecast the fare of a taxi ride (tolls inclusive) given basic information, like pickup and dropoff location. Fee for a ride is dependent on a taxi price-list, however, it can vary depending on a route and traffic congestion. The secondary aim was to compare how various machine learning models cope with the task of a regression. This basic information could later be used to build more advanced models for transportation companies for prediction of ride fares. 

Compared models:  
linear regression,  
decision tree,  
random forest,  
bagged tree,  
XGBoost.  

Dataset used in this project was made available in 2018 by Google for a Kaggle competition (https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction/rules). It consists of 55m rows and variables depicting coordinates of pickup and drop-off, exact timestamp of a pickup, passenger count and total fare for the ride. 

Since the dataset is too big to build models based on it, 100k rows were selected on random. Records from 2014 and 2015 were also omitted (prices may have been changing across the years, hence for prediction only the data from the latest years available were chosen). 
