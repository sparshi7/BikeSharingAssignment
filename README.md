# Bike Sharing Assignment
Bike Sharing Assignment as part of Upgrad IIIT Bengaluru course in Machine Learning and AI is to identify the driving factors behind bike sharing demand for BoomBikes, a bike-sharing provider, so that they can build a strategy to meet the business demand levels and understand dynamics of a new market.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusion](#conclusion)
* [Contact](#contact)

## General Information
- **Business Understanding**: A US bike-sharing provider **BoomBikes** have contracted a consulting company to understand the factors on which the demand of their shared bikes depends. Specifically, they want to understand the factors affecting the demand for the shared bikes in the American market. The company wants to know:
  - Which variables are significant in predicting the demand for shared bikes
  - How well those variables describe the bike demands

- **Problem Statement**: We are required to model the demand for shared bikes for BoomBikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

- **Dataset**: In the dataset provided, there are three columns named 'casual', 'registered', and 'cnt'. The variable 'casual' indicates the number of casual users who have made a rental. The variable 'registered' shows the total number of registered users who have made a booking on a given day. The 'cnt' variable indicates the total number of bike rentals, including both casual and registered. 'cnt' is the target variable for building the model and predicting the demand of bike sharing.

## Technologies Used
- pandas - version 2.1.4
- numpy - version 1.26.4
- matplotlib - version 3.8.0
- seaborn - version 0.13.2
- sklearn - version 1.2.2
- statsmodels - version 0.14.0

## Conclusion
Major driving factors behind bike sharing demand are mentioned below:
 - **Positively impacting features**:
   - temp
   - yr
   - winter
   - Mon
   
- **Negatively impacting variables**:
  - light_snow_rain
  - windspeed
  - misty_cloudy
  - spring


## Contact
Created by @sparshi7 - feel free to contact me!
