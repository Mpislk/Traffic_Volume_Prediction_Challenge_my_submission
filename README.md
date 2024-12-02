# Traffic_Volume_Prediction_Challenge\n
My solution of MachineHack's 'The Great Indian Hiring Challenge 2025'\n
The problem statement is to accurately predict or rather forecast the volume of Traffic given different climatic conditions like Temperature, cloud cover etc.\n
Also, the train data spans between October 2008 and June 2014 (on hourly basis) while the test data spans the next three months (July to Septmeber) of 2014. \n
Given Features: Temperature, Rainfall_last_hour, Snowfall_last_hour, Cloud_Cover, Weather, Weather_Desc, Date, TimeStamp \n
Target variable: Traffic_Vol \n
The model used is Gradient Boosting Regressor (upon better performance compared to Linear Regression and Random Forest Regressor by trial-and-error). The model achieved root_mean_squared_error around 900 on test dataset. \n
