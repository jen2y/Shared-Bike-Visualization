# Explore the User Habbits for Shared Bike in San Francisco
## by Mingshu Li


## Dataset

Bike-share has becoming increasingly popular for citizens and tourists in big cities, namely New York City, Chicago, San Francisco, etc. 

The ford-go bike data I'm exploring today has trip records in San Francisco during Feb 2019. 

The database recorded 183,412 trips from both subscribers and non-subscribers, it also give us the duration of each trip, the start/end stations and their altitude and longitude. 

Most variables are categorical and are recorded in numeric datatype. 

There are missing data in all categories, but mostly in users' personal information. 

## Summary of Findings

During the exploration, I found most (85%) of the trips last less than 45 mins, and 8:00/9:00 and 17:00/18:00 are the most popular time to start the trips. I had a guess that shared bike system might serve as a commute tool for users. 

I want to understand what type of users the database best described and learned that 89% of data recorded were from subscribers. I further looked into users' time spending per trip, and subscribers' trip durations appearred similar patterns to the non-subscribers'. Most users ride 12-13min despite s/he is a subscriber or not. 

I then looked into the geographic feature of the dock stations and found that San Francisco shared bikes system has three main hubs around downtown area, Oakland and the silicon valley & San Jose area. 8 The top 10 most popular stations are within the downtown area. The most frequent start time for the top 10 most popular stations are around the morning and evening commute time. From the trip start time in each of the top 10 stations, I observed different patterns. For example, Market St & 10th St is popular during daytime; Caltrain Stations (& 2) are mostly popular at 5:00 and 14:00, maybe due to people commuting in the form of both train and bike. 12:00, 13:00 and 14:00 are popular time when people unlock the bikes, which trips could be used to go to lunches. 

## Key Insights for Presentation

My presentation follows my thinking pattern and presents viewers about the trip duration distribution and the trip start time characteristics. 

The presentation then use integrated maps to explore the geographic feature of the stations and the top 10 start stations. Furthermore, the presentation uses the boxplot to present the duration features for the top 10 stations.

The presentation ends with a exploration on duration and start time distributions for the top 10 stations.