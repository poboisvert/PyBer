# PyBer Project Overview

The goal of this project was to give insights on a dataset by aggregating ride-sharing data and production charts on the total weekly fares for each city to determine affordability and underserved area.

## Overview & results of the analysis

The figures and tables are based on a bataset that include 66 urbans cities, 18 rurals cities and 36 Suburbans cities with all the drivers and fare recorded for each area.

### Table 1: ride-sharing by city area

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/table.png?raw=true" width="750" />

The table 1 present the tree cities at a high level. The urban region seems to be the most popular for the driver which would make sense because this is the most densified. By having the highest drivers, it generates also the highest rides count. The major downside of working in the most densified area would be the average salary is the lowest since each trip are shorter.

The highlight of this analysis if the urban has 1,625 rides and the suburbans has 490 which is 30% of the urban area, but the average fare (suburban area) per ride is $30.97 and the average fare per driver is $39.50. This could mean that some cities would require more drivers in order to meet the demande for some cities in the suburban area.

## Ride analysis

### Figure 1: ride-sharing by city area

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/Fig1.png?raw=true" width="450" />

The figue 1 present the total ride by city for the three regions. We can conclude that some suburban and urban region have the same activities in rides, but the suburban regions are more lucrative. This would be logical because the trip are longer for the suburban area and the people are usually older and can afford longer trip.

### Figure 2: Total Ride for each region

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/Fig2.png?raw=true" width="450" />

The figure 2 present an aggregation of all the "ride_id" for each region. This present the urban regions with a wild deviation and a data (39) above our chart. This figure concluse again the popularity of this service for the urban region (the size of each buble is the aggration of all the rides completed), but it also confirm that some cities are not using this service as it should be.

## Price analysis

### Figure 3: Price rides

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/Fig3.png?raw=true" width="450" />

The figure 3 show again the overlap between the rural and suburban with similar pricing. The urban has a median of 24 with a standard deviation of 5.4 and the suburan area has a median of 17 with a standard deviation of 4.3. This could be possible meaning that the people use this service to travel between these 2 areas.

### Figure 4: Timeline of price evolution

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png?raw=true" width="450" />

In order to asses the market activity, the figure show the price evolution from 2019-01-01 to 2019-04-28 for the three regions. The information that we can conclude that the totalfares by city seems to be steady without drastic increase.

## Total drivers

### Figure 5: Total Drivers

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/Fig4.png?raw=true" width="450" />

The urban has 1,625 rides and the suburbans has 490 which is 30% of the urban area, but the average fare (suburban area) per ride is $30.97 and the average fare per driver is $39.50. This could mean that some cities would require more drivers in order to meet the demande for some cities in the suburban area.

### Figure 6: Total Drivers

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/Fig6.png" width="450" />

The figure 6 present the total count of all the "ride_id" against the total ride count. With the figure 5, we can conclude that the suburban with a median of 16 drivers and 37 median, the suburban is 50% of drivers present a higher fare with a small market shares.

## Recommendations

- The total fares evolution seems to be steady. From an external view, the ride-sharing is popular and we would expect a steady increase for the total fares.
- Hire drivers for the suburbans area and since the price is similar with the urban area, the driver could mix between the areas when possible.
- Rural cities present a wild standard deviation. It could be possible that some rural are not fully aware of this service or the price in some cities are simply to expense for the customers.
