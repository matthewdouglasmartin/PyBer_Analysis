# PyBer_Analysis
Using Matplotlib to create visualizations for analysis
## Overview of the analysis:

Initially the ride-sharing company PyBer, was interested in an analysis of its company data in order to better understand how its riders, drivers, fares, and city types were related.  Analysis was conducted on these metrics and their relationships to each other in an effort to help PyBer imporove two main components of its business model: access and affordability. In addition, the team at PyBer requested a summary of the ride-sharing data by city type and multiple-line graph that shows the total fares for each city type.  This last portion of analysis provided was then used to draw conclusions regarding decisions PyBer can make to positively impact any opportunities from the analysis provided.  

## Results:

In order to conduct analysis on how the ride-sharing data differed based on the city type, a summary DataFrame and multiple-line chart were created from the data provided by PyBer.  The summary DataFrame provides the total rides, total drivers, total fares, average fare per ride, and average fare per driver per city type.  There are three main city types used to organize the data: rural, suburban, and urban.  The multiple-line chart visualizes the total fares per week by city type for four month period in 2019.  These two visualizations should be used in conjunction with each other when performing analysis because each provide additional insight for the data the other provides.  

The PyBer Summary Data Frame hones in on the drastic difference between total fares by city type and the average fare per driver by city type.  

PyBer Summary DataFrame:

![PyBer Summary DataFrame](https://github.com/matthewdouglasmartin/PyBer_Analysis/blob/main/analysis/PyBer_Summary_DF.png)

When comparing the total fares for Rural cities to the total fares of Urban cities, total fares for Urban cities are nine times the total of total fares for Rural cities ($39,854.38 and $4,327.93 respectively).  In addition, the average fare per driver for Rural cities is $55.49 while it is $16.57 for Urban cities.  Suburban cities' total fares are $19,356.33 and their average fare per driver is $39.50, landing between those of Rural and Urban cities.  One main factor that causes the average fare per drive of Urban cities to be so much lower than that of Rural cities is due to Urban cities' total number of drivers.  Urban cities have 1.4 times more drivers than rides, whereas Rural cities have just over half as many drivers as it does rides.  

The multiple-line chart depicts the total fares of each city type over the course of a four month period in the spring of 2019.

PyBer's Total Fare by City Type chart:
![Total Fare by City Type](https://github.com/matthewdouglasmartin/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

Similar to the PyBer Summary DataFrame, the first difference that can be seen is the variance between total fares for each city type.  Within this time frame, Urban cities generate a lot more volume from its fares when compared to Suburban and Rural cities.  For the most part, all city types experience increases and decreases around the same times each month as each other.  Though Urban cities do generate the most volume from fares, they do experience more drastic change in the fares week to week.  This can be seen when specifically looking at Urban cities in the last week of February, where the total fares totaled about $2500.  By the end of the last week of March, the Urban city total fares dropped to a total of about $2000.  The most Rural cities generate in fares over this four month period is about $500.  Suburban cities, unlike Urban and Rural cities, do not have as many sharp changes in volume generated, but instead slowly increase and decreased over time.    

## Summary: 

Based off of this analysis, the largest disparities are seen in the total fares, total rides and total drivers which then impact the average fare per ride and average fare per driver for each city type.  One of the main factors causing the average fare per dirver in Rural cities to be so high is the lack of drivers in the Rural cities.  If PyBer were to implement hiring and recruiting initiatives in Rural cities in an effort to expand its driver presence in rural cities- an increase in drivers for Rural cities would help lower the average fare per driver.  Another option in order to have more drivers available in Rural cities would be for Ubran drivers to pick up more rides in Suburban or Rural cities and Suburban drivers to do the same in Rural or Urban cities.  It would make the most sense for Subruban drivers to be incentivized in this manner due to their likely proximity to other rural cities.  A final suggestion would be to run promotions within Rural and Urban cities to help generate more ride requests to lower the average fare per ride. This would have to be done after the drivers available in these cities increases.  This approach would also help PyBer to further expand its presence outside of Urban cities.  All of these suggestions are viable options to address the differences in the average fare per ride and the average fare per driver between city types.    