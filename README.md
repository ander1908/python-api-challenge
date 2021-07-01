# python-api-challenge
This was an exercise using pythong to visualize the weather data of 500+ cities around the world, utilizing geographic coordinates as a selective citeria.
We were to generate scatter plots of Temperature, humidity, cloudiness and wind speed as they related to latitude. Additionally, we were to run a liniear regression on each relationship, but further analyze the data. 
We seperated the data into northern and southern hemisphere and ran the data again with the regression analysis. 

The second portion of this wasa to create a heatmap that shows the humidity for every city we had chosen from Part 1. We were then to select a series of criteria for our "ideal weather condition"
Based on this, the rows that didn't meet the criteria were dropped from the data set. Then we used the google places API to find the first hotel for each city located within 5000 meters of the coordinates, and then mapped them on the humidity heatmap
