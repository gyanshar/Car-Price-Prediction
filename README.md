# Car-Price-Prediction

## Aim:
This project aims to predict the prices of cars by using attributes like model name, company name etc.

## About the Dataset:

[Quikr-cars](https://www.quikr.com) 

QuikrCars helps you find, sell and buy used cars, new cars, bikes and scooters, commercial vehicles, bicycles and even spare parts and accessories. 

[Quikr-cars-dataset](https://www.kaggle.com/datasets/raihansoniwala/quikr-cars) (taken from Kaggle)

This dataset contains data of Quikr Cars about second hand cars. This data was web scrapped from their website and have data of about 1000 cars and have features like: Name, Company, Quikr Label (Platinum / Gold), Location, Price, Kms driven, Fuel type.

## Description:

Parameters: Name, Label, Location, Kms_driven, Fuel_type, Year, Owner, Company <br>
Model: Linear Regression <br>
Libraries Used: NumPy, Pandas, Matplot, Seaborn, Sklearn <br>
r2 score: *0.86* <br>

## Summary:

-	Analysed and trained 7 attributes using the Linear Regression model in Python to predict the price of used cars with a r2 score of 0.86
-	Used OneHotEncoder, OrdinalEncoder and StandardScaler in Sklearn to transform the categorical values to numerical values and to normalize the data values
-	Cleaned and Pre-processed 1,000 rows using Pandas in Python to prepare the data for analysis and used Seaborn and Matplotlib in Python for data visualization
