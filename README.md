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

Furthermore, because of the existence of null values in some records, the data needs to be preprocessed before any further processing.

## Data Preprocessing
In its current form, the data is not ready for analysis.  First, the non-relevant columns must be dropped, as well as the features of the relevant columns need to be converted from object data types to numerical data types.  
After my initial overview of the data set, I have decided to focus on only four features: accident severity, weather conditions, road conditions, and light conditions.
In order to get a good understanding of the dataset, I have checked different values in the features. The results show, the target feature is imbalance, so we use a simple statistical technique in order to balance it.
