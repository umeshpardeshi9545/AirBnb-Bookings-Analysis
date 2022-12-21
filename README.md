# AirBnb-Bookings-Analysis

Firstly we imported all required library then we have a dataset from New York-based Airbnb. NY is one of the most expensive places to live in the United States. We want to do an in-depth analysis of one of these populous cities in the world. Our dataset contains many features, locations with host id, pricing, hostnames, room types, and availability throughout the season. as the data set have a review column by using that column we figure out Top neighbourhood_group as per the review. In given data set there is last_review column which in date form but data type string. with the help of datetime librarly we extract year from give data set. after that we add new coloumn which is year and extracted year data assign to year column. now we have new year column with the help of that column. we extracted year wise data along reviews. From these characteristics, we extract information like the Most booked neighbourhood_group by using the count function. then we extract the minimum price of the respective room type in their neighbourhood_group. also, we extract information total number of different room types like Private rooms, Entire homes/apt & Shared rooms available in neighbourhood_group. we also fetch information As per selected area, midtown & room type with the budget. we also visualize all the above data in different like bar charts, pie, lines, box plots, and map chart forms by using matplotlib and seaborn Library.

with the same we also tried to extract information like the most expensive places to live in New York, the location actually varies by occupancy, the type of room people tend to select, is there a specific season for travelers, or an area where we can track spikes in property prices or occupancy rates, and more. We've been doing data processing, zeroing, and creating new features since the last review date. In addition, we plotted the location data and distributed our numerical features, and perform univariate and bivariate analyses with multiple dependencies. As provided data set contains latitude & longitude by using these values we plot the map as per the given latitude & longitude values. but we can conclude that,

Manhattan and Brooklyn are NY's most expensive neighborhood.
Manhattan and Brooklyn are NY's most expensive neighborhoods.
Manhattan has given more business in terms of revenue because they have booked the maximum no of entire homes/apt and private rooms.
We should work to find a way to get more business from Brooklyn since they have very less bookings compared with other groups.
Manhattan is the busiest neighborhood group than others ie, Brooklyn, Queens, Bronx, and Staten Island.
As on 2013 there are only 48 reviews, as year changes number of reviews rapidly increasing on 2019 it will became total 25209 reviews
Guest prefered private room as compared to Entire home/apt & shared room,room Count as follow.
Private room = 629
Entire home/apt = 488
Shared room = 454
