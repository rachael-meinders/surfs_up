# Surfs Up Analysis

## Project Overview
In the pursuit of opening a Surf 'n' Shake shop in Oahu, Hawaii, an invesor has tasked me with evaluating historical weather data to help evaluate the business's chance of successs.

### Purpose
1. Connect to and query from the provided .sqlite data file
2. Analyze the climate using the previous year's daily temperature and precipitation
3. Identify the most active temperaure-recording stations
4. Display these results with a Flask webpage

### Resources
- Data Sources: hawaii.sqlite
- Software: Python 3.6.1, Jupyter Notebook, Flask

## Challenge Overview
An investor has tasked me with examining the temperaure trends for June and December in order to evaluate year-round sustainability. I persoanlly chose to extend this analysis to the precipitation measuremens for each month as well.

### Challenge Purpose
1. Collect the temperature records for June and December
2. Create a dataframe for these records
3. Create and display summary stats for June and December temperatures

### Challenge Results
- Daily temperatures are roughly 70-80°F year round, with December average temperature dropping only 3°
- Max daily temperature is 85°F in June, and 83°F in December
- The standard deviation for both months is less than 4°
These statistics indicate that the weather in Oahu is fairly consistent and predictable for both summer and winter. This gives confidence to Surf 'n' Shake's year-round demand.

- Winter in Oahu has slightly more daily precipitation with an average of .21", rather than .13" average in June.
- Less than 25% of days in June and December had a daily precipitation of .15"
- June had a standard deviation of .33" and December had a standard deviation of .54"
These statistics indicate that Oahu overall does not have a lot of precipitation, with winter having both more rainy days and less overall predictability.

<b>Overall, this analysis establishes that the weather conditions in Oahu, Hawaii should not be an obstacle to both initial and year-round success for Surf 'n' Shake.</b>


![image](https://user-images.githubusercontent.com/90879979/143083709-89be7fac-624a-4e80-8d81-0b6c0c1f80dd.png)
--
![image](https://user-images.githubusercontent.com/90879979/143083773-3a3024eb-992e-4c4d-a279-def384c43b5a.png)
