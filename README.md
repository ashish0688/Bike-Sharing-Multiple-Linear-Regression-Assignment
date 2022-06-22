# Bike Sharing Assignment
> This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. You will need to submit a Jupyter notebook for the same. 

## Table of Contents
* Problem Statement
* Business Goal
* Dataset and Data Dictionary
* Steps Performed
* [Conclusions](#conclusions)
* Technologies Used
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
> In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
> They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    - Which variables are significant in predicting the demand for shared bikes.
    - How well those variables describe the bike demands
> Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Business Goal
> We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Dataset and Data Dictionary
> The following files are present inside datasets folder:
    - day.csv (dataset)
    - Readme.txt (data dictionary)

## Steps Performed
> Assignment is divided into following parts:
	- Reading and Understanding the Data
	- Data Quality Check
	- Data Cleaning
	- Exploratory Data Analysis
	- Creating Dummy Variables
	- Splitting the Data into Training and Testing Sets
	- Rescaling the Features
	- Building a Linear Model
	- F Statistics
	- Test Data Aalysis
	- Conclusion

## Conclusions
> According to the final Model, the top 3 predictor variables that influences the bike booking are:
	a. temp: A coefficient value of '0.5499' indicated that a unit increase in temp variable, increases the bike hire numbers by 0.5499 units.
	b. yr: A coefficient value of '0.2331' indicated that a unit increase in yr variable, increases the bike hire numbers by 0.0.2331 units.
	c. season_winter: A coefficient value of '0.1318' indicated that w.r.t season_spring, a unit increase in season_winter variable increases the bike hire numbers by 0.1318 units.

> The next best features that can also be considered are
	a. season_summer: A coefficient value of '0.0874' indicated that w.r.t season_spring, a unit increase in season_summer variable decreases the bike hire numbers by 0.0874 units.
	b. weathersit_Light Rain: A coefficient value of '-0.2880' indicated that, w.r.t Weathersit_Clear, a unit increase in weathersit_Light Rain variable, decreases the bike hire numbers by 0.2880 units.
	c. windspeed: A coefficient value of '-0.1552' indicated that, a unit increase in windspeed variable decreases the bike hire numbers by 0.1552 units.

## Technologies Used
	a. Python - 3.7.11
	b. matplotlib - 3.4.3
	c. seaborn - 0.11.2
	d. pandas - 1.2.4
	e. numpy - 1.8.5
	f. sklearn - version 0.21.3
	g. statsmodels - version 0.10.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->
## Acknowledgements

## Contact
Created by Ashish Kumar Singh[@ashish0688] - feel free to contact me!
