### Space-Time Prediction of Scooters Demand and use case design
Space-time prediction models are built using OLS regression to predict scooter activity. Two models are built here: one based on the demand of each census tract in the city and another one based on the demand of each 300 * 300 meters grid cell in each census tract. With the prediction result, we calculate the subtraction of supply and demand, then design an app use case for re-balancing staff based on the prediciton result.

<img src="images/app.png?raw=true"/>

**For more details about the prediction see [R Markdown](/html/scooters.html)**