# PyBer_Analysis

## Resources
- Data Sources: city_data.csv, ride_data.csv
- Software: Python 3.7.6, Jupyter Notebook 6.4.5
- Libraries: Pandas, Matplotlib

## Project Overview
PyBer - a Python-based ride-share app company - is looking to better understand rider access based on location.
Of key interest to the CEO, V. Isualize, is the relationship among:
* Type of city (urban, suburban, rural).
* Numbers of riders and drivers.
* Percentages of total fares, riders and drivers by city type.

Summary statistics are highlighted by the use of visual aids that include bubble charts, bar charts, box-n-whisker plots and pie charts.
With furnished code and assistance from manager Omar and co-worker Sasha, providing V. Isualize with the necessary information was a piece of cake (and a possible alternative to pie).

Initial work included importing two separate csv files of rider and driver data, which were then converted to data frames, inspected and merged.
From the data present, the calculated number of rides per city and average fares per city were converted into a bubble chart that better demonstrated the larger number of rides and fares occurring in urban areas.
Differences in ride count, driver count and fare spread by location was easier to see in combined box-and-whisker plots. Finally, pie charts detailed how driver, ride and fare percentages varied by urban, suburban and rural settings.

![ALT Text](https://user-images.githubusercontent.com/30667001/150445805-55b23053-ef0b-4805-b074-78c326ae4445.png)

## A Brand New Assignment (Challenge)
V. Isualize - impressed with these findings - requested Pandas be further employed to:
* A. Summarize ride sharing by city type.
* B. Create a multiple-line graph that showed total weekly fares for each city type.

Data were once again loaded, converted and merged, then grouped by type (urban, suburban, rural) to produce the summary data frame and formatted accordingly.

![ALT Text](https://user-images.githubusercontent.com/30667001/150442601-73802679-be48-4a9c-8ca3-0f493ed4a0d2.png)

Data were limited (per CEO request) to the first four months of the year and further manipulated to create a pivot table that allowed the data to be aggregated by week.
From this, the resulting line graph was produced.

![ALT Text](https://user-images.githubusercontent.com/30667001/150442582-7d7a1863-71af-4f8a-96ae-53cd5d620304.png)

# ADD - There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)

## Summary

# ADD - There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)
