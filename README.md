# NYC Citi Bike
Using Tableau to create visualizations for bike trip analysis on NYC Citibank dataset

## Overview

### Purpose
The purpose of this analysis is to use Tableau to perform bike trip analysis on NY Citi Bike dataset for 2018 and create visualizations to:
    
    - Show the total number of bike trips.
    - Show the number of bike trips by gender and user type.
    - Show the length of time that bikes are checked out for all riders and genders
    - Show the number of bike trips for all riders and genders for each hour of each day of the week
    - Show the number of bike trips for each type of user and gender for each day of the week.

## Results

The following link is to Tableau NYC Citi Bike Story: [NYC Citi Bike](https://public.tableau.com/shared/FMK3872TD?:display_count=n&:origin=viz_share_link)

 - The first chart reveals that the total number of bike trips on record is more than 2300k. This number is then broken down by gender. Riders identifying as 'Male' account for 2x as many as those identifying as 'Female'. 
 
- Citi Bike breaks down user types into two categories: customer and subscriber. Customers have a 24-hour or 3-day pass while subscribers have an annual pass. The Subscribers account for the majority of users regardless of identifying as male or female. However, users of unknown gender leans towards being customers rather than subscribers. 

<img src=resources/totaltrips.png height=400 width=400 align=left>
<img src=resources/tripsbygender.png height=400 width=400 align=middle>
<img src=resources/tripsbyusergender.png height=400 width=400 align=right>

- The most popular time for bike trips are 8am to 9am Monday through Friday, while 5pm to 7pm are popular times Monday through Friday. Rides on Saturday and Sunday popular times are spread throughout the days between the hours 9am to 8pm. There is a noticeable drop in the number of trips for Wednesday in the evening. This trend follows when popular ride times are split by gender.

- Riders of unknown gender did not follow this trend having popular ride times on Sunday and Saturday between the hours of 9am to 7pm and 9am to 8pm respectively. During the week the numbers also tend to drop on Wednesdays compared to other work days. 
- Popular ride days broken down by user type reveals that Saturday is the most popular trip day for customers regardless of gender or if gender is unknown. For subscribers, the most popular day is Thursday overall. Filters are needed to see this and can be applied via Tableau link.

- Overall the number of riders decreases as the trip duration increases as seen in the last image. 

<img src=resources/popularrides.png height=400 width=400 align=left>
<img src=resources/popularridesunknown.png height=400 width=400 align=middle> 
<img src=resources/tripduration.png height=400 width=400 align=right>
<img src=resources/populardays.png height=400 width=400 align=right> 



## Summary
Overall, the user types seem to differ on when they ride alluding to that there these different groups may depend on tourism. Tourists may fall under customers more than subscribers since it is reasonable to have a shorter pass if they're only visiting and will not benefit from a subscription. Also, customers, riders with 24-hour or 3-day passes, are more likely to ride on the weekend. Again, this alludes to being a visitor not a resident of NYC. Subscribers seem more likely to bike on Thursdays and will benefit more from a subscriber pass. 
An additional map showing the start location for riders with a layer that includes points of interest could give more insight as to where people are more likely to start based on points of interest. 
Finally, a visualization of all  start and stop stations to show the total use of each station and which stations have the highest amount of traffic and or the lowest.
