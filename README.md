# Bikesharing
## 1.	Overview
NYC Citi Bike is a bike sharing analysis in NYC using Tableau to visualize the data. This analysis will be used later to make a business proposal for investor to make a bike sharing program in Des Moines.
The Following task will be performed in this analysis:
-	Create visualizations that show how long bikes are checked out for all riders and genders.
-	Create visualizations that show how many trips are taken by the hour for each day of the week, for all riders and genders.
-	Create visualizations that show a breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.
-	Create visualizations that show total number of rides, customer type,  User by gender, peak hour in August break by hour and gender. 
-	Create visualizations that show top starting locations
-	Create visualizations that show map to determine the bikes due for repair
## 2.	Resources
Data Source: 201908-citibike-tripdata.csv

Software: Tableau Public 2021.3, Pandas, Python

## 3.	Result
To see full visualization of the story click : [link](https://public.tableau.com/app/profile/inez8143/viz/assignment_16379023188680/NYCCitiBike?publish=yes)

a.	Basic Information

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/143724923-1a950280-f4fd-49eb-868e-bb54c33f7071.png"/>
</p>
<p align="center">
  <sub>Figure 1 Basic Information Dashboard  </sub>
</p>

In this dashboard it shows basic information about bike sharing in NYC:
-	The total number of rides is 2,344,224
-	Gender breakdown of users in pie chart that shows the user of bike sharing is Male around 65%, female user around 25% of the user and the rest is unknown.
-	Around 81 % of the user is subscriber and the rest is customer
-	The peak Hour is around 8 A.M to 9 P.M in the morning and 5 P.M to 6 P.M in the evening 

b.	Checkout times for User

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/143724974-68e0f359-841d-4601-889f-32c38de6a6ac.png"/>
</p>
<p align="center">
  <sub>Figure 2 Checkout times for user </sub>
</p>

Figure 2 shows us Checkout times for user, with x axis is trip duration divided by minutes, and y axis is number of checkout bikes.  User mostly checkout around 5 minutes and the trip is usually less than one hour. It means that user usually use bike sharing for short distance trip.

c.	Checkout times for User by gender

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/143724981-b563f9d4-fd96-4660-8bb4-29d804ddcf57.png"/>
</p>
<p align="center">
  <sub>Figure 3 Checkout time user by gender </sub>
</p>

Figure 3 shows us Checkout times for user, with x axis is trip duration divided by minutes, and y axis is number of checkout bikes. It has 3 lines that represents gender, blue for female, orange for male and red for unknown. From the graph we can see that  gender is not impacted checkout times that much. Male user checkout around 5 minutes, Female user in 6 minutes and unknown user in 10 minutes.

d.	Trips by Weekday for Each Hour

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/143725016-ab6a621d-460f-4dde-9ee5-8a7eae2b4fc9.png"/>
</p>
<p align="center">
  <sub>Figure 4 Trips by weekday for each hour  </sub>
</p>

Figure 4 shows number of trips per hour and per weekday. The darker the color means that more trips happened on that specific time while the lightest color means less trips happened on that specific time. From the figure we can see that most of the trips happened around Monday to Friday from 8 A.M to 9 A.M in the morning and 5 P.M to 6 P.M in the evening. While on the weekend most of the trips starts from 10 A.M to 5 P.M

e.	Trips by Gender (Weekday per Hour)

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/143725054-0cb746a6-2825-4123-9736-00654f372049.png"/>
</p>
<p align="center">
  <sub>Figure 5 Trips by Gender (Weekday per Hour) </sub>
</p>

Figure 5 shows number of trips per hour and per weekday divided by Gender. The darker the color means that more trips happened on that specific time while the lightest color means less trips happened on that specific time. From the figure we can see that there is no significant impact of gender, the checkout times is almost similar. Most of the trips happened around Monday to Friday from 8 A.M to 9 A.M in the morning and 5 P.M to 6 P.M in the evening. While on the weekend most of the trips starts from 10 A.M to 5 P.M. Although from the graph we can see that male user has higher number of trips.


f.	User Trips by gender by Weekday

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/143725077-f44251b1-c108-403c-bde9-f84ee906f3ce.png"/>
</p>
<p align="center">
  <sub>Figure 6 User trips by Gender by Weekday  </sub>
</p>

Figure 6 shows number of trips on weekday divide by user type and gender. The darker the color means that more trips happened on that specific time while the lightest color means less trips happened on that specific time. From the figure we can see that for customer the trips happened on weekends while for the subscriber on weekday, although the number of trips on weekend for subscriber still high. 

There is higher number of trips for unknown gender customer compared to female and male on weekend, while the distribution of trip is almost the same for all gender on weekday. The distribution of trips for subscriber during the weekday for female and male almost the same, while for the unknown gender has the same distribution in all day. 

g.	Top Starting location

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/143725101-8796e619-74a1-4b98-b8d3-c50950eabde2.png"/>
</p>
<p align="center">
  <sub>Figure 7 Top Starting Location  </sub>
</p>

Figure 7 shows us map of top starting location in NYC. The larger and the darker color of the circle represents that most of trips start at that location, while the smaller and the lighter color of the circle represents the opposite. From the graph we can see that downtown areas are much popular than the other location.

h.	Bike Repair
<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/143725106-eb886f49-1f42-4949-9f6d-7021708262d2.png"/>
</p>
<p align="center">
  <sub>Figure 8 Bike repair  </sub>
</p>

Figure 8 show bike that due for repair. The larger and the darkest the color of the square represents that bike due for repair sooner. It counts the trip for the specific bike id, the higher the number of trips the square will be larger and darker. By using this map, company can prioritize which bike that need to be repair first and rotate it with the bike with the less trips.


## 4.	Summary
From the visualization above we can take conclusion:

a.	Basic Information

Most of the user is male with category type subscriber. The peak hour is around 8 A.M to 9 P.M in the morning and 5 P.M to 6 P.M in the evening. To increase the market of bike sharing for female gender, the company need to make research to know why the female user is relatively small compared to the male, is it because of the bike is not that comfortable to use for female, is it about safety issue, or any other issues.  By knowing the issue, company can make improvement in the service to accommodate user and increase their market potential.

b.	Checkout Times and Trips by Weekday

Looking at the checkout times, most of the user use the bike for less than one hour trip with most trips is 5 minutes for male, 6 minutes for female, and 10 minutes for unknown gender. This means that they usually take the bike usually only for short distance trip.

In figure 4,5 and 6 we can see that most of the trips happened around 8 A.M to 9 P.M in the morning and 5 P.M to 6 P.M in the evening from Monday to Friday. Connecting the dots with checkout times, we can say mostly the user take a trip for work or school in the morning and back to their homes in the evening. To increase potential user, bike sharing company can offer discount for company or student. 

c.	Starting Location and Bike Repair

From Figure 6 we can see that the popular starting location is in downtown. Using this information, the company will know where to add more station and bike in downtown area.  By using the starting location and bike repair graph, company can decide which bike that need repair and rotate the bike from popular station to less popular one.


To add more information for the investor, we can add more visualization:

a.	Graph to show starting and stop location for weekday and weekend. The trend might be different for weekday and weekend. The popular location for weekday might be in business center area, school, or university, while for the weekend in popular tourist spot. By knowing this the company can decide how many bikes to put in the location for different days.

b.	Checkout times per user type. By using this we can know the nature of different user type. Does customer usually take a trip more longer because they are using it for sightseeing , the subscriber only use it for work or school, or any other information we can see from the graph.


