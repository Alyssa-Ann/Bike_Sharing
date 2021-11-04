# Bike Sharing Challenge

## Project Overview

1. Import data into Tableau.
2. Create and style worksheets, dashboards, and stories in tableau.
3. Use Tableau worksheets to display data in a professional way.
4, Portray data accurately using Tableau dashboards. 


Software: Tableau, Pandas, Jupyter Notebook

## Overview of the Analysis

Using Tableau, import, style, and accurately portray data to create a proposal for a bike-sharing company in Des Moines. Present data that will help describe bike trip analysis of users for potential investors. This includes data on how long the bikes are checked out for all riders, the number of bike trips riders took each hours of a week, and the number of bike trips for riders for each day of the week. The data used will be from New York City's actual bike sharing program with real-life data that can then be analyzed and applied to Des Moines. While the two cities are very different, the fundamentals of the bike share program can be the same. 

## Results 

### Data Clean Up

Before any of the visualisations could be made, the original dataset had to be cleaned so it could be easily formatted in the visualisations. The tripduration column was originally formatted as an interger, but it would be more easily manipulated if it was shown in time. A new column was created to run the tripduration as datetime. To more easily deal with the gender of the bikers, the gender was changed to string as well. Below are the column lists from before the data clean and then after the clean. 

Data columns before clean up.

![Deliverable_1_Original_Columns](https://user-images.githubusercontent.com/88064181/140241874-0b9e3fbe-a00c-41da-b574-5c16214c62f2.png)

Data columns after clean up.

![Deliverable_1_Updated_Columns](https://user-images.githubusercontent.com/88064181/140241882-d6051578-72b5-4294-886b-9cc545885ad7.png)

### Visualizations 
By setting the data to visuals, one can determine the trends in users, ride times, and geographics locations where the bikes were used. These visual can help determine whether a bike sharing business would be successful in Des Moines. 

* To determine why riders are using the bikes, the August Peak Hours is an important graph to show that the peak times for usage center around commuting hours. Afternoon hours stay high, most likely, from the weekend users. 

![Deliverable_3_August_Peak_Hours](https://user-images.githubusercontent.com/88064181/140242638-ee163fe2-886d-46d8-8669-9613b538d671.png)

* The following checkout time by user graph shows how long users check bikes out within a set time. 

![Deliverable_2_Checkout_Time_by_Gender](https://user-images.githubusercontent.com/88064181/140242227-4e5ed318-9832-4a57-a079-6ce6db5969ed.png)

* The next graph, which shows the checkout time by gender,  shows that men checkout bikes for longer durations than women do. 

![Deliverable_2_Checkout_Time_by_Users](https://user-images.githubusercontent.com/88064181/140242298-7307dad2-43c4-4c75-aaba-3eee82946128.png)

* The Trips by Weekday by hour graph shows one that during the week, peak times for bike usage center around commuting hours in the morning and in the evening. 

![Deliverable_2_Trips_By_Weekday_by_Hour](https://user-images.githubusercontent.com/88064181/140242392-263d81e8-e13c-4afb-a32e-bd8cc70758cc.png)

* When broken down further, the Trips by Gender by Weekday chart shows that more men than women check out the bikes at these peak times. 

![Deliverable_2_Trips_By_Gender_By_Weekday_by_Hour](https://user-images.githubusercontent.com/88064181/140242433-47acf00a-c297-4397-a137-e996894f68db.png)

* When broken down evenfurther, the Use Trips by Gender by Weekday chart shows that subscribers to the service, especially male subscribers, make up the majority of bike trips. 

![Deliverable_2_User_Trips_By_Gender_By_Weekday](https://user-images.githubusercontent.com/88064181/140242518-72ed2be2-1868-4605-9896-226903c1c4d2.png)

* Finally, a chart that shows Rides per Bike is useful to determine how much maintenance may be needed on bikes, and to parse out how much this will cost. 

![Deliverable_3_Number_of_Rides_per_bike](https://user-images.githubusercontent.com/88064181/140242739-fd89d58f-3d7d-4d5a-8742-035e909f6f50.png)


## Summary 

[Tableau Story](https://public.tableau.com/app/profile/alyssa.dantuono/viz/CitiBikeChallengewithStory/CitiBikeChallengeStory)

Based on the data presented above as well as in the Tableau story whose link is above, it seems that while New York Citi Bike is used for toursits, it has a much bigger base of subscribers who use it in their daily lives. The trends of peak times being around commuting and early evening hours suggests that New Yorkers use these bikes to help them get around. More men than women use the bikes, which can be expected, and they trend in those peak hours. 

To help visualize this theory, maps with starting and ending locations by gender can help determine how these bikes are being used. While the most popular data points focus on Midtown, a lot of the outlying locations overlap between start and end site. With so many similar starting and ending points being used by the same gender, one can assume the bikes are being used in a round trip type of scenario. 

* Starting Locations by Gender

![Deliverable_3__Starting_Locations_Gender_recommendation](https://user-images.githubusercontent.com/88064181/140247268-e7681050-74b8-4f37-90dc-3a9a4367ed0a.png)

* Ending Locations by Gender

![Deliverable_3__Ending_Locations_Gender_recommendation](https://user-images.githubusercontent.com/88064181/140247288-77e0a9d6-1af6-4dd2-8af6-3a8bad7e0ff8.png)

In the Tableau Story presented above, with an example picture to follow, the usage of the bikes is highlighted. This is to determine how many bikes are utalized to the extreme and will need more maintenance. As see in the Bike Utilization chart, there are only a few outliers of bikes that will need maintenance provided more than the average bike. While the cost of maintenance and taking bikes off the routes is a concern, it is not one that should greatly affect the day to day usage of the bikes. Based on peak ride times, the middle of the night between 1 and 4 am is the best time to perform any neccessary maintenance. 

After reviewing the data, I would recommend a bike sharing company to be implemented in Des Moines. The majority of riders are subscribers which guarentees income for the company. The summer and spring quarters may see heavier traffic due to toursim which woud only boost the income provided by subscribers. Based just on timing and trends, it seems that the bikes are used for commuting and daily errands. This would be a benefit for the people of Des Moines. 
