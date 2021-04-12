# PyBer_Analysis

## Project Overview

The purpose of this analysis was to analyze all the PyBer rideshare data from January to early May of 2019 and create a compelling visualization for the CEO.

## Results

Urban cities have the highest total number of rides, total number of drivers, and total fares.
Rural cities have the highest average fare price per ride and the highest average fare price per driver.

![summary_data](https://user-images.githubusercontent.com/78178900/114329755-ce1bc400-9b05-11eb-84e7-5b08b6146a7a.png)


### Scatter Plot Visualization

![Number_of_rides_per_city](https://user-images.githubusercontent.com/78178900/114327437-ab39e180-9afe-11eb-9ece-edb301dbdfc0.png)

After analyzing the total number of rides for 2019 among each type of city, Urban cities have the largest number of rides at the highest prices. Suburban cities coming in second, and Rural coming in third. I believe it is notable that the price of rides tends to be higher in the Rural cities but much less frequent from the lower priced Urban city rides that are more frequent.

### Box-and-Whisker Visualization

#### Summary Statistics for Number of Rides by City Type
![Number_of_rides_box-and-whisker](https://user-images.githubusercontent.com/78178900/114327942-bdb51a80-9b00-11eb-9d2f-78dce4b2746c.png)

- West Angela has the highest rider count.
  - #urban_city_outlier = urban_ride_count[urban_ride_count==39].index[0] 
  - #print(f"{urban_city_outlier} has the highest rider count.")

- The mean for the ride counts for urban trips is 24.62.
- The median for the ride counts for urban trips is 24.0.

- The mean for the ride counts for suburban trips is 17.36.
- The median for the ride counts for suburban trips is 17.0.

- The mean for the ride counts for rural trips is 6.94.
- The median for the ride counts for rural trips is 6.0.


#### Summary Statistics for Number of Drivers by City Type
![Number_of_drivers_box-and-whisker](https://user-images.githubusercontent.com/78178900/114327949-c3126500-9b00-11eb-8c58-a44f6885964e.png)

- The mean number of drivers for Urban cities is 37.
- The median number of drivers for Urban cities is 37.

- The mean number of drivers for Suburban cities is 14.
- The median number of drivers for Suburban cities is 16.

- The mean number of drivers for Rural cities is 4.
- The median number of drivers for Rural cities is 4.


#### Summary Statistics for Ride Fare Totals by City Type
![Ride_fare_box-and-whisker](https://user-images.githubusercontent.com/78178900/114327951-c73e8280-9b00-11eb-8acc-6ad3d4764d18.png)

- The mean fare price for urban trips is $24.53.
- The median fare price for urban trips is $24.64.

- The mean fare price for suburban trips is $30.97.
- The median fare price for suburban trips is $30.75.

- The mean fare price for rural trips is $34.62.
- The median fare price for rural trips is $37.05.


### Pie Chart Visualization

#### Total Rides by City
![Ride_by_city_piechart](https://user-images.githubusercontent.com/78178900/114327972-d8878f00-9b00-11eb-8d07-267f16bb5327.png)


#### Total Drivers by City
![Drivers_by_city_piechart](https://user-images.githubusercontent.com/78178900/114327977-dde4d980-9b00-11eb-8a50-3cd4a869c74c.png)


#### Total Fares by City
![Fare_by_city_piechart](https://user-images.githubusercontent.com/78178900/114327984-e0dfca00-9b00-11eb-8190-48acd33a2a37.png)


## Summary

Since Urban areas have much more nightlife and available activities to partake in, that could be an indication of why the Urban cities have a much higher volume in every section: given the data that indicates a much higher demand for Urban cities, I would advise the consideration of increasing fare prices for those types of cities. More analysis may be needed on consumer behavior for a better indication of how much to raise the price; nevertheless, I believe it is worth a discussion.

On the other hand, rural areas may not have as many rides because of two possible reasons: there are not enough drivers OR the prices are too high. With this information I believe it would be in the company's best interest to conduct A and B testing by choosing two groups of rural cities and increase the drivers for one without manipulating the price and increase the price without manipulating the drivers for the other. This can give much better insight into whether these issues will solve the disparity between fare prices and drivers between Rural and Urban cities. 

Furthermore, we should investigate what happens during the last week of February that causes a peak in fare price by each city type. Whatever is happening that week is causing people to use the ride share service more so, I recommend an increase on advertising and marketing for the month of February via social media and major television networks. The increase in activity for that week can be increased even more by advertising to our target market. I believe it is also worth considering the advertisement of promotional deals for the month of January. This way, it will increase our target market activity and give people time to get acquainted with the brand and develop a loyalty to it, then when the peak in February comes there may be a larger population that uses the ride share service. 

![summary_fare_by_city](https://user-images.githubusercontent.com/78178900/114329990-54d0a100-9b06-11eb-9875-53c9e4ab8ae0.png)
