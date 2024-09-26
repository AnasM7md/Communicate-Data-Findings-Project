# Data Visualization - Ford GoBike 2019

## About the dataset
The dataset 2019-fordgobike-tripdata is downloaded from Udacity and licensed by Ford GoBike. This dataset includes 183,412 trips with 16 features such as duration_sec (time of take the bike in seconds), start_time and end, and type of user and its gender, there are also id for the bike, stations, and finally wethear the bike shared durnig the trip or not .

## Summary of data wrangling process that performed
- The null velue have been removed
- The start_time & end_time have been converted into datetime, they were 'object' as we see above
- The start_time & end_time have been splited into date_start, time_start, date_end, and time_end to make the structre better
- The start_time & end_time columns have been revomed after perform the split step
- The columns start_station_longitude and end_station_longitude values converted into + values
- The outliers have been dealt with

## Univariate analysis
- For the histogram chart I asked, Which is the peak that most of the customer use the bike in second? and what kind of the distrubition? To answer that I had to create the plot and it turns out that, as it clear that the histogram is RIGHT SKEWED distribution, the plots clarify that the most of the users their peak of using the bike is between 300 to 350 seconds approximatly
- For the bar chart I asked about the top 10 stations that have trips While part of the anser is two of them were Market St at 10th St, and San Francisco Caltrain Station 2 (Townsend St at 4th St)

## Bivariate analysis
- For the scatter plot, I asked based on the user birth year, Which is the generation that used the bike most? They were bewteen 1950s and 2000s
- For the box plot, Which the users whose used the bike long time? Particapiate or not? They are who NOT participate
- For the heat map, Usually, Which is the highest path for (start to take and submit) the bike? They starting from Berry St at 4th St, and submit their bike in San Francisco Ferry Building (Harry Bridges Plaza)

## Multivariate analysis
- For the facet plot, Who is the highest propotion in the latitude, The answer based on the plot is The male users who subscribe in the program seems to be the highest proption of the latitude
- For the matrix plot(Pair plot), How do user types (Customers vs Subscribers) differ in their trip duration, starting latitude, and starting longitude based on the pair plot? And it shows that customers tend to have longer trip durations, while subscribers typically take shorter!
