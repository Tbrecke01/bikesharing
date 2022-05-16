# bikesharing

## Overview
An analysis of NYC CitiBike bikesharing data from August 2019 using Tableau. This Tableau story can be seen here: https://public.tableau.com/app/profile/tyler.brecke/viz/NYC_Citibike_Challenge_16526642294450/NYCCitibikeAnalysis?publish=yes

This analysis was done as a baseline to gauge potential use for a bikesharing program based in Des Moines, Iowa. This analysis sought to answer a few key questions such as:
    - Who uses the bikeshare program?
    - What is the most popular time(s) to rent bikes?
    - How long do people usually rent bikes?

### Results
![Gender of Riders](https://github.com/Tbrecke01/bikesharing/blob/main/Images/Gender_of_Riders.png)

Above we can see the breakdown of NYC Citibike users by gender. We can see that ~2/3 of riders are male. This can be used in the early-stages of setup to focus advertising more towards the male audience and potentially tailor bikes more towards males where possible (more larger bikes available for instance). Alternatively this means we should tailor advertising more towards females to hit a broader population, since we may be able to count on higher male adoption.

![Checkout Time](https://github.com/Tbrecke01/bikesharing/blob/main/Images/Checkout_Time.png)
![checkout time by gender](https://github.com/Tbrecke01/bikesharing/blob/main/Images/Checkout_Time_Gender.png)
This data showcases how many trips were done for varying lengths of time. From these graphs, we can see that the vast majority bike trips are sub 30 minutes in length, irregardless of gender. This points towards our bikes having frequent but not very intense use, which could influence how far apart bike stations are placed as well as what kinds of maintenence activities we should most expect.

![weekday trips](https://github.com/Tbrecke01/bikesharing/blob/main/Images/Trips_by_Weekday.png)
![gender trips](https://github.com/Tbrecke01/bikesharing/blob/main/Images/Trips_by_Gender.png)
![weekday gender trips](https://github.com/Tbrecke01/bikesharing/blob/main/Images/Trips_by_Gender_wk.png)
These charts all highlight peak trip activity, or what times and days most people are renting bikes. From this data, we can see that peak bike usage is generally 6am-9am and 5pm-8pm during the week. This points to two things: that the majority of users are using bikes to commute to and from work (possibly influencing bike features again) and that the optimal times for maintenence and repairs would be Sunday mornings when usage is the lightest.

![average trip duration by age](https://github.com/Tbrecke01/bikesharing/blob/main/Images/trip_duration.png)
This chart showcases average trip length based on the users age. It shows that, generally, as users get older their trip durations get shorter. This can be used to help gauge trip duration for Des Moines vs New York based on average population age for the two cities.

## Summary
At a high level, we can predict when the highest bike usage will be (6am-9am and 5pm-8pm during the week), who the majority of our riders will be (males), and how long the average bike rental is (sub 30 minutes). This data can be used to inform optimal bike station placement (10 minute intervals), maintenence times (Sunday morning), and how we should focus marketing. One of the major downsides of this data though is that it is all based on New York City. Some additional visuals that would be useful would be: a comparison of existing bikelanes in Des Moines compared to NYC, average age for Des Moines vs NYC, and the gender profile of Des Moines vs NYC. This will help us determine whether the NYC Citibike data is a good reference for Des Moines, or whether data from alternate cities is needed.
