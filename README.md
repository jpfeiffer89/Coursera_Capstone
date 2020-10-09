# IBM Coursera_Capstone: Car Accident Severity Report
## Introduction | Business Problem
According to the National Highway Traffic Safety Administration (NHTSA), 36,096 people died in motor vehicle crashes in 2019.  In an effort to reduce car accident fatalities, an algorithm must be created to predict the probability of an accident given several parameters: weather, road and visibility conditions.  In the future, when these conditions are poor, a service will alert drivers and remind them to drive more carefully. 
## Data
The data was collected by the Seattle Police Department and Accident Traffic Records Department from 2004 to present.
The data consists of 37 independent variables and 194,673 rows. 
Our predictor variable will be 'SEVERITYCODE' because it is used measure the severity of an accident on a scale from 0 to 5 within the dataset (outlined below). Attributes used to weigh the severity of an accident are 'WEATHER,' the weather conditions, 'ROADCOND,' the road conditions, and 'LIGHTCOND,' the visibility. 
### The severity code meanings:
0 : Little to no Probability (Clear Conditions)

1 : Very Low Probablility - Chance or Property Damage

2 : Low Probability - Chance of Injury

3 : Mild Probability - Chance of Serious Injury

4 : High Probability - Chance of Fatality

