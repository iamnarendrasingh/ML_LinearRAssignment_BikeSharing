# Project Name
> ML_LinearRAssignment_BikeSharing


## Table of Contents
* [Problem Statement](#general-information)
* [Business Goal](#business-goal)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.



## Business Goal
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1.	Demand for bikes has increased from 2018 to 2019. 100 % hike against 2018.
2.	Month plays very important role as Jan- Jun there is very high demand for the bikes.
3.	Demand for bikes is high during the fall season and next will be summer, winter, and spring seasons.
4.	Demand for bikes increase with weather.
5.	Demand on working days is slightly higher. However it is not that much correlated.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

=========================================
## Technologies Used
=========================================
1. pandas as pd: for data manipulation and analysis.
2. numpy as np: for numerical operations.
3. -matplotlib.pyplot as plt: for data visualization.
4. seaborn as sns: for data visualization.
5. autoviz.AutoViz_Class from the autoviz library: for automatic visualization of data.
6. matplotlib.gridspec as GridSpec: for creating subplots in Matplotlib.
7. sklearn.model_selection as train_test_split: for splitting data into training and testing sets.
8. statsmodels.stats.outliers_influence as variance_inflation_factor: for calculating variance inflation factors.
9. warnings: for handling warnings during code execution.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

Dataset characteristics

day.csv have the following fields:
	
	- instant: record index
	- dteday : date
	- season : season (1:spring, 2:summer, 3:fall, 4:winter)
	- yr : year (0: 2018, 1:2019)
	- mnth : month ( 1 to 12)
	- holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	- weekday : day of the week
	- workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	+ weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	- temp : temperature in Celsius
	- atemp: feeling temperature in Celsius
	- hum: humidity
	- windspeed: wind speed
	- casual: count of casual users
	- registered: count of registered users
	- cnt: count of total rental bikes including both casual and registered
	
## Contact
Created by [@iamnarendrasingh] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->