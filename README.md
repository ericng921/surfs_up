# surfs_up
## Overview of the analysis

In the previous module we had used Python, SQLAlchemy, Object Relational Mapper, and Flask to analyze and visualize the climate data on browser.

The purpose of the challenge is to analyze the temperature trend in Oahu, Hawaii. W. Avy wants to know the difference between the June Temperature and December temperature in Oahu so that she can have a better idea before opening her year-round surf and ice cream shop business.

## Resources

- Data Source: hawaii.sqlite

- Program codes Files: SurfsUp_Challenge.ipynb, climate_analysis.ipynb

- Data tools and libary: SQLAlchemy, numpy, panda, matplotlib    

- Application: Python 3.9.7, Jupyter Notebook 6.4.5

## Results

![temp_stats](https://user-images.githubusercontent.com/100378319/165632296-9ea7195a-d951-484a-a0a8-f557ad82bf4b.png)

![june_temp](https://user-images.githubusercontent.com/100378319/165632325-6fbaf9cf-3b59-4c12-870e-be83576dc329.png)

![dec_temp](https://user-images.githubusercontent.com/100378319/165632330-19714e90-a10b-4405-8d85-6465047b3522.png)

There are some key differences in weather between June and December:

- One of the differences is the temperature in December of range of 71 to 73 degrees F occurs most frequently in the plot, the curves look more vary than June; however, for the June temperature it is normal distributed in range 70 to 80 degrees F.  

- For this 7 years data, somehow the count of June and December are 183 (1700-1517) days different. It maybe missing a year of December data or some information are missing.

- The standard deviation of December is higher than June. it's a 0.488 different. That means the data of December is more spread out from the mean.

- The temperature in June is apparently higher than December. The minimum temperature in June is 64 degrees F but the minimum temperature in December is 56 only.


## Summary

For a ice-cream shop one of the most concerns is the temperature in December gets too cold or snowy that would result in lower revenue, however according to the stats, the average December Temperature is only about 4 degrees F lower than average June Temperature. It is expected to have a sustainable year-round ice-cream shop in Oahu.

There are three additional queries to perform to gather more weather data:

1. We can perform another query for precipitation during both June and December because it is also an important factor for choosing a location and see if the shop requires more roof to avoid heavy rain.

2. We can also review another important factor which is the wind condition at the beach. The windy area can affect the traffic of the location and also cause a high wave swell that people wouldn't want to stay at the area.

3. We can have another data on demography of the location. For example, we can get the age group and income group of the area, then we can have a deeper analysis on the location, however it will increase our project budget by doing another larger survey and research.


