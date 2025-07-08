# Traffic_Volume_Prediction_Challenge
This repository contains my solution for MachineHack's 'The Great Indian Hiring Challenge 2025'.\
The problem statement is to accurately predict the volume of Traffic given different climatic conditions like Temperature, cloud cover etc.\
Also, the training data spans between October 2008 and June 2014 (on hourly basis) while the test data spans the next three months (July to Septmeber) of 2014. \
Given Features: Temperature, Rainfall_last_hour, Snowfall_last_hour, Cloud_Cover, Weather, Weather_Desc, Date, TimeStamp. \
Target variable: Traffic_Volume \
The model used is Gradient Boosting Regressor (upon better performance compared to Linear Regression and Random Forest Regressor by trial-and-error). The model achieved root_mean_squared_error around 900 on test dataset.
