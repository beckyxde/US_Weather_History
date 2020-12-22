# US Weather History

This dataset contains the data behind the story: [What 12 Months of Record-Setting Temperatures Looks Like Across the US](https://fivethirtyeight.com/features/what-12-months-of-record-setting-temperatures-looks-like-across-the-u-s/)

### Each file corresponds to US city ICAO airport codes.

| Code | City         |
| ---- | ------------ |
| KCQT | Los Angeles  |
| KCLT | Charlotte    |
| KHOU | Houston      |
| KIND | Indianapolis |
| KJAX | Jacksonville |
| KMDW | Chicago      |
| KNYC | New York     |
| KPHL | Philadelphia |
| KPHX | Phoenix      |
| KSEA | Seattle      |

### Code file Description

visualize_weather.py - Creates the visualization of the weather data

### Data

| Column                | Description                                               |
| --------------------- | --------------------------------------------------------- |
| date                  | The date of the weather record, formatted YYYY-M-D        |
| actual_mean_temp      | The measured average temperature for that day             |
| actual_min_temp       | The measured minimum temperature for that day             |
| actual_max_temp       | The measured maximum temperature for that day             |
| average_min_temp      | The average minimum temperature on that day since 1880    |
| average_max_temp      | The average maximum temperature on that day since 1880    |
| record_min_temp       | The lowest ever temperature on that day since 1880        |
| record_max_temp       | The highest ever temperature on that day since 1880       |
| record_min_temp_year  | The year that the lowest ever temperature occurred        |
| record_max_temp_year  | The year that the highest ever temperature occurred       |
| actual_precipitation  | The measured amount of rain or snow for that day          |
| average_precipitation | The average amount of rain or snow on that day since 1880 |
| record_precipitation  | The highest amount of rain or snow on that day since 1880 |

##### Sources:

[Weather Underground](https://www.wunderground.com/)

[US-Weather_History](https://github.com/fivethirtyeight/data/tree/master/us-weather-history)

##### License:

The data is available under the Creative Commons Attribution 4.0 International License and the code is available under the MIT License. If you find it useful, please let us know.

###### Additional:

wunderground_scraper.py - Downloads weather data web pages from Weather Underground
wunderground_parser.py - Parses the weather data from Weather Underground into a flat CSV file
