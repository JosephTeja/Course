# Boom Bikes Rental Predictions
Creating a Linear regression Model on Boom Bike Rentals as part of Upgrad course assignments


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- We have used multiple linear regression model to detect the count of bike rentals with using variables like temperature, weather, humidity, holiday, etc.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The R-squared value of the train set is 81 % whereas the test set has a value of 86.11% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model. 
Year (1.0601 coefficient): Each subsequent year sees an increase in bike rentals, reflecting either growth in the service or rising popularity of bike rentals over time.
- Temperature (0.4294 coefficient): Higher temperatures positively affect bike rentals, indicating that warmer weather encourages more people to rent bikes.
- Seasonal variables: The coefficients for months and seasons (such as spring, winter, December, January, July, November) suggest differential impacts on bike rentals. For example, the negative coefficient for spring (-0.5541) suggests a decrease in rentals compared to the baseline (likely summer), while winter has a positive effect (0.3244), indicating more rentals than in spring.
- Specific months like September (0.2140 coefficient) and November (-0.3247 coefficient): These also show significant variations, with September increasing bike rentals and November decreasing them.
- Weather conditions: Light snow (-1.3117) and mist or cloudy conditions (-0.3541) both negatively impact bike rental counts, indicating fewer rentals during less favorable weather conditions.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
- numpy
- RFE

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@JosephTeja] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->