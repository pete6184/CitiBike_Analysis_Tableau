# Citi Bike Analytics

## Requirements
- The data set for this analysis came from a .csv file downloaded from https://s3.amazonaws.com/tripdata/index.html
- Next, the data was loaded into a dataframe in Jupyter Notebook and cleaned using pandas
- Lastly, the data was loaded into Tableau Public where I created the graphs

- To view project visit Tableau Public Link 

https://public.tableau.com/profile/pete.johnson3008#!/

## Background

![Citi-Bikes](Images/citi-bike-station-bikes.jpg)

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have several questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

# Analysis

## Observation 1
There is a significant disparity in the gender of riders. As you can see in the charts the number of riders that have identified as male is almost 3x as many as riders who identify as female. Even more significant are the users that did not select a gender. 

![user_types](https://user-images.githubusercontent.com/74940976/118342538-91623480-b4d8-11eb-8a7a-f190bebab329.PNG)

![riders_per_day](https://user-images.githubusercontent.com/74940976/118342549-9d4df680-b4d8-11eb-9582-02cf25c4f003.PNG)

As you can see from the illustrations above, there has been a sharp decline in riders listed as 'male' or 'female' and subsequent increase in riders listed as 'unknown' since the end of January 2021. This could be due to a couple possible factors:

1. A significant number of riders are tourists and only use the app/bikes when in NYC and they are typically only in the city for a few days. This would lead to users not filling in all the information when signing up for the app and therefore leading to an 'unknown' gender type.

2. CitiBike's app has gender identifying options other than the male or female pronouns and even an option that allows users to not disclose this information at all. This would certainly lead to the trends we are seeing in the graphs.



## Observation 2
There is much heavier use in Manhattan than in other parts of the city. This caught me by surprise because Manhattan is arguably the most walkable part of NYC and one of the most heavily trafficked areas. I would think that walking and using the subway system would be a much more popular way of getting around Manhattan and that the surrounding boroughs would have more use.

![startStation_map](https://user-images.githubusercontent.com/74940976/118343142-01be8500-b4dc-11eb-87e2-b3747340f30a.PNG)


Another usage trend that I was not expecting was the busiest station's peak start time was not rush hour, but 9pm. This could be due to people not wanting to walk through the city at that hour or people simply taking evening joyrides around Manhattan in the evenings.

![top10_starting](https://user-images.githubusercontent.com/74940976/118343146-0a16c000-b4dc-11eb-8b84-273a5349d79d.PNG)


![busiest_station](https://user-images.githubusercontent.com/74940976/118343155-1438be80-b4dc-11eb-9262-b82f6189f7bf.PNG)

![top_startTimes](https://user-images.githubusercontent.com/74940976/118343158-1733af00-b4dc-11eb-89ee-1eeb3736c51b.PNG)

