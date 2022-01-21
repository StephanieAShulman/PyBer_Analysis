# PyBer_Analysis

### Resources
- Data Sources: city_data.csv, ride_data.csv
- Software: Python 3.7.6, Jupyter Notebook 6.4.5
- Libraries: Pandas, Matplotlib

### Project Overview
PyBer - a Python-based ride-share app company - is looking to better understand rider access based on location in order to address disparities among city types.
Of key interest to the CEO, V. Isualize, is the relationship among:
* Type of city (urban, suburban, rural).
* Numbers of riders and drivers.
* Percentages of total fares, riders and drivers by city type.

Using furnished code, summary statistics were highlighted with the use of visual aids that include bubble charts, bar charts, box-n-whisker plots and pie charts.

Initial work included importing two separate csv files of rider and driver data, which were then converted to data frames, inspected and merged.
From the data present, the calculated number of rides per city and average fares per city were converted into a bubble chart that better demonstrated the larger number of rides and fares occurring in urban areas.
Differences in ride count, driver count and fare spread by location was easier to see in combined box-and-whisker plots. Finally, pie charts detailed how driver, ride and fare percentages varied by urban, suburban and rural settings.

Examples include:
   ![ALT Text](https://user-images.githubusercontent.com/30667001/150445805-55b23053-ef0b-4805-b074-78c326ae4445.png)

### New Assignment (Challenge)
V. Isualize - impressed with these findings - requested Pandas be further employed to:
* A. Summarize ride sharing by city type.
* B. Create a multiple-line graph that showed total weekly fares for each city type.

Data were once again loaded, converted and merged, then grouped by type (urban, suburban, rural) to produce the summary data frame and formatted accordingly.

   ![ALT Text](https://user-images.githubusercontent.com/30667001/150442601-73802679-be48-4a9c-8ca3-0f493ed4a0d2.png)

Almost 70% of all rides originated in urban areas, source of 81% of the drivers and 63% of total fares. In suburban and rural areas, the lower number of ridership and driver count contributed to an average fare of the combined areas ($33) that was almost one-third greater (32%) for riders in these areas than those in urban areas. Urban drivers made 135% and 224% less than suburban and rural drivers, respectively.

Data were limited (per CEO request) to the first four months of the year and further manipulated to create a pivot table that allowed the data to be aggregated by week.
From this, the resulting line graph was produced.

   ![ALT Text](https://user-images.githubusercontent.com/30667001/150442582-7d7a1863-71af-4f8a-96ae-53cd5d620304.png)

Almost all areas show a similar fare patterns over the four months, peaking in late February, then rising and falling in somewhat similar patterns for the remaing weeks. Fares  vary greatest for urban riders between March and April. The first week of April, urban and rural fares increase while suburban fares fall and continue to move in an opposite pattern.

### Summary
Next steps should include a review of the following:
* Time-to-destination - Despite greater number of riders in urban areas, travel time may be affected by surrounding traffic.
* Distance driven - For rural areas, distance traveled may be a factor in the increased fares in rural areas, despite more time spent in traffic by urban riders completing short trips.
* Ride timing - Is there something about ridership at certain times that contributes to increased usage in areas (eg: urban nightlife versus rural medical use).
A high-level summary of typical destinations may also yield further insight.

With these additional pieces of information, PyBer can better assess the relationship among riders, drivers, and fares, improving understanding of the root causes of disparities among different city types.
