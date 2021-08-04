# NY Citibike with Tableau

## Overview of Project
For this week's project, we will be using Tableau, a data analysis and visualization tool. Tableau is great for helping us tell a story by providing us with the tools to create analytic dashboards. Creating clear and easy to read visualizations is helpful for stakeholders when making decisions. 

### Purpose
The purpose of this week's project is to present a business proposal for a bike-sharing company. We will be creating visualizations based on data from a New York Citibike dataset. Citi Bikes is the nation's largest bike share program. This information will be used to see if a bike-sharing company could be a good business investment in Des Moines. Using Tableau, we will be creating visualizations that show:
- What are the peak times for bike trips and how many bike trips were there in the month of August.
- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

## Results

To display our New York Citibike data, we created four dashboards with two visualizations per dashboards. We then combined the dashboards to create a story. 

[Link to Tableau Dashboards/Story](https://public.tableau.com/views/NYC-Citibike-Challenge_16279379182660/NYCCitibikeAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link)

#### August Peak Times and Total Number of Rides
![AugustOverview](/Resources/AugustOverview.PNG)
The bar chart above displays the amount of bike trips per hour for the month of August. By looking at this chart, you can see the peak times are around 7am and between 5pm to 7pm. It can be assumed that these bikes are being used for commutes since they are around the times that people are going to or leaving work. I also included the total amount of rides in August on the upper right-hand side. 

#### User Trips by Gender by Weekday and User Types
![UserTypesbyGenderbyWeekday](/Resources/UserTypesbyGenderbyWeekday.PNG)
On the left, we have a heatmap that shows the number of bike trips by gender for each hour for each day of the week. This heat map is also separated into user types. There are two user types: Customers and Subscribers. One the right, we have a pie chart that shows the amount of Customers and Subscribers. Subscribers make up 81% of the users. Specifically, Male Subscribers have the highest amount of trips. 

#### Trips By Weekday 
![TripsByWeekday](/Resources/TripsByWeekday.PNG)
The two heatmaps above show bike trips by weekday per hour. Trips by Weekday for Each Hour shows that there is a high number of trips taken Monday through Friday around 7am and between 5pm and 7pm. It also shows on weekends there's higher activity between 9am and 8pm. Trips by Gender (Weekday per Hour) shows the same bike trip information from the visualization above but broken out by gender. This chart confirms that there are more males that use the citi bikes.

#### Checkout Times
![CheckoutTimes](/Resources/CheckoutTimes.PNG)
The two line charts above show the length of time that bikes are checked out. Checkout Times for Users shows how long bikes are checked out for all users. Checkout Times by Gender shows the same bike trip duration information from the visualization above but broken out by gender. Regardless of gender, most bike trips are used for a short duration or less than one hour. There are a large number of bikes that are only being used for 5 minutes.


## Summary
Based on the visualizations above, there are a few key findings that I would like to highlight. By looking at the peak times and which days the bikes are most used, it looks like most users are using the bikes to commute to work. Also by looking at the users, there are more Subscribers than Customers. The Subscribers most likely live in the city so they can utilize the bikes regularly such as using the bikes to get to and from work or getting around on the weekends. Males also take the most bike trips. It has not been determined why there are more males using the bikes than females or unknown.

If we had additional data, I would have liked to create visualizations on reasoning for bike trips. This can help clarify if the majority of bike trips are used for commuting. It would also be helpful if we had more information to visualize the amount of bike routes and accessibility. New York may have more bike friendly routes in comparison to other cities. 
