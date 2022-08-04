# Surfs-Up
After wanting to open a surf shop that also sells ice cream year round in Hawaii, I find an investor, W. Avy who will help me open this shop. His main concern is the weather. In his previous investment at a surf shop, the business was rained out so he does not want to make the same mistake again. Since I have been learning to to analyize data, W. Avy asks to run some analysis on the weather data that he has saved regarding the island we will open the surf shop at. 

In this analysis, I will be using Python in VS Code and importing dependencies such as Pandas, Numpy, and SQLAlchemy with Session. 

## Overview 
After some weather analysis, W. Avy is sure about my skills, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results
There are some key differences in weather in the month of June and December. I have attached a quick summary statistics for both these months below. 

### June Temperature Statistics vs. December Temperature Statistics
![June_temps](https://user-images.githubusercontent.com/105755095/182946442-545d7127-76b9-404a-bdc5-f557b27f4552.png)
![December_temps](https://user-images.githubusercontent.com/105755095/182946460-521cf78f-4092-4313-a98a-0f417a73b49e.png)

- The average temperature for for each month differentiates about 4 degrees. 
    - June has an average temperature of 74.9 while December's average temperature is 71 degrees Fahrenheit. 
- Both months' average temperatures are very close if not the same to the mean temperature for each month. We can make the conclusion that the temperature does not frequently go out from this range and that there are no outliars of weather points skewing the data.
    - Due to this, it is safe to assume that the temperature does not go through extremes in these two months.
- The minimum temperature in June is 64 degrees while in December it is 56 degrees Fahrenheit. That is a large difference of 8 points. 
    - These temperatures may be too low for some surfers to go surfing at this time, however, the ice cream business would still be a success as it is not too cold. 

## Summary
The temperatures of the peak summer month and peak winter month of the year in Hawaii shares that it stays warm almost all year round. The temperatures barely dip from the summer to winter which is promising for the business. The ice cream portion of the business would stay open all year round as it stays warm even in December at a nice 71 degrees. After some research, the average temperatures that most beginner surfers go surfing stays around 62-78 degrees which encompasses most of the year in Hawaii. However, more advanced surfers are able to go in the watter at temperatures even as low as 50 degrees and with Hawaii being a popular surf spot where many grew up surfing, it is safe to assume that we will still have customers coming in the winter months for surf gear as well. It would be wise to open a surfing/ice cream shop here as all the data points to a viable environment for this business to thrive. 

I did want to look at some additonal queries to ensure the other data points positvely towards this venture. Starting off with percipitation data in the area.

### Query 1: Percipitation in June and December
![June_Prcp](https://user-images.githubusercontent.com/105755095/182952042-5ee1bfe2-bb3f-4881-af83-d273241020ea.png)
![December_Prcp](https://user-images.githubusercontent.com/105755095/182952053-4d3dd77e-c8bc-4825-b1d7-ade5ff8cdd91.png)

From these statistics we can see that the average amount of rain is close to 0 during both months which is promosing. The medians for both months are also close to 0 which lets us infer that there are not many outliars of extreme data skewing this summary. Even at the 75% marker, both months have less than .2 in of rain. The max rain is at 4 and 6 in. for June and December respectively, but because the other data points of averages and standard deviation is so low, these high points are most likely just extreme weather chances which occur naturally. From the precipitation data, this business venture still seems promising. 

### Query 2: Charts of Percipitation and Temperature
To better visualize and help the board understand the temperatures and percipitation more clearly for the months of June and December, I have created histogram charts of the data points as seen below. 

#### June Data vs. December Data
![June_graphs](https://user-images.githubusercontent.com/105755095/182955710-eb3c71fa-adc8-412e-86d0-699419e37f7f.png)
![December_graphs](https://user-images.githubusercontent.com/105755095/182955712-cb06b418-c793-4a52-9a8b-13b1ba47662d.png)

From these graphs we can see something very promising. The percipitation data, just as we had assumed from the summary statistics, is largely at the 0 in. of rain. This is great news for the business as fewer rainy days in these months. However, after some research regarding the seasons of Hawaii, the wettest months are actually November through March. Because of this information, I went ahead and made visualizattions of the perceipitation for those two months and below are the results. 

![Nov_rain](https://user-images.githubusercontent.com/105755095/182956744-7cdfb7e5-720c-4208-aaa4-f19a0957aeac.png)
![March_rain](https://user-images.githubusercontent.com/105755095/182956758-786018bf-5239-4e5e-bcd1-6db88cd26464.png)

And we are met with good news again! For most days of either of those months, there is 0 in of rain. The business venture from all the information we found seems to all point towards this venture being a success!
