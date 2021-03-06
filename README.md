# NYC Bike Sharing Analysis

## Overview
This analysis uses data from one month of rides with a bikesharing service in New York City to provide insight which may be helpful in the design of a similar service in another location. The focus is on when and for how long users tend to use the bikes. A gender breakdown is included as a potential modifier. Also, there are two methods for users of this service. Some subscribe to the service, while others pay by the ride. 

[see Tableau story: NYC Bikesharing](https://public.tableau.com/app/profile/anna.wiste/viz/NYCBikesharing_16392737140530/NYCBikesharing)


## Results

1. Distribution of trip duration
![trip duration](NYC_Bikesharing1.png)
Peak duration for trips is 5 minutes, dropping off rapidly, with few rides lasting more than an hour.
<br/>

2. Breakdown of rides by gender of rider
![gender breakdown](NYC_Bikesharing2.png)
65% of rides were by male riders, and 25% by female riders. 10% were unknown.
<br/>


3. Distribution of trip duration broken down by gender of rider
![trip duration by gender](NYC_Bikesharing3.png)
The distribution of rides by males and females is similar, with a peak of 5 and 6 minutes, respectively, but proportionally, female riders had more rides of 20-30 minutes duration.
<br/>

4. Heatmap showing distribution of rides by hour of the day, broken down by day of the week
![Rides by hour of the day and day of the week](NYC_Bikesharing4.png)
Peak start times for rides fall from 6am-10am and 5-8pm pn weekdays, with rides on weekends more evenly distributed between 9am and 8pm. There is a surprising lack of rides on Wednesday afternoons.
<br/>

5. Distribution of rides by hour, broken down by day of the week and gender
![Rides by hour, day of the week and gender](NYC_Bikesharing5.png)
The pattern in start times is the same in male and female riders, including the lack of rides on Wednesday afternoon.
<br/>

6. Breakdown of rides by user type: subscribers vs. customers
![User type](NYC_Bikesharing6.png)
81% of rides were taken by subscribers to the service, with 19% as individual rides.
<br/>

7. Rides by user type and gender, broken down by day of the week
![Day of the week, by gender and user type](NYC_Bikesharing7.png)
Subscribers tend to ride more on weekdays (except Wednesday), though still with high numbers of rides on weekends. Customers with individual rides were comparatively evenly spread throughout the week, though there were more rides on the weekends. Patterns are the same in both male and female riders. Riders with unknown gender were much more likely to be customers rather than subscribers, and to have weekend rides. 
<br/>

## Summary
This dataset contains information on over 2 million rides with a bikesharing service in just one month, with information on duration, location and timing of the rides, and age and gender of the rider. A large majority of rides overall are very short, less than 10 minutes in duration, in both male and female riders There is some greater variance amongst female riders, with relatively more rides falling in the 20-30 minute duration. Overall two-thirds of rides had a male rider. There is a consistent pattern where peak ridership occurs during rush hour times on weekdays (with the exception of Wednesday afternoons), which is not dependent on gender. Not surprisingly these weekday rush hour rides are primarily taken by subscribers to the service. Subscribers do use the bikes on weekends, but this is also the time when riders try out the service for single rides. 

Another feature available in this dataset which we have not yet explored is the age of the rider. It would be helpful to see the distribution of age of the riders. Based on that distribution I would then bin the data and look at patterns in user type and day of the week by age of the rider. 
