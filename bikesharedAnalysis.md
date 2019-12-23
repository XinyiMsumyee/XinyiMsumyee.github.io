## Bike shared data analysis

**Project description:** Bike share System gains popularity as a healthy, and low-carbon mode of travel. It is economical, energy-saving, environmentally-friendly, flexible and convenient. However, when the planning and maintaining the system, there appears great amounts of problems like bicycles re-balancing. Knowing the demand of the system ahead could be helpful to mitigate the unbanlance. By analyzing the travel patterns of different user groups and the demand across the space, related predictors are selected for model building. Time-space predicting model is built to predict the bike activity of the system, with which, administrators can easily gain actionable insight into demand change in time and space, and therefore could better allocate the resources to those crowded stations.
<br>
<img src="images/wordCloud_bike.png?raw=true"/>

### 1. Analysis of Urban Residents’ Travel based on Shared Bicycle Data
As a preliminary exloratory analysis, this research focus on the bike trips in January, Apirl, July and October, 2018. Space-time characteristics of bike acitivity in NYC and the activity patterns of different user groups are analyzed first. Moreover, factors like temperature that might influence bike activity are figured out, which paves path for the demand prediciton. 

Clustering analysis are conducted respectively based on the geographic coordinate, and transition pattern of stations as well as station activity. The results are mapped to city map in order to understand the flow of residents in different time and how the surroundings affect the bike activity of each station.

<img src="images/bikeAnalysis1.png?raw=true"/>
<img src="images/bikeAnalysis2.png?raw=true"/>
<img src="images/bikeAnalysis3.png?raw=true"/>

### 2. Analysis system built on Google Earth Engine
This system enable users to analyze the trips generated on their interested date and hour. 
<img src="images/gee1.png?raw=true"/>

Daily or hourly bike activity of stations within 1 kilometer of selected location are visualized using map and bar plot. At the same time, the weather information and longitude as well as latitude of selected location are also provided. 

<img src="images/gee2.png?raw=true"/>

### 3. Site planning for new bike station using ArcPy
When planning for new station, I think distance to facilities, like subway stops, population density, as well as current bike activity are important. Thus, based on these, I conduct the analysis using ArcPy and visualize the result on Google Earth Engine.
<img src="images/siteplanning.png?raw=true"/>

### 4. Space-Time Prediction of Bike Share Demand
In this report, a prediction model for bike share ridership is built based on bike share data of Citi Bike in NYC in September 2019, taking not only spatial and temporal effects but also time lags and holiday effects into account. Generally, the model performs well in predicting the demand in the bike share system and can track the spatio-temporal component of bike usage. However, the model yields rather high errors for active stations, and underpredict the activity especially for periods of high demand. With the result, the overall usage could be easily obtained, but we do not recommend predicting the system demand in specific stations that observe active bike activity in high-demand hours like peak. Otherwise, the underprediction may cause the insufficient docks as well as bikes in hot station, and therefore, the user dissatisfaction and loss.

**For more details about the prediction see [R Markdown](/html/spacetime.html)**
<img src="images/bikeActivity.gif?raw=true"/>
