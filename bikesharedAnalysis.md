## This can be your internal website page / project page

**Project description:** Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### 1. Analysis of Urban Residents’ Travel based on Shared Bicycle Data

As a preliminary exloratory analysis, this research focus on the bike trips in January, Apirl, July and October, 2018. Space-time characteristics of bike acitivity in NYC and the activity patterns of different user groups are analyzed first. Moreover, factors like temperature that might influence bike activity are figured out, which paves path for the demand prediciton. 

Clustering analysis are conducted respectively based on the geographic coordinate, and transition pattern of stations as well as station activity. The results are mapped to city map in order to understand the flow of residents in different time and how the surroundings affect the bike activity of each station.

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 2. Space-Time Prediction of Bike Share Demand

In this report, a prediction model for bike share ridership is built based on bike share data of Citi Bike in NYC in September 2019, taking not only spatial and temporal effects but also time lags and holiday effects into account. Generally, the model performs well in predicting the demand in the bike share system and can track the spatio-temporal component of bike usage. However, the model yields rather high errors for active stations, and underpredict the activity especially for periods of high demand. With the result, the overall usage could be easily obtained, but we do not recommend predicting the system demand in specific stations that observe active bike activity in high-demand hours like peak. Otherwise, the underprediction may cause the insufficient docks as well as bikes in hot station, and therefore, the user dissatisfaction and loss.
<img src="images/bikeActivity.gif?raw=true">
<br><br>
For more details check the R Markdown (/html/spacetime.html).
<br><br><br>
<img src="images/wordCloud_bike.png?raw=true"/>