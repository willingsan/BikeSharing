# Bike Sharing Linear Regression Assignment
A US bike-sharing provider BoomBikes wants to understand the demand for shared bikes among the people in post covid world. They want to know the top features that they must consider so that they can tap the market's growth potential and improve their revenue situation.

This project is an attempt to model the demand for shared bikes with the available independent variables. This will help the management of BoomBikes to understand the demand dynamics of the new market.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

A US based bike-sharing provider has suffered losses due to COVID pandemic lockdown. The management wants to reposition themselves in the market after the Covid led restrictions are lifted. For that, they want to analyse the factors that greatly impact the bike rental business. This project provides that information after applying machine learning techniques and various statistical processes on the provided dataset. The company has suffered revenue losses, so we want to address that business problem and aspire to provide them with exact information on the factors that affect the bike sharing demand.

The dataset provided is named day.csv.


## Technologies Used
	- Python - version 3.11.5
	- jupyter notebook - version 6.5.4
	- matplotlib - version 3.7.2
	- seaborn - version 0.12.2
	- pandas  - version 2.0.3
	- numpy - version 1.24.3
	- plotly - version 5.9.0


## Conclusions

#### Recommendations for BoomBikes
Bike sharing business has major impact of these three top features:- temp, season_winter, yr. Coefficient of 0.479 & 0.4 for temp indicates that one unit increase in temp, improves bike rental count by 0.4 approx. Coefficient of 0.23 for yr indicates positive trend, and the bike rental business is likely to increase in year on year basis.

Besides, weathersit_clear, mnth_sept, season_summer also have positive impact on bike hiring. So the company must focus on staying ahead of the competition during these periods.

windspeed negatively impacts bike rental service, and one unit of increase in windspeed, impacts it by 0.15 units.

season_spring has a negative coefficient. Company may plan to run promotions to boost the rental service.

#### Other recommendations
Since some seasons and weather situations (e.g. Mist, Cloudy, Heay Rain, Snow) are not conducive for the business, the company may think of using this downtime for staff training, bikes maintenance, overfall facilities upliftment, etc.


## Acknowledgements

This project was created for upGrad and IIITB Machine Learning & AI Program-October 2023, Linear Regression Assignment

## Contact
Created by Sanat Srivastava !

