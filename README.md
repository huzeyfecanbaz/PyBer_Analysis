# PyBer_Analysis

## Overview of the Analysis
The purpose of this project was to summarize and visualize the csv files provided in the package and make a dataframe that will show the ride sharing data by urban, suburban, and rural city type. The finding in the data drives us to generate a line graph that has multiple lines which shows total weekly fares by each city type. In order to pull and read the data pandas has imported and its several functions such as groupby(), sum(), count(), pivot(), resamble() and so on implemented throughout the process in order to get the total number of drivers, rides, and fares for each cit type. These information is used to calculate the average fare per driver and ride. All those informations used together to format into a new dataframe and reformat the columns. In the second part of the project, pivot() and resample() functions used to create a more meaningful data to implement it to create multiple line graph that show the total fares on weekly bases for each city type between the months of Jan and Apr 2019.
In this project, a series of the steps followed to provide the most accurate and logical code to the audience. The important functions and methods followed throughout the process as follows:
- Reading csv file by using pandas library.
- Cleaning and changing necessary data by using loc () function.
- Merge two datasets to generate a new DataFrame for more information.
- Perform calculations with the help of groupby () function.
- Visualize the data with tables and format them via map() method.
- Making pivot table by using pivot() function.
- Resampling the date time accurately via resample() function.
- Using matplotlob to create a line graph.

## Resources
- Data Source:PyBer_Challenge_starter_code.ipynb
- Software:Python,Pandas Library, Matplotlib Library, Numpy Library,Scipy Library, Jupiter Notebook.

## Results
The screenshot below is going to use to express the results found in this analysis.

https://github.com/huzeyfecanbaz/PyBer_Analysis/blob/65b203d93c435aaadd0dd91277cfc5aaa439a56b/analysis/Screenshot1.png

There are three main findings by using the picture above;
- The rural cities has the least amount of total rides, drivers, and total fares. However, it has the highest average fare per ride and fare per driver.
- Suburban cities are located in the second place for all the total rides, drivers, and total fares,verage fare per ride and fare per driver.
- Lastly, urban cities has the highest amount of rides, drivers, and total fares. However, it has the least amount of average fare per ride and per driver.
The graph below explains the weekly change in the total fare by city type in USD dollars.
https://github.com/huzeyfecanbaz/PyBer_Analysis/blob/65b203d93c435aaadd0dd91277cfc5aaa439a56b/analysis/PyBer_fare_summary.png

## Summary
As a summary, the data gathered from the csv files help us to tell the trends and general pictures of what kind of fares will be dominated based on the city type the passenger is a ride in. The analysis gives an idea what fares will look like based on weekly change on each city type and it will lead us to decide the future steps for the emerging areas. The analysis explicitly exhibited that the rural cities gives a higher fare because the mileage is longer than usual and it makes the ride longer and higher average fares per ride and driver who are working for this areas. The recommendations for the company as follows;
- The analysis showed that the urban city drivers are earning less than other city types and it should be fixed with others.
- Make a dynamic change in the charges based on the number of riders in the cities during a certain months.
- There might me a circulation for the drivers for different city types.
