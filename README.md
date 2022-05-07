# PyBer_Analysis

## Overview of the analysis
  The questions we are looking to answer include analyzing the data and differences grouped around city type: Rural vs Suburban vs. Urban. Using Matplotlib, Python, Jupyter Notebook, I am able show in different ways what is occuring in the rideshare forum and some business ideas based on these findings.  
  
## Purpose:
  Creating visualizations of rideshare data for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighborhoods; specifically create a multiple-line graph that shows weekly fares for each city type.

## Results:
  As the results show (Figure 1), the lowest total rides, driver count belong to the Rural area, Suburban is next at five times as many as Rural, and Urban is leading with the most at 1625 total rides (2.5 times the amount of rides in the Suburban areas).  Results logically follow that with less total rides and fewer drivers, Total Fares are in the same order with Rural rides at the bottom of total fares, Suburban fares are four and a half times more what the Rural totals; Urban fare totals leading at $39,854.38 which is 2 times the Suburban fare totals.  The final numbers are also explained by these trends: because there are fewer Rural drivers and rides, the average fare per ride as well as the fare per driver are highest.  Both the averages of ride per fare and fare per driver are highest in the Rural areas, followed by Suburban, and finally Urban.  The Urban fares per driver are 2.5 times lower than the Suburban ones, and 3.3 times lower than Rural fares per driver.

![Total Ride Summary](https://user-images.githubusercontent.com/102183530/167273043-bcd9a490-7059-4620-9c81-63225bebff57.png)

###### Figure 1. PyBer summary of total rides, fares, and average fare per ride and drivers.

  The total fare by city type in $USD are graphed for the first part of the year in 2019.  This graph below (Figure2) summarizes the results reported above.  With Urban (green) having the most total rides and highest aggregater fares, followed by Suburban (orange), and the lowest number of rides therefore smalled monetary summation of fares at the Rural level. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/102183530/167272978-01b22d77-1de1-4da6-bf93-a3a18f74e752.png)


## Summary:

### Based on these results there are a number of items that could be addressed with different outcomes in mind.

### Addressing ride availability in Rural areas:   
- Coupons : Ride coupons to help with affordablity could be utilized.
- Driver Pay : Increasing Rural driver pay to encourage more drivers, could encourage more riders as the availability would be higher.  If there are more cars/drivers available people who had to count on this type of service could increase.
- Maximum Charge based on a maximum radius :  Look into the route lengths to see if this is where the charge increases are coming into play.  If this is part of the larger fares, consider a flat fee after X amount of miles.  Or a radius included in a smaller flat fee closer to a smaller population center or road grouping.  While this would take further data needs, it could be worth knowing more about these data points.

### Opportunity in Suburban and Urban areas:
- Cost Increase : Consider pulling data from competitors, specifically to see the charge per mile based on these locations. Is there room to slightly increase per mile or simply add a $2-3 gas fee or similar.  This would help align the fare per driver rates and fare averages with the Rural averages; increasing overall income for the entire brand.
- Driver Pay : Similarly, cap driver pay in Suburban and Urban, letting tips help support the pay.  This could drive down the availability of drivers, thus increasing a fare fee due to capacity limitations.  People might opt to pay a higher rate for a guaranteed time, or increasing a "wait time" for Urban drivers to increase fares to better align with Rural and Suburban rates.

### Data Limitations
- While there was a vast amount of data used to analyze with these results; they could still be skewed.  Depending on the location of the city, we are only looking at winter/early spring.  Is it more difficult to get to Rural areas due to weather caused road issues?  What does the rest of the year look like, do these trends hold up?  Is 2019 an anomoly year?  This company is new, what does marketing look like in Urban areas vs Rural?
