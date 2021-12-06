# Written Report for the Pyber Project

## Overview of PyBer Challenge 

- Through this module we were provided ride sharing data. With the data provide we are able to create (learned through the module) many different kinds of charts and dataframes in order to provide helpful data to PyBer. 
### Purpose

- The purpose of this challenge was to provide data to PyBer in order to improve access to ride-sharing services and determine how affordable ride-sharing services are for those underserved areas. 

## Analysis and Challenges

- First thing we did was set up a new DataFrame from the data provide. 
- See PyBer_Analysis\analysis\Challenge_df.PNG
- With our first DataFrame set up we are able to filter to the relevant data that PyBer wants to use. 
- With the instructions provided we ended up with data specifically in the first third of the year, 2019-01-01 to 2019-04-29. Sample code provided these dates. 
### Analysis of Outcomes 

- We were able to set up a graph to present our findings through the use of the new resampled DataFrame as well as Matplotlib using the df.plot() method.
- See PyBer_Analysis\analysis\Challenge_df.PNG 

### Challenges and Difficulties Encountered

- The main difficulty I encountered throughout this challenge was setting up correct DataFrames with the correct lables. 
- One other challenge was that my data does not line up with the module data examples but I used slightly different dates. The code can be easily editted however to fit different dates. 

## Results

- With the dataframe we created we are able to compare the averages of fairs for the three different areas, Rural, Suburban, and Urban.
- We found that Rural areas, have a significantly higher average in fairs for both the riders as well as drivers, this would be a sign of under saturation because the Rural area also has the least amount of total rides by a significant margin. 
- We also found that there is a negative corelation in the month of March in regards to fair totals. While Urban reached its peak in the month of March both Suburban and Rural areas fall to lows in terms of totals. 
