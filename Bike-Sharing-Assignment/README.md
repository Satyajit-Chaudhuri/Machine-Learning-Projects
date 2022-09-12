# Bike Sharing Assignment 

## Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.- The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc



## Business Goal

The company wants to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.



## Model Equation:

**cnt = 0.4103 * temp + 0.2422 * yr - 0.0746 * holiday - 0.0966 * windspeed - 0.1619 * season_spring + 0.0852 * season_winter - 0.0663 * mnth_dec - 0.0538 * mnth_july + 0.0543 * mnth_mar - 0.0816 * mnth_nov + 0.0478 * mnth_sept + 0.0846 * Clear - 0.01878 * Light-RS + 0.1661**

### The Major Factors affecting the bike hiring are : 

- Temperature
- Year
- Holiday
- Windspeed
- Season
- Month
- Weather

### Factors positively affecting the hiring:

- Temperature
- Year
- Season winter
- Month march
- Month september
- Clear Weather


### Factors negatively affecting the hiring:

- Holiday
- Windspeed
- Season spring
- Month december
- Month july
- Month november
- Light rain

### Strategic Planning for BoomBikes:

- The temperature has a positive impact on hiring trends. So the company should be prepared for higher demands during higher temperature days.
- Year-on-Year hiring rates has increased which is a positive news for the company. They can expect a greater demand in the coming year.
- The hiring rates are relatively lesser in the holidays, so they should focus more on renting out during the working days.
- Windy days attract lesser bike hires. Hence they should focus more on boosting sales during less windy days.
- People are more likely to hire bikes on a clear weather day then a rainy one. Hence focus should be more on attracting customers on a clear day.
- The hiring will be more during the winter seasons then compared to the others. So they should look forward to gaining more profits during this season.
- The months of March and september will attract a higher hiring rate whereas July, November and December will see a lesser demand. Hence the company can plan to rebalance manpower appropriately.



## Technologies Used

- pandas - version 1.2.4
- numpy - version 1.20.1
- seaborn - version 0.11.1
- matplotlib - version 3.3.4

## Acknowledgements
Give credit here.
- This project was inspired by IIITB & Upgrad's - Linear Regression case study.



## Contact
Created by [@Satyajit-Chaudhuri]- feel free to contact us!# Project Name
