# Surf's Up Temperature Analysis

## Purpose
What's better than surf, sun, and ice cream? W. Avy agrees with us that not much is, which is why he's interested in investing in our idea for a 'Surf and Shake' shop on Oahu, providing surf rentals and ice cream snacks. While we're already sold on the idea ourselves, W. Avy prefers his due diligence before investing. Pulling a collection of weather data from around the island, W. Avy has tasked us with a statistical analysis on the temperature data for the months of June and December to ensure the shop will have success. 

## Results

The provided database includes daily weather data collected from 9 substations across the island. Using Python tools, we've pulled the temperature data and run statistical analyses for the months of June and December. The following table presents the analyses -- consisting of the temperature averages, standard deviations, interquartile ranges, mininum values, and maximum values -- with the temperatures in Fahrenheit. 

##### Temperature Statistics for June and December
| Month: | Jun. | Dec. | 
|---|---|---|
| Avg. Temp | 75 | 71 | 
| St. Dev. | 3.3 | 3.7 | 
| IQR | 4.0 | 5.0 |
| Min | 64 | 56 | 
| Max | 85 | 83 | 

There are three overall conclusions we can come to with the above information:
- Average June temperature is about 4 degrees warmer than December.
- Larger standard deviation of December temperatures than June.
- Greater total range of temperatures in December than June.


## Summary and Discussion

Looking at just June and December temperatures leaves lots of holes in understanding weather patterns of Oahu. Primarily, June and December aren't even the warmest and coolest months, respectively, and give only a middling temperature pattern. Indeed, querying all months for temperature readings, we find that the coldest average temperature is about 69 degrees in January and warmest is about 76 degrees in August.   

Including the other months, we start to get a picture of the temperature on Oahu. The temperature is usually in the 70s degrees decade and the variability, measured by the standard deviation, is consistently within 4 degrees, suggesting a comfortable setting for a vacation any time of the year.  

Of course, the temperature isn't the full story; there are other factors that affect the perception of weather. These factors are primarily the amount of precipitation and cloud coverage, but others, such as wind speed, cannot be overlooked either. A 70 degree day with full sun and no breeze will feel much warmer than a 75 degree with no sun (full cloud coverage) and a biting wind gust. Additionally, it's difficult to surf in windy weather or eat ice cream in a downpour; if these are consistent weather patterns on Oahu, a surf and ice cream shop here is not a wise idea. Precipitation amounts, cloud coverage, and wind speed are certainly queries that should be investigated fully before investing in an Oahu surf and ice cream business.
