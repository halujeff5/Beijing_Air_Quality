# Beijing_Air_Quality

[Portfolio link](https://jeffreyngds.com/beijing-air-quality/)

### Because of China's industrial development which required large amounts of fossil fuel burning, the air quality of Beijing has suffered drastically. More research into the health of residents will be done to further demonstrate this well known urban problem for the city.

### This dataset comprises of hourly air quality metrics for Beijing in SO2 (sulfur dioxide), O3 (ozone), CO2 (carbon dioxide), NO2 (nitrogen dioxide), PM10 (particulate matter) PM2.5 (particulate matter), wind direction/speed, and precipitation etc. for various locations in the Beijing metro area from Mar 2013 to Feb 2017. There are a total of 12 stations. I chose to study sulfur dioxide and PM10 concentrations and forecasted it for the next 3 months. The five stations I chose lay in the NE, NW, E, C, and S parts of Beijing. The NE (Huairou) and NW (Dingling) lie in the outskirts of the city. I wanted to see if there was a noticeable difference in the sulfur and PM10 concentrations outside of the city since the winds have a dominant NE,NW direction on most days.

### Conclusion
### After using the ARIMA model which was unsuccessful. I used a LSTM with rolling windows which uses the previous 60 predictions to predict the next prediction. This algorithm with LSTM in Keras proved to be very accurate with a RMSE of 1. This LSTM with rolling windows prediction can be used in all time series predictions in this project to get accurate results. 
