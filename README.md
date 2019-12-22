# PyBer_Analysis
Matplotlib

# Project Overview
Analysis of PyBer in urban, suburban, and rural cities
-	Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for three city types.
-	Determine the mean, median, and mode for the following:
	-	The total number of rides for each city type.
	-	The average fares for each city type.
	-	The total number of drivers for each city type.
-	Create box-and-whisker plots that visualize each of the following to determine if there are any outliers:
	-	The number of rides for each city type.
	-	The fares for each city type.
	-	The number of drivers for each city type.
-	Create a pie chart that visualizes each of the following data for each city type:
	-	The percent of total fares.
	-	The percent of total rides.
	-	The percent of total drivers.
# Resources
-	Data Source: city_data.csv and ride_data.csv
-	Software: Python Python 3.6.9:: Anaconda, Inc., Jupyter Notebook, 6.0.2, Visual Studio Code, 1.40.2. 
# Summary
-	The bubble chart is in the analysis folder.
	-	Illustrates PyBer Ride Sharing Data (2019). City Types are Urban, Suburban and Rural
	-	The chart shows that the PyBer rides are more in demand in urban cities. 
-	Determine the mean, median, and mode for the following.
	-	The total number of rides for each city type.
		-	Urban
			-	The mean for the ride counts for urban trips is 24.62.
			-	The median for the ride counts for urban trips is 24.0.
			-	The mode for the ride counts for urban trips is ModeResult(mode=array([22], dtype=int64), count=array([7])).
		-	Suburban
			-	The mean for the ride counts for suburban trips is 17.36.
			-	The median for the ride counts for suburban trips is 17.0.
			-	The mode for the ride counts for suburban trips is ModeResult(mode=array([17], dtype=int64), count=array([7])).
		-	Rural
			-	The mean for the ride counts for rural trips is 6.94.
			-	The median for the ride counts for rural trips is 6.0.
			-	The mode for the ride counts for rural trips is ModeResult(mode=array([6], count=array([5])).
	-	The average fares for each city type.
		-	Urban
			-	The mean fare price for urban trips is $24.53.
			-	The median fare price for urban trips is $24.64.
			-	The mode fare price for urban trips is ModeResult(mode=array([22.86]), count=array([5])).
		-	Suburban
			-	The mean fare price for suburban trips is $30.97.
			-	The median fare price for suburban trips is $30.75.
			-	The mode fare price for suburban trips is ModeResult(mode=array([17.99]), count=array([3])).
		-	Rural
			-	The mean fare price for rural trips is $34.62.
			-	The median fare price for rural trips is $37.05.
			-	The mode fare price for rural trips is ModeResult(mode=array([37.05]), count=array([2])).
	-	The total number of drivers for each city type.
		-	Urban
			-	The mean for the drivers counts for urban trips is 36.68.
			-	The median for the drivers counts for urban trips is 37.0.
			-	The mode for the drivers counts for urban trips is ModeResult(mode=array([39], dtype=int64), count=array([86])).
		-	Suburban
			-	The mean for the drivers counts for suburban trips is 13.71.
			-	The median for the drivers counts for suburban trips is 16.0.
			-	The mode for the drivers counts for suburban trips is ModeResult(mode=array([20], dtype=int64), count=array([79])).
		-	Rural
			-	The mean for the drivers counts for rural trips is 4.30.
			-	The median for the drivers counts for rural trips is 4.0.
			-	The mode for the drivers counts for rural trips is ModeResult(mode=array([1], dtype=int64), count=array([32])).
-	Create box-and-whisker plots that visualize each of the following to determine if there are any outliers. (The box-and-whisker plots are in analysis folder).
	-	The number of rides for each city type.
		-	The ‘Ride Count Data (2019)’ illustrates that there is one outlier in urban ride counts
			-	West Angela city has the highest rider count.
	-	The fares for each city type.
		-	The ‘Ride Fare Data (2019)’ shows:
			-	rural cities have higher fare price than urban and suburban cities.
			-	urban cities fare price is less than suburban and rural cities.
	-	The number of drivers for each city type.
		-	The ‘Driver Count Data (2019)’ demonstrates that urban cities have more drivers and rural cities do not have many drivers.
-	Create a pie chart that visualizes each of the following data for each city type. (The pie charts are in the analysis folder).
	-	The percent of total fares. The percent of total rides. The percent of total drivers.
		-	The pie charts of total fares, total rides and total drivers illustrate that the percentage of PyBer rides are much higher in Urban cities compared to suburban and rural cities.
# Challenge Overview
-	Create a summary DataFrame that shows following for each city type:
	-	Total Rides
	-	Total Drivers
	-	Total Fares
	-	Average Fare per Ride
	-	Average Fare per Driver
-	Plot the sum of the fares for each city type. 
	-	Use the object-oriented interface method to plot the chart.
# Resources
-	Data Source: city_data.csv and ride_data.csv
-	Software: Python Python 3.6.9:: Anaconda, Inc., Jupyter Notebook, 6.0.2, Visual Studio Code, 1.40.2. 
# Summary
-	Create a summary that shows the total rides, drivers and fares for each city type and average fare per ride and driver.
	-	The PyBer analysis summary shows that there is correlation between the price of fares, the driver counts and the frequency of rides. The urban cities have more revenue, ever though the average fare per ride and per driver is lower than suburban and rural cities. However, urban cities have more rides.
 
|          | Total Rides | Total Drivers | Total Fares | Average Fare per Ride | Average Fare per Driver |
|----------|-------------|---------------|-------------|-----------------------|-------------------------|
| Rural    | 125         | 78            | $4,327.93   | $34.62                | $55.49                  |
| Suburban | 625         | 490           | $19,356.33  | $30.97                | $39.50                  |
| Urban    | 1,625       | 2,405         | $39,854.38  | $24.53                | $16.57                  |

-	Create a line chart of sum of the fares for each city type
	-	The line chart also illustrates that urban cities bring more revenue that suburban and rural cities.
![Total Fare by City Type]( https://github.com/k389/PyBer_Analysis/blob/master/analysis/Fig8.png)
-	Both the chart and the graph show that the PyBer rides are more successful in urban cities. The PyBer rides are less successful in rural cities. Suburban cities bring moderate success. 

