# Bike_sharing_assignment

# Project Name
> Bike Sharing Assignment
This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes.


# Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems
allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike 
can then be returned to another dock belonging to the same system.A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to
the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business 
plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.In such an attempt, BoomBikes 
aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned 
this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors
affecting the demand for these shared bikes in the American market. The company wants to know:
Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands Based on various meteorological surveys 
and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.


## Table of Contents
* General Info
* Technologies Used
* Conclusions
* Contact


## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems
allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike 
can then be returned to another dock belonging to the same system.A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to
the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business 
plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.In such an attempt, BoomBikes 
aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned 
this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors
affecting the demand for these shared bikes in the American market. The company wants to know:
Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands Based on various meteorological surveys 
and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.



## Conclusion

The performance metrics for the regression model indicate the following:

- **Adjusted R² Values:**
 -Train data adjusted r^2 : 73.02
  -Test data adjusted r^2 : 69.59
  

- **R² Values:**
  -Train data  r^2 :76.39
  -Test data r^2 : 74.2

These metrics suggest that the model explains a significant portion of the variance in the training dataset, with an R² value of **71.89**. However, there is a noticeable drop in performance when applied to the test data, as evidenced by the adjusted R² of **55.31**. This discrepancy may indicate some overfitting on the training data.

The selected features used in the model include:
- Year (`yr`)
- Working day status (`workingday`)
- Windspeed (`windspeed`)
- Seasonal indicators (`season_spring`,  `season_winter`)
- Month indicator for September (`mnth_sept`)
- Weekday indicator for Saturday (`weekday_sat`)
- Weather situation for moderate conditions (`weathersit_moderate`,`weathersit_bad`)

Future improvements may include feature engineering or exploring additional predictors to enhance model performance on unseen data.



## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.4
- matplotlib - version 3.4.3
- plotly - version 5.6.0
- seaborn - version 0.11.2
- statsmodels - version 0.12.2
- sklearn - version 0.24.2
- scipy - version 1.7.1



## Contact
https://github.com/Selvasankari8990/Bike_Sharing_Assignment



