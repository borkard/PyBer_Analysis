# PyBer_Analysis

## Overview
Using [city_data.csv](https://github.com/borkard/PyBer_Analysis/tree/main/Resources/city_data.csv) and [ride_data.csv](https://github.com/borkard/PyBer_Analysis/tree/main/Resources/ride_data.csv), an analysis was conducted with Pandas and Python to determine the Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver for each type of city (Urban, Suburban, Rural). After creating a summary view of the ride-sharing data by city type, Matplotlib was used to create a multiple-line plot to show the total weekly fares for each type of city.

## Results
From the summary of ride-sharing data, it can be concluded that the number of "Total Rides" and "Total Drivers" is highest in Urban cities and decreases significantly in Suburban cities and still more in Rural cities. The "Total Rides" for Urban cities is 93% higher than in Rural cities and 62% higher than in Suburban cities. The "Total Drivers" for Urban cities is 97% higher than in Rural cities and 80% higher than in Suburban cities. The "Total Fares" for Urban cities is 89% higher than in Rural cities and 49% higher than in Suburban cities. While Urban cities brought in the most revenue ("Total Fares"), the "Average Fare per Ride" and "Average Fare per Driver" are inversly proportional to city size and are both significantly higher in Rural cities and decrease as the city size increases and is classified as Suburban and Urban. While the "Total Fares" for the Urban cities are 10.86% higher than those of Rural cities, the "Average Fare per Driver" is nearly 30% higher for Rural cities than for Urban cities and the "Average Fare per Ride" is also 29% higher for Rural cities than for Urban cities. According the the monthly view of the Total Fare by City Type (in graph below), all city types follow a similar cadence in Total Fares from January-April 2019, with the exceptions of Rural fares nearly reaching a plateau  between March and April while Suburban and Urban fares slightly peak, and Suburban Fares steeply spiking in April as Urban and Rural fares decrease. The Suburban Fares also decline slightly in late January and have a sharper peak and decline in fares in late March compared to Urban and Rural fares.

*Ride-sharing data by city type:*
![PyBer_summary_dataframe.PNG](https://github.com/borkard/PyBer_Analysis/blob/main/analysis/PyBer_summary_dataframe.PNG)

*Line Graph: Total Fare by City Type*
![PyBer_fare_summary.png](https://github.com/borkard/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

Based on the results, to address any disparities among the city types, I would recommend that the CEO look into the fares per ride for 
