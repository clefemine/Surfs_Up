# Surfs_Up

## Project Overview

Provide the data needed to show the climate patterns of the island of Oahu. These data points are provided by multiple weather stations around the island. They collect percipitation and temperature data points. Descriptive analysis on the months of June and December will provide a better understanding of the island's climate fluctuations throughout the year. 

## Resources

- Data Sources: hawaii.sqlite
- Software: Python 3.7.6, Visual Studio Code, 1.45.1, Anaconda-Navigator (Jupyter Notebook)

## Summary

Using SQLalchemy we are able to interpret the data provided from hawaii.sqlite. Gathering the measurements from each station lists are then made according the information desired. SQLalchemy's extract feature allows the extraction of the desired month's measurements. Once we have a data frame of the desired month's data point pandas' describe function is use to provide descriptive statistics. 

## Results/Discussion

Comparing the results found in the descriptive statical analysis on June and December we see that there is a difference in the mean temperature per month. June has a higher mean temperature as well as maximum and minimum temperatures. The differences is at most 8 degrees farenheit. 
