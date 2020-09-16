# Flights Data Exploration

## Dataset

The dataset used is the Airline On Time Data from the Data Expo 2009, which consists of commercial flights within the US from 1987 up until 2008. Originally, the data is from RITA, where it should also be downloadable. Due to memory issues, not a whole year of data could be loaded. To allow for some comparisons, data for January 2018 and January 2019 are selected. It can be found [here](https://www.transtats.bts.gov/Fields.asp?Table_ID=236).


## Summary of Findings


In the exploration, I found that most flights take place on Wednesdays and the least on Saturdays. At the same time, Wednesday has the least amount of delayed flights, even though it is the day with most cancellations.

Moreover, carrier WN has, by far, operated the most flights in this period. However, they have also cancelled the most flights throughout this period. In general, it is found that the delays definitely vary widely between carriers.

Surprisingly, it is not only that there are quite a few flights which arrive delayed (18%), but also many which arrive earlier (63%).

When it comes to origins and destinations of delayed departure and arrival flights, Chicago, New York, and Atlanta are at the top of the list.

Additionally, I found that most flights take around 70 minutes. The distribution of this variable matches that of flight distance. Moreover, this is proven through a high correlation of 0.981 between the variables.


## Key Insights for Presentation


For the presentation, I focused on the different carriers, the storyline being that it might be interesting (e.g. for investors) to see which carriers have especially good service and management. First, I looked at the carriers that fly most planes. Next, I dived into how many cancellations each of these carriers had. Finally, my focus shifted to their delayed and early aircrafts.



## References

- https://www.transtats.bts.gov/Fields.asp?Table_ID=236
- https://stackoverflow.com/questions/58705843/unable-to-allocate-array-with-shape-1482535-67826-and-data-type-int64
- https://stackoverflow.com/questions/42262563/please-explain-in-detail-2d-histogram-in-python
- https://stackoverflow.com/questions/47104862/pandas-dataframe-plot-colors-by-column-name
- http://seaborn.pydata.org/tutorial/color_palettes.html
- Udacity Example Project - Diamonds Part1
- Udacity Example Project - Diamonds Part2
