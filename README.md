🌧️ Project: Predict Rainfall
This project aims to predict the occurrence of rainfall based on daily meteorological statistics such as atmospheric pressure, maximum temperature, mean temperature, minimum temperature, dew point, humidity, 
cloud coverage, sunshine duration, wind direction, and wind speed.

Given the complexity and potential multicollinearity among these features, we applied a feature selection process to identify the most informative variables. The final set of selected features includes:

Humidity
Cloud coverage
Sunshine duration
Wind speed
Rainfall (binary target)
Diff_temp_dewpoint (the difference between air temperature and dew point)

After testing several models, we determined that XGBoost delivers the best performance, achieving a ROC AUC score of 0.888271.

