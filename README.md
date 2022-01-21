# NYC Citi Bike Analysis

## Overview of Analysis

The purpose of this analysis is to create visualizations of NYC Citi Bike data from August 2019 to support a business proposal being pitched to potential investors to expand this bikesharing program to Des Moines. While NYC and Des Moines are very different, it is useful to see how successful the program already is in general. The visualizations in this analysis will explore the following:
- Length of time that bikes are checked out for all riders and genders
- Number of bike trips for all riders and genders for each hour of each day of the week
- Number of bike trips for each type of user and gender for each day of the week
- Top starting locations
- Peak hours

[Link to the NYC Citi Bike Story.](https://public.tableau.com/views/NYCCitiBike_16427169816350/NYCCitiBikeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## Results
### Checkout Times for Users
Citi Bike users check out bikes for less than one hour, and most riders check out bikes for a total of 5 minutes.
![CheckoutTimesforUsers](https://user-images.githubusercontent.com/90656004/150448070-0a14d9ab-26c0-44e7-89de-3b269e29f2ac.PNG)

### Checkout Times by Gender
Riders are primarily male, but females and those in the unknown categories also follow a very similar distribution in trip duration.
![CheckoutTimesbyGender](https://user-images.githubusercontent.com/90656004/150448493-df984b47-d45b-435b-afdd-5c54c9f34027.PNG)

### Trips by Weekday for Each Hour
The most popular times to use Citi Bikes during the weekdays were from 7-9am and 5-7pm, which are peak commuting times. This suggests that many customers and subscribers use the bikes to commute to and from work.
![TripsbyWeekdayforEachHour](https://user-images.githubusercontent.com/90656004/150448340-2ba59874-0cd2-4474-936b-a7a20fb3269f.PNG)

### Trips by Gender by Weekday per Hour
A breakdown by gender shows that most males and females use the bikes during commuting hours. 
![TripsbyGender_WeekdayPerHour](https://user-images.githubusercontent.com/90656004/150447964-b9d30631-e618-4d6a-88f9-4d0a4e1eab83.PNG)

### Trips by Gender by Weekday
Subscribers used Citi Bikes significantly more than regular customers, which was to be expected. Both user types and genders used the bikes on Thursday's more than any other day. 
![TripsbyGenderbyWeekday](https://user-images.githubusercontent.com/90656004/150447970-d3b31ff7-1fc0-4f80-a4aa-0b538bb1a4cd.PNG)

### Top Starting Locations
The highest-traffic locations for starting Citi Bike rides were clustered in the downtown area. 
![TopStartingLocations](https://user-images.githubusercontent.com/90656004/150451712-11bfe34d-e490-4d44-b617-615db72db442.PNG)

### Peak Hours
The bar chart below indicates that the demand for bikes is highest at 8am, 5pm, and 6pm. 
![AugustPeakHours](https://user-images.githubusercontent.com/90656004/150451730-293b8b42-f7eb-4212-b01b-7fda087e18a3.PNG)

## Summary

Based on these analyses, this Citi Bike program is successful and safe to invest in for expansion to Des Moines. The visualizations revealed some interesting information that could be useful for investors and the bikesharing team. In general, Citi Bikes are used for short trips (less than one hour), riders are primarily male, Citi Bikes have the highest usage during weekdays at peak commuting times, and the downtown is the most popular place for people to start their Citi Bike trips. These trends may not be the same in Des Moines once the program is implemented, but gathering this data for the new city and comparing it to NYC could suggest its sustainability in other cities as well. 

Additional visualizations that could be performed, given the dataset, to inform the company how best to attract new users and increase utilization by existing and potential new users:
- The top starting and top ending locations with respect to the hour and to the day. This would show where and when Citi Bikes are being used in a more holistic way. 
- The starting station id's and name with the highest traffic. The team can get then look into why these stations are performing better than others.
