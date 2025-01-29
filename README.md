# Bike Sharing Assignment
> This assignment was to prepare a linear regression model to predict the demand of bike rentals that the company can anticipate based on various factors so that the company can reap maximum profits based on the demand that the model is predicting.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- In this project we have used Linear Regression Modelling technique to predict the demand of Bike Shraing sales for the company.
- We need to come up with a Linear Regression Model to predict the demand of Bike Sharing that might come up when business is back to normal.
- Predict the demand of Bike Sharing sales for the company once business is back to normal, basically what all factors are more likely to effect these sales, so that the company can align its
marketing strategies accordingly to reap maximum profits.
- Dataset which was used included many factors such as temperature, humidity, date of rental, season, month, year, windspeed etc to predict the count of sales on any given day.


## Conclusions

- As per the pair-plot and correlation matrix among the numerical variables, ‘atemp’ and ‘temp’ has the highest correlation with the target variable ‘cnt’.

- The top three features which are significantly explaining the demand of the shared bikes are: temp, hum and yr, while ‘temp’ and ‘yr’ have a positive impact on the demand of the bikes but ‘hum’ have a negative impact on the demand of shared bikes.

- Categorical variables have a significant effect on the target variable as many categorical variables like season (spring, winter), month (July, September), weekday (Monday) and weather situation (Misty) have ended up in the final model with very low p-value indicating their high significance in predicting the dependent variable. Their low p-value indicates each variables’ significance towards the prediction of the target variable with very less multicollinearity effect as indicated by low VIF.


## Technologies Used
- Python libraries such as Matplotlib(3.8.4), Seaborn(0.13.2), Numpy(1.26.4), Pandas(2.2.2), Stats Model(0.14.2), scikit-learn (1.4.2) are used.
- Analysis has been done using Jupyter Notebook(7.0.8)

## Contact
Created by [@akash-bhardwaj] - feel free to contact me!
