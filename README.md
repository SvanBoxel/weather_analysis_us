### U.S. weather history visualization

The raw data and code behind the story [What 12 Months Of Record-Setting Temperatures Looks Like Across The U.S.](http://fivethirtyeight.com/features/what-12-months-of-record-setting-temperatures-looks-like-across-the-u-s/)

#### Code

Code file | Description
---|---------
`wunderground_scraper.py` | Downloades weather data web pages from Weather Underground
`wunderground_parser.py` | Parses the weather data from Weather Underground into a flat CSV file
`visualize_weather.py` | Creates the visualization of the weather data

#### Data

Column | Description
---|---------
`date` | The date of the weather record, formatted YYYY-M-D
`actual_mean_temp` | The measured average temperature for that day
`actual_min_temp` | The measured minimum temperature for that day
`actual_max_temp` | The measured maximum temperature for that day
`average_min_temp` | The average minimum temperature on that day since 1880
`average_max_temp` | The average maximum temperature on that day since 1880
`record_min_temp` | The lowest ever temperature on that day since 1880
`record_max_temp` | The highest ever temperature on that day since 1880
`record_min_temp_year` | The year that the lowest ever temperature occurred
`record_max_temp_year` | The year that the highest ever temperature occurred
`actual_precipitation` | The measured amount of rain or snow for that day
`average_precipitation` | The average amount of rain or snow on that day since 1880
`record_precipitation` | The highest amount of rain or snow on that day since 1880

Source: [Weather Underground](http://wunderground.com)

#### Steps for this workshop
**Person A**  
```
1. Visit this repository. (You're here, great job!)  
2. Fork this repository (button top right)   
3. Add your team member (Settings -> Collaborators)   
```

**Person B**  
```
4. Accept invitation
5. Open `visualize_weather.py`
6. Update line 13 (`KPHL` -> `KHOU`)
7. Update line 113 (`Philadelphia, PA\’s` -> `Houston, TX\’s`)
8. Create commit on a new branch
9. Submit pull request and assign your colleague
```

**Person A**  
```
10. Go to pull request and leave a suggestion
11. Request changes and submit review
```

**Person B**  
```
12. Accept suggestion (You can say thank you)  
```

**Person A**
```
13. Approve Pull Request
```

**Person A or B**
```
14. Merge Pull request
```



