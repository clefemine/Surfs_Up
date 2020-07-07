# Surfs Up

## Project Overview

Provide the data needed to show the climate patterns of the island of Oahu. These data points are provided by multiple weather stations around the island. They collect precipitation and temperature data points. Descriptive analysis on the months of June and December will provide a better understanding of the island's climate fluctuations throughout the year. 

## Resources

- Data Sources: hawaii.sqlite
- Software: Python 3.7.6, Visual Studio Code, 1.45.1, Anaconda-Navigator (Jupyter Notebook)

## Summary

Using SQLalchemy we are able to interpret the data provided from hawaii.sqlite. Gathering the measurements from each station lists are then made according the information desired. SQLalchemy's extract feature allows the extraction of the desired month's measurements. Once we have a data frame of the desired month's data point pandas' describe function is use to provide descriptive statistics. 

## Results/Discussion

Comparing the results found in the descriptive statistical analysis on June and December we see that there is a difference in the mean temperature per month. June has a higher mean temperature as well as maximum and minimum temperatures. The differences is at most 8 degrees Fahrenheit. 

Recommendations for further analysis:
- Analyze precipitation rates to see if any flooding occurs. Filter to see only high amounts of precipitation recorded. Find where these stations are located that read these amounts. See if these heavy rains last for multiple days. Flooding could cause major damage to your shop so it is something to consider and plan for. 
- Correlate precipitation and temperature data. It would helpful to know if when temperatures drop then does precipitation increase or vice versa. If they are negatively correlated then this could mean that there might be less sales on those days but overall there will be more hot days with no rain. Use the dates that the data was collected to compare the two measurements. Take the average of the temperature when precipitation is very low and when it is very high. 
