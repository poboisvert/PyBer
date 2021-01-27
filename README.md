# PyBer Project Overview

The goal of this project was to give insights on a dataset aggregating ride-sharing data and production charts on the total weekly fares for each city type.

# Overview & results of the analysis

The figures and tables are based on a bataset that include 66 urbans cities, 18 rurals cities and 36 Suburbans cities with all the drivers and fare recorded for each area.

## Ride analysis

## Table 1: ride-sharing by city area

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/table.png?raw=true" width="650" />

The table 1 present the tree cities at a high level. The urban region seems to be the most popular for the driver which would make sense because this is the most densified. By having the highest drivers, it generates also the highest rides count. The major downside of working in the most densified area would be the average salary is the lowest since each trip are shorter.

### Figure 2: ride-sharing by city area

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/Fig1.png?raw=true" width="450" />

The figue 2 present the total ride by city for the three regions. We can conclude that some suburban and urban region have the same activities in rides, but the suburban regions are more lucrative. This would be logical because the trip are longer for the suburban area and the people are usually older and can afford longer trip.

### Figure 3: Total Ride for each region

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/Fig2.png?raw=true" width="450" />

The figure 3 present an aggregation of all the "ride_id" for each region. This present the urban regions with a wild deviation and a data (39) above our chart. This figure concluse again the popularity of this service for the urban region, but it was confirm that some cities are not using this service as it should be.

## Price analysis

### Figure 4: Price rides

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/Fig3.png?raw=true" width="450" />

The figure 4 show again the overlap between the rural and suburban with similar pricing. The urban has a median of 24 with a standard deviation of 5.4 and the suburan area has a median of 17 with a standard deviation of 4.3. This could be possible meaning that the people use this service to travel between these 2 areas.

### Figure 5: Timeline of price evolution

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png?raw=true" width="450" />

In order to asses the market activity, the figure show the price evolution from 2019-01-01 to 2019-04-28 for the three regions.

### Figure 3: Total Drivers

<img src="https://github.com/poboisvert/PyBer_Analysis/blob/main/analysis/Fig4.png?raw=true" width="450" />

### Recommendations

- The total fares evolution seems to be steady. From an external view, the ride-sharing is popular and we would expect a steady increase for total fares.
- Urban doing Suburban trips if possible when the the drivers are able to be near the Suburban area and reduce the wild deviation for the urban area.
- Rural cities present a wild standard deviation. It could be possible that some rural are not fully aware of this service or simple against it.
