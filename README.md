# PyBer Analysis
This is an analysis of a  ride-sharing app to explore rideshare data and to help improve access to rideshare services and find better pricing. We will use visualization and Matplotlib library to better understand the data and convey the information.
## Overview of the analysis:
The data provides information for rides in each city. The ride information includes fare and date. Other information that is provided are type of the city and number of drivers that work in that city.
The first analysis to perform is to find the number of rides in each type of city. The type of city can be Rural, Suburban, or Urban. There were 1,625 rides in urban cities, 625 in suburban cities, and 125 in rural cities. Putting these data in a pie chart will result in:

![Pie chart for the number of rides for each City type](analysis/Fig6.png)

The next study is performed on the number of drivers for each city type. There were 2,405 drivers for urban cities, 490 drivers for suburban cities, and 78 drivers for rural cities. Putting these data in a pie chart will result in:

![Pie chart for the number of drivers for each City type](analysis/Fig7.png)

The next analysis is to find the total amount of fare charged for each city type. There was an income of $39854.38 for urban cities, $19356.33 for suburban cities, and $ 4327.93 for rural cities. Putting these data in a pie chart will result in:

![Pie chart for the total amount of fare for each City type](analysis/Fig5.png)

Using these data, the average fare per ride and average fare per driver can be calculated. These results are shown in the following table:


![Summary](analysis/summary_data.PNG)

The next step is to get deeper into the data and find the total fare by city type for specific date ranges, January 2019 to March 2019, and plot this information in a weekly format. To show this data, first, we need to confine our table to these specific dates and then pivot our table to get information for each city type. The last step is to resample it using the weekly format and plot it. This plot is shown in the following figure:

![Summary](analysis/PyBer_fare_summary.png)

## Summary:
This was a very in-depth analysis of the data provided for each city type. This is the information that can be extracted from the above graphs

  - Urban cities use the app the most and there are more drivers in urban cities. As a result, the majority of PyBer's revenue occurs in urban cities.
  - On the other hand, the costs for using PyBer are greater among riders in rural cities than in urban cities. This could potentially discourage riders from using PyBer given the high average fare per ride.
  - Drivers in rural cities are earning more than drivers in urban cities. This could potentially discourage drivers from working with PyBer given the low average fare per driver.
