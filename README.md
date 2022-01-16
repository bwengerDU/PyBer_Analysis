# PyBer_Analysis

## Overview of the analysis

The purpose of this analysis is to provide the CEO of PyBer data analysis from the company's ride share activity from January through May of 2019. In order to analyze the data I have to utilize Jupyter to format data and create dataframes that would yield the necessary information. I used Groupby, count, and sum functions to analyze rider and fare data by city types grouped in rural, urban, and suburban areas. From these totals I calculated average fares per rider and driver. This information was then combined into a dataframe and was formatted to show USD$ on relevant columns. 

The second phase of the project aims to reformat the data so that a line plot map can be created to display total fares by city type. The Groupby, loc, pivot, and resample functions are utilized to calculate the sum of fares for each week by city type. Matplotlib is then used to translate this data into a multiple line graph to showcase performance of the three city types from January through April of 2019.  


## Results
The table below is the result of the work completed in Deliverable 1. 

Some of the main points that show in the data is that urban and rural areas occupy the two extremes while suburban cities occupy the middle ground in all categories. 

Rural areas have the least number of rides, drivers, and total fares, but they also have the highest fare per ride and driver amounts. 

Urban areas have the highest number of rides, drivers, and total fares, but they have the lowest fare per ride and driver amounts. 

These figures do make sense as rural areas have smaller populations and the rides that would be requested would cover greater distances, while urban areas would be comprised of a high volume of short drives. 

![alt text](https://github.com/bwengerDU/PyBer_Analysis/blob/main/Section%201%20Dataframe.png)


The multi line graph below is the result of work performed for Deliverable 2. 

![alt text](https://github.com/bwengerDU/PyBer_Analysis/blob/main/Resources/PyBer_fare_summary.png) 

## Summary

Three main outcomes are shown in the above dataframe and graph that would serve as useful insights into the company's operations and would allow the CEO to impliment new strategies. The first item to address would be to adjust the way they charge urban city passengers because they are currently averaging far below the other city types and it is the only city type that averages a lower fare per driver than it does per ride. Urban markets have a significant volume of shorter drives so a small rise in fares would have a significant amount for the company for drivers. Urban markets may also be suffering from an abundance of driver competition. This leads into the second observation that rural and suburban rides fetch a significantly higher amount of average fares. It may be an opportunity for some of these urban drivers to expand out and fetch higher fares, which would also grow the company's profit margins as they would be tapping into these higher wage ride opportunities. The third potential for growth would be delving into the peaks and valleys of the total fares during certain periods. Shifting drivers to meet these fluctuations would allow the company to take advantage of changing demands for rides. Allocating drivers to different city types during times of demand will allow the compamy to maximize their driver fleet and earn more money. 
