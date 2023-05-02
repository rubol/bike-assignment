# Bike Sharing Linear Model
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


> In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


> They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

> Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Table of Contents
* [Business Goal](#business-goal)
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [License](#license)


<!-- You can include any other section that is pertinent to your problem -->

## Business-Goal

> You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## General Information 

- We will be using Multiple Liear Regression in Python to predit the demand for the bike service based o the historical data provided
- The repo contains a jupiter notebook with the implementation of the same


## Conclusions
- Final List of Features 'temp', 'windspeed', 'season_spring', 'season_summer',
       'season_winter', 'weather_light_snow_rain', 'weather_mist', 'month_Jan',
       'month_Sept', 'yr_2019', 'holiday_yes'
- R2 Score for the Trainig data - 83.4
- R2 Score for the Test Set - 80.0
- Final Equation - demand = 0.207978 + 0.458296 x temp - 0.155470 x windspeed - 0.050043 x season_spring +  0.058266 x season_summer +  0.087618 x season_winter - 0.286295 x weather_light_snow_rain - 0.077852 x weather_mist - 0.040339 x month_Jan + 0.090036 x month_Sept + 0.234864 x yr_2019 - 0.095612 x holiday_yes

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python 3
- Pandas
- Numpy
- matplotlib.pyplot
- seaborn
- sklearn.model_selection
- MinMaxScaler from sklearn.preprocessing 
- statsmodels.api
- variance_inflation_factor from statsmodels.stats.outliers_influence
- RFE from sklearn.feature_selection
- LinearRegression from sklearn.linear_model
- r2_score from sklearn.metrics

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by an assignment by upgrad


## Contact
Created by [@rubol] - feel free to contact me!


<!-- Optional -->
 ## License

- GNU 3.0 

<!-- You don't have to include all sections - just the one's relevant to your project -->