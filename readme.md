# Flight Delay Data Exploration
## by  Walid Naous


## Dataset

> The dataset chosen is for Domestic Flight record for the USA in the mo the July 2018 (the busiest month of the year). Follwing the download of the data, the dataset has been wrangled as follow:
- Delay departure that is zero have been dropped.
- Origin Airport and Airline carrier ID have been replaced with their corresponding full name
 - Date column have been trasnformed to datetime type
 - Delay departure more than 20 minutes have been dropped to remove outlier
 - Top 50 origin airports have been selected to work with to decrease the amount of data


## Summary of Findings

> South West Airlines,Delta Airline and American Airline represented the most delay in departure. Departing delay in US airports ranges from 1 minutes to 200 minutes with right skewed Hist.
In terms of origin airport departure delay, the top 3 airports are Atlanta, Chicago and Dallas/Fort Worth.
It was also found that departure occurence is steady between the time of 6 am and 5pm. Where the peak in departure delay at 6 am in the monring. 
In addition, it was found that airline such as Southwest have their departure delay increase as the day progress but in general all airline do not have a high departure delay duration, indication that airlines are on average ontime taking off.


## Key Insights for Presentation

> Southwest Airline and Atlanta airport presented the most departure delay occurence, while flying at 6 am during the month of July indicated the highest number of delay in deaprting. Moreover, it was also observed that day of the month do not have any major effect on delay occurence. Lastly, the mean departure time for all domestic airline was between 11 am and 1 pm.