# bikesharing

Link to Story - https://10az.online.tableau.com/#/site/roo/workbooks/1879467?:origin=card_share_link


## Background:

Investors are considering a bike sharing program in Des Moines, Iowa and want to base it on the Citi Bank bike sharing program in New York City. The bike share data from New York City was doanloaded and analyzed using Tableau to present the data to the investors. The key questions being anaswered in this analysis are:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.


## Results: 

### Number of Bikes based on Duration

![Checkout Times for Users](https://user-images.githubusercontent.com/107443962/191166957-0ccfd777-78a1-426a-b409-1a0b09582d0b.png)

This graphing of number of trips by duration show that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in length, with a swift dropoff in number of rides over an hour in length.

### Number of Bikes based on each Gender by Hour

![Number of Nikes based on Duration ](https://user-images.githubusercontent.com/107443962/191167589-44b46c52-a85a-4617-964d-93638e11d863.png)

This breakdown of number of rides by duration, separated by gender, makes it even more apparent how many more rides are taken by male-identifying customers.

### Number of Bike Trips on an Hourly Basis

![Trip by Weekday per Hour ](https://user-images.githubusercontent.com/107443962/191167888-360d2e64-5c81-40c2-9ba2-12e70dc58671.png)


### Number Bike Trips by Gender on a Hourly Basis

![Number Bike trips by Gender on Hourly Basis](https://user-images.githubusercontent.com/107443962/191167854-e3b6f0c0-0158-40be-8b32-a4f3b43ec99c.png)

A heatmap also helps show weekly usage patterns. Once again we can see the heavy bike usage during weekday commute times, and weekend usage is spread throughout the middle of the day. An interesting anomaly is the relatively low bike usage during Wednesday's end-of-day commute. It could be useful to explore reasons for this (system outage, Wednesday holidays in August, something less obvious?), but it could just be an arbitrary anomaly. Also, we can still see that low-usage time in the early morning hours, every day of the week.

### Number of Bike Trips based on Gender on a Daily Basis

![Numberof Bike Trips based on Gender on a Daily Basis](https://user-images.githubusercontent.com/107443962/191167797-65c5d817-2e17-4ad6-a72a-cf3fcf43c17f.png)

Lastly, this heatmap reinforces how much of the userbase is dominated by male-identifying, subscribing users. Why this is the case is unclear and warrants additional study.

There are one or two additional charts available in the Tableau analysis, but they tell pretty much the same story that has already been displayed above.

## Summary 

In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders, but male users seem a reliable market. And main usage seems focused around morning and evening commute times.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:

- Trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;
- Average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.
