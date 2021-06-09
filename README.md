# Bikesharing

## Overview
The purpose of the analysis on this repository is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To do so, bike trip analysis is performed on Citibike data from NYC to figure out how the business works in New York. From that analysis, a proposal is created on how it might work in Des Moines. The following results describe the analysis from NYC and how it would apply in Des Moines.

[Click here for a link to the Tableau Public Dashboard](https://public.tableau.com/profile/sam.young5633#!/ "link to dashboard")
The dashboard utilized for this repository is Bikesharing_Challenge


## Results

### Where did bikers start their rides?

<p align="center">
  <b>NYC Bikeshare Starting Locations</b>
 <br>
  <img src="https://github.com/smyoung88/bikesharing/blob/main/images/start_1.png" title="NYC Bikeshare Starting Locations">
</p>

This map visualization shows where the starting locations are for bikeshare rides and are colored and sized by the count at each station. One observation was that there may have been a higher count of riders at starting locations that had higher amounts of tourism at them. This is one of the original visualizations created early on in the analysis and a key indicator at where the first locations should be positioned in Des Moines. 

### How long do they ride?

<p align="center">
  <b>Length of Time Bikes Are Checked Out in NYC</b>
 <br>
  <img src="https://github.com/smyoung88/bikesharing/blob/main/images/trip_duration_2.png" title="Length of Time Bikes Are Checked Out in NYC">
</p>

New York City does not have a bikeshare business where its riders are on their bikes for a long time. As seen in this graph, the majority of bikes are only used for less than an hour per ride. This business might have more to do with easy commuting around the city rather than taking long scenic joyrides. This presents two different opportunities to the investors on where they can place their bikeshare stations. One may serve the workfoce for commuting around the city during the day and and the other locations could be for leisure and joyriding around scenic routes or any special landmarks that would be worth a nice long ride to. 

### Who are the main riders?

<p align="center">
  <b>NYC Male vs Female Rider Distribution</b>
 <br>
  <img src="https://github.com/smyoung88/bikesharing/blob/main/images/gender_bias_3.png" title="NYC Male vs Female Rider Distribution">
</p>

This graph shows that there are a lot more males riding bikes around NYC than females. Female riders are in blue, male riders are in orange, and riders whos genders were unknown are in red. As an outsider that is not familiar with the area, one might wonder if there are more males than females in NYC and that is where there is such a big difference. If not, investors might consider how to be more inclusive of females to increase their numbers and improve the business opportunity when applied to Des Moines.

### What are the peak hours?

<p align="center">
  <b>NYC Bikeshare Peak Hours</b>
 <br>
  <img src="https://github.com/smyoung88/bikesharing/blob/main/images/peak_hours_4.png" title="NYC Bikeshare Peak Hours">
</p>

The heatmap above shows the count of riders by the time of day and the day of the week. The darker colors represent higher counts as seen on the legend, and lighter yellow colors represent less traffic of riders. As mentioned above, it appears the bikeshare business in NYC likely caters to the working community for their source of transportation to and from work. Although areas might have higher traffice with tourism in those areas, the majority of traffic shown on the bikes is during the commuting hours of the day during the week. Weekends tend to be more populated on bikes during the days as expected when peopl are going out to have some fun!

### Are peak hours the same for males and females?

<p align="center">
  <b>NYC Male vs Female Bikeshare Peak Hours</b>
 <br>
  <img src="https://github.com/smyoung88/bikesharing/blob/main/images/header_peak_5.png" title="header"><br>
</p>
<p float="left">
  <img width="45%" height="45%" src="https://github.com/smyoung88/bikesharing/blob/main/images/peak_female_6.png" title="female_peak">
  <img width="53%" height="53%" src="https://github.com/smyoung88/bikesharing/blob/main/images/peak_male_7.png" title="male_peak">
</p>

As we dove in further to gender analysis, the above heatmaps tell a similar story that we saw from the previous graphs. There is a higher count of males riding bikes than females overall. The female and male heatmaps are alike where the timing during days of the week vs the number of rides for each follows the same trend.

### Who is subscribing?

<p align="center">
  <b>NYC Bikeshare Subscribers vs Customers</b>
 <br>
  <img src="https://github.com/smyoung88/bikesharing/blob/main/images/usertype_8.png" title="NYC Bikeshare Subscribers vs Customers">
</p>

This heatmap gives a bold statement again on where the majority of the business is coming from. The darker the blue, the higher the number of either subscribers or customers there were for those days. There are significantly more males subscribing to the bikshare service vs females and the amount of one off customer are about the same. Avoiding redundancy from previous visualizations, maybe there is a higher working demographic for males than females, and this is why male numbers are so much higher. Thursdays and Fridays appear to have the highest count of subscribers from males. Maybe there are promos on those days? 

### Where do bikers end up?

<p align="center">
  <b>NYC Bikeshare Ending Locations</b>
 <br>
  <img src="https://github.com/smyoung88/bikesharing/blob/main/images/usertype_9.png" title="NYC Bikeshare Ending Locations">
</p>

Very similar to the very first visualization, the was also one of the early created visualization in the analysis. The dots on the map represent the areas where bikes are being dropped off and are sized and colored by the total count. When comparing the starting and ending location maps, it looks like most rider ending locations are similar to popular starting locations. Bikers may be renting across town for the inital parts of the day and ending their rides at those initial destinations. At the end of the days, those same riders are likely renting the bikes to return back to where the were originally at the beginning of the day. 


## Summary: 
Overall, the analysis from the Citibike Bikeshare Data from NYC was very beneficial for analysis on applying that same kind of business in Des Moines. I believe Des Moines has very good potential for success. It was decided that bikeshare locations could be prioritized based off popular commuting areas between work and home as well as fun places that tourists could enjoy or those same locals during the weekends. More males are likely to subscribe to the business if it replicates trends in NYC; however, an attempt could be made to reach out to females by providing more feminine-appealing bike options that may intrigue them to be more active than they are in NYC.


<b>Two additional suggested visualizations for further analysis with the current dataset are:</b>
1. I would create a calculated column that would check if the lat/longs for the start location and end location are the same to see the count of trips that are round trips vs one-way. This could also be done by seeing if the Starting Station Id and Ending Station Id's are equal. I believe NYC would have way more one-trip riders than round trip if the conclusions made from the above visualizations are accurate.

2. A final one I might look at would be a final look into gender analysis. Since this is of particular interest to the investors, I would map both the lat/longs for start and end locations in different visualizations, color the locations by gender, and size them by count of rides. My guess is you would see certain locations where only males start and end at or maybe more populare locations for females.

<b>One visualization that would be a bonus if the data was available would be:</b>
1. The type of bikes i.e bmx, EV, women cruiser, mountain bike, etc to is which appeals more to men than women. If there is a deficient supply of bikes that women are more likely to rent, adding more inventory of those types of bikes could help boost sales numbers for females. Bike color with this data could also be beneficial.
