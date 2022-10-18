# Bike Sharing Field Research

## Overview

### Background
We are helping our friend Kate to research the bikeshare business in New York City so that we can make a proposal to start a bike sharing business in Des Moines, Iowa. The data we selected was from August of 2019, because we wanted to analyze peak use during the summer. There is a potential angel investor who wants to help with the seed funding for the business in Des Moines, so we will create a business proposal with a Tableau Story. 

### Purpose
The purpose of the analysis is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. We are sharing a bike trip analysis to convince one of the key stakeholders. We are interested in what kind of users are riding (e.g. males and females, subscribers or customers), and the characteristics of the trips they are taking (e.g. time of trip, length of trip, locations of start and end points). 

## Results

The results can be viewed using the link below. There are screenshots of each data visualization below, and summaries of the conclusions from each image.

[Link to dashboard](https://public.tableau.com/views/CitiBike_Challenge_16659597506140/CitiBikeChallengeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

**1. Checkout Times for Users**

![checkout times for users](https://github.com/saramcel/bikesharing/blob/35f05a6fd35866c919a0337a75b56cb57bdeb2f6/Resources/img1.png)
- This graph shows that most rides are less than 23 minutes long, and the vast proportion of rides are less than an hour. The trip length that most users seem to take is about 5 minutes. 

**2. Checkout Times by Gender**

![checkout times by gender](https://github.com/saramcel/bikesharing/blob/35f05a6fd35866c919a0337a75b56cb57bdeb2f6/Resources/img2.png)
- This graph shows that most bike riders are male, and that the trends for male and female riders are similar. Both male and female rides tend to spike at 5-6 minutes per trip, and trips tend to taper off around 47 minutes for all reported genders. Unknown gender has a flat curve, with low kurtosis. 

**3. Trips by Weekday per Hour**

![trips by weekday per hour](https://github.com/saramcel/bikesharing/blob/35f05a6fd35866c919a0337a75b56cb57bdeb2f6/Resources/img3.png)
- This heatmap shows that the most common stoptimes are right before typical work hours on each weekday, and right after work hours on Mondays, Tuesdays, Thursdays, and Fridays. Wednesday evenings are not as popular for Citibike, for reasons that we should investigate--possibly there is a competing form of transportation, for example a free bus that runs on Wednesday evenings. On the weekends, the bikes are used throughout daylight hours, mostly in the mornings and more often on Saturdays than Sundays. 

**4. Trips by Gender (Weekday per Hour)**

![trips by gender weekday per hour](https://github.com/saramcel/bikesharing/blob/35f05a6fd35866c919a0337a75b56cb57bdeb2f6/Resources/img4.png)
- Males, who compose most of the ridership, have a defined pattern of riding that is much like what we observed in the previous graph. The heatmap for females shows a similar pattern,but with less ridership. The unknown gender seems to use the bikes on Saturday afternoon more than any other time.

**5. User Trips by Gender by Weekday**

![user trips by gender by weekday](https://github.com/saramcel/bikesharing/blob/35f05a6fd35866c919a0337a75b56cb57bdeb2f6/Resources/img5.png)
- This heatmap shows customers vs subscribers and each recorded gender. Customers take fewer trips than subscribers, as one might expect. The heaviest use is by males who are subscribers. The highest usage day for males and females is Thursday, which is something we should explore further. The unknown gender rides the bikes most often on the weekend as a customer--these might be tourists who are not subscribing to the service because they are only in the city for a little while (which also explains why they might not have submitted gender data).

**6&7. Top Starting Locations and Top Ending Locations**

![starting and ending locatioons](https://github.com/saramcel/bikesharing/blob/35f05a6fd35866c919a0337a75b56cb57bdeb2f6/Resources/img6&7.png)
- These maps show the most popular starting and ending locations for Citibike trips. These maps are best presented together for easier comparison. The maps are very similar, with most of the activity happening in lower Manhattan. The starting and ending location maps being so similar implies that the same trips could be repeated often, for example commuting to work.

## Summary

The one big takeaway from these visualisations is that the typical Citibike rider is a subscriber who is male, and the rides are typically short commutes to and from work, and outings on Saturday. Trips seem to be within lower Manhattan, and usually last less than 23 minutes, typically only about 5 minutes.

1. One additional visualization would be to analyze the fee structure in tandem with the trip length. For example, if there is an extra charge for each minute over 5 minutes, then there would be an incentive for the riders to only use the bikes for 5 minutes. Shorter rides might work in New York City, but not in Des Moines, so the fee structure might need to be different to allow longer use of the bikes before extra charges begin. 
2. Another additional visualization would be to alter the bike utilization visualization from the module. Rather than visually estimating which bikes have traveled the longest by the size of the marker, we could create a table with the Bike ID in one column and the amount of total trip time in the second column. Then, we can add the trip time to the color marker and sort descending, so that at the top of the list we can see the exact numbers and the relative colors for the bikes with the most checkout time. Although the trip times might be different in Des Moines, it is useful to get an idea of how the bikes are used. 

