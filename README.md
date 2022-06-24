# bikesharing

## Overview
In this analysis, we explored bike sharing data from NYC company CitiBike. This data was analyzed to determine what is successful about the bike sharing business in NYC and to determine if a similar bike share business would be successful in Des Moines, IA.

## Results
The following are images of the data visualizations performed on the CitiBike data.

This image shows that the peak hours for bike rentals are between 5pm and 7pm. This might be due to the after work commute. There is also a peak in bike rentals at 8am. This might be due to the morning commute to work.
<img width="1125" alt="Screen Shot 2022-06-22 at 4 07 24 PM" src="https://user-images.githubusercontent.com/101693004/175170602-05b6014e-607f-4357-a8fa-911755ed328d.png">

More bikes are rented in the city center of Manhattan than other areas of NY. This is likely due to the larger population in the city and ease of using bikes to get around.
<img width="1132" alt="Screen Shot 2022-06-22 at 4 07 46 PM" src="https://user-images.githubusercontent.com/101693004/175170765-df68410f-637e-4c6f-842e-698ac940cd5a.png">

The most popular trip duration among its users is 5 minutes.
<img width="1126" alt="Screen Shot 2022-06-22 at 4 04 24 PM" src="https://user-images.githubusercontent.com/101693004/175170630-7313f8ee-df58-494a-b24a-bc1d60e38278.png">

With over 1.5 million trips, male users make up the largest portion of user trips. Female users make up roughly 25% of user trips.

<img width="268" alt="Screen Shot 2022-06-22 at 4 05 30 PM" src="https://user-images.githubusercontent.com/101693004/175170640-f57e687a-248a-4d4c-a3a4-7d456f7e8f08.png">

The most common trip duration for males is 5 minutes, while for females it's 6 minutes.
<img width="1138" alt="Screen Shot 2022-06-22 at 4 06 07 PM" src="https://user-images.githubusercontent.com/101693004/175170657-1683ff09-0229-4f24-bb67-ea3f9a10118f.png">

The most popular hours for bike use on Monday through Friday are 7-10am, with rentals peaking between 8-9am, and 5-8pm, with hours peaking between 6-7pm. These hours coincide with the morning and evening commute to work. On Saturday, the most popular hours for bike use are 10am-7pm with bike use peaking from 12-1pm. On Sunday the most popular hours for bike use are 11am-6pm.
<img width="1125" alt="Screen Shot 2022-06-22 at 4 06 27 PM" src="https://user-images.githubusercontent.com/101693004/175170859-e66e4031-b5d3-4aae-bd49-c618446f1a6a.png">

The popular hours of bike use seem to be the same for males and females, but males are using the bikes in much higher numbers than females.
<img width="1130" alt="Screen Shot 2022-06-22 at 4 06 45 PM" src="https://user-images.githubusercontent.com/101693004/175170914-6fdb08e3-07d0-43cf-b9e7-977a1006d9d9.png">

The largest user demographic are male subscribers on Monday, Tuesday, Thursday, and Friday. 
<img width="1135" alt="Screen Shot 2022-06-22 at 4 07 02 PM" src="https://user-images.githubusercontent.com/101693004/175170963-22d020c2-5556-4ca8-be1f-c78ee416fb00.png">

## Summary
We can see from the data visualizations of the CitiBike sharing data, that their biggest user demographic is male subscribers in the more populated city center. The average trip duration is 5 minutes, so it would make sense for bikes to be placed within 5 minutes of popular business and recreational desintations. Also, the busiest time of day for bike rentals are Monday-Friday during the morning and evening commute hours, with peak rentals between 8-9am and 6-7pm. This again shows that bikes should be placed around densely populated areas of business buildings.
Two additional visualizations that I would suggest for future analysis would be the birth year vs the total number of trips, and gender as a color mark to determine what age group and gender is their largest demographic. I would use this information to help determine if Des Moines, IA has a similar age and gender demographic in their city center for their bike sharing business to be successful. Another visualization would be a map of the most densely populated areas of subscribers. You would first need to create a calculated field converting the 'Subscriber' string in Usertype to an integer that can be counted. After that I would create a map and put the subscriber count on the size mark and color mark. I would also put the subscriber count on the detail mark so I can see how many subscribers are using each staring point location. This would be important information because subscribers make up over 3/4 of the CitiBike users, and therefore you want to know what locations your subscribers are using most and try to determine why to try and recreate that in Des Moines, IA.

<img width="1133" alt="Screen Shot 2022-06-23 at 6 43 49 PM" src="https://user-images.githubusercontent.com/101693004/175445706-603783e2-8a8d-483d-a266-15a290688128.png">

<img width="1133" alt="Screen Shot 2022-06-23 at 6 43 20 PM" src="https://user-images.githubusercontent.com/101693004/175445721-9e1c8ee1-b77d-4efb-94e4-6153b3d42aa4.png">


## Tableau Public Link
[Link to Dashboard](https://public.tableau.com/views/NYCCitiBikeChallenge_16558597231940/NYCStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
