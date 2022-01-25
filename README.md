## PyBer Ride Analysis
Challenge 5 for Butler Data Science

## 1. Overview of Ride Analysis
### 
* The goal of this module is to a ride sharing company with their analysis of user, driver, and fare data. We have broken our analysis into city type (rural, suburban, and urban) to group like users together.

## 2. Results
### 
* Analysis of total rides
	- As expected the most rides occur where there are the most people -- in urban areas. Second is suburban and last is rural. This analysis confirms that the higher the population of an area, the more rides there will be.

	  - Total Rides

![Total Rides](https://github.com/coxjack/MatPlotLibChallenge5/blob/main/additional%20supporting%20images/total_rides.png)

* Analysis of total drivers
	- Similarly to the analysis of rides this data meets what you would expect. Where the population is the highest there is also the most drivers. Second is suburban and last is rural just like the total rides data.

	  - Total Drivers

![Total Drivers](https://github.com/coxjack/MatPlotLibChallenge5/blob/main/additional%20supporting%20images/total_drivers.png)

* Analysis of total fares
	- In line with the analysis of total rides and total drivers, total fares follows the same pattern. Where there are the most people there are the most rides and the most money spent on ride fares. Second is suburban and last is rural just like the total rides and total drivers data.

	  - Total Fares

![Total Fares](https://github.com/coxjack/MatPlotLibChallenge5/blob/main/additional%20supporting%20images/total_fares.png)

* Analysis of average fare per ride
	- Here is where the analysis flips -- since there are less rides in rural areas it has the highest average fare per ride. Second is suburban and last is urban, this is the inverse of the total rides, total drivers, and total fares data.

	  - Average Fare per Ride

![Average Fare per Ride](https://github.com/coxjack/MatPlotLibChallenge5/blob/main/additional%20supporting%20images/avg_fare_per_ride.png)

* Analysis of average fare per driver
	- This analysis echoes the previous analysis of average fare per ride -- since there are less drivers in rural areas it has the highest average fare per driver. Second is suburban and last is urban, just like the average fare per ride data.

	  - Average Fare per Driver

![Average Fare per Driver](https://github.com/coxjack/MatPlotLibChallenge5/blob/main/additional%20supporting%20images/avg_fare_per_driver.png)
	
	 
* Summary DataFrame
	- The above analysis is summarized in the DataFrame below. Urban areas lead in total categories while rural areas lead in the average categories.

	  - Summary DataFrame

![Summary DataFrame](https://github.com/coxjack/MatPlotLibChallenge5/blob/main/additional%20supporting%20images/summary_df.png)
	
* Total Fare by City Type
	- To graph a piece of this analysis we took a look at a sample time frame (from Jan 2019 - April 2019) and totaled the fares by each city type. The month over month chart confirms our findings from the DataFrames above and shows urban cities have the most fares, suburban the second most, and rural the least.

	  - Total Fare by City Type Chart

![Total Fare by City Type Chart](https://github.com/coxjack/MatPlotLibChallenge5/blob/main/additional%20supporting%20images/total_fare_by_city_type_chart.png)
	
## 3. PyBer Ride Summary
### 
* The business recommendations based on this data are the following:
	- Advertise to potential drivers in rural and suburban areas, while there is not the robust demand as there is in urban areas there is still these areas are still in need of more drivers. In both of these areas there are more rides than there are drivers.
	- Incentivize some urban drivers to work in nearby rural and suburban areas, this would increase the amount of money they could make as well as increasing the average fare per ride in the urban areas.
	- When expanding always focus on urban areas first -- this where the most rides and drivers will be and thus will create the most profit for the business.



