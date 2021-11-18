Written Analysis
Overview of the Analysis: 
Explain the purpose of the new analysis.
The purpose of this new analysis is to create a summary DataFrame of the ride-sharing data 
by city type. PyBer CEO want a visualization of the rideshare data on a summary DataFrame
and multiple line graphs showing four months of rideshare data from January to 
April  of 2019 of total weekly fares for each city type. This analysis will help PyBer to improve access
to ride-sharing services. It will also help determine affortability for certain under-served neighborhoods. 
We used Pandas and Matplotlib libraries for the analysis and visualization.

Results:
PyBer_summary_DataFrame:
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing
data among the different city types.
The summary DataFrame shows the total rides, total drivers, total fares, average fare per ride, 
and average fare per driver for each type of city. As shown in the pyber_summary_df (see first link below), 
rural city type has 125 Total rides compared to 625 and 1,625 in suburban and urban respectively.
In the rural city type, there are 78 Total Drivers, compared to 490 and 2405 in the suburban and urban city 
types respectively. This disparity reflected in the average fare per ride in the rural city type being the 
highest at #34.62 compared to #30.97 and $24.53  for suburban and urban respectively. The $55.49 average fare 
per driver in the rural city type also highlights  the disparity when compared to urban city type with average 
fare per driver of $16.57. 

Total Fares by City Type line graphs
Also, the "Total Fares by City Type" line graphs, shows the relationship between total fares and date and the differences 
in weekly total fares from January to April (see second link below).
The highest total fares is seen in the Urban cities with fares ranging from $1,661.68 to $2,470.93 depicted by the yellow 
line. The red line shows that the total fares in suburban cities on weekly bases ranges from $721..60 to $1,412.74 while 
the total fares for the rural cities depicted by the blue line is the lowest ranging from $67.65 to $501.24. The line graph
also shows that the total fares in all city types was at the peak towards the end of February. 


pyber_summary_df = ![PyBer_summary_df.png](https://github.com/FUNMIIB/PyBer_Analysis/blob/main/analysis/PyBer_summary_df.png)
Total Fares by City Type" line graphs = [resample_fig.png](https://github.com/FUNMIIB/PyBer_Analysis/blob/main/analysis/resample_fig.png)


Summary
Bussiness Recommendations
These recommendations are given based on the results of the analysis. 
1. The first recommendation to address the disparities among city types is that the fares in the rural and suburban cities should be decreased to even out the total fares and the average fares per ride. This might help reduce the differences in the total number of rides among the city types.
2. The second recommendation is that more effort should be put into increasing the amount of users in the rural and suburban cities. This could be achieved by different marketing strategies in order to increase the total fares and the total number of rides and reducing the disparity
3. The third recommendation is that they should hire more drivers in the rural and suburban cities to correct the disparity in the total number of drivers and average fare per driver in these city types. 
 


 

