# Pyber_Analysis
## Background
You’ve been asked by your CEO to create an overall snapshot of the ride-sharing data. In addition to your scatter and pie charts, she would like to see a summary table of key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type. <br />
## Summary Data Frame Analysis
![Summary Dataframe](https://github.com/RudyR32/Pyber_Analysis/blob/master/analysis/Fig9.png) <br />
Above are the summary statistics of the the 3 city types(Urban, Suburban and Rural). As population density decrease the number of rides decrease 1625 in urban citys to 125 in rural citys.  Similarly and number of drivers also decreases from 2405 in urban cities to 78 in rural cities.  Conversely, the average Fare per Ride and the average Fare per Driver both increase as the population density decreases.  These seem to be correlated because in an ecosystem where the ratio of rides to drives is higher you would expect rides to be more expensive than an ecosystem where there are actually more drivers than rides to be given.   <br />
Note:  In every case suburban cities slotted in between urban and rural as would be expect.<br />
Extra:  While not part of the challenge I believe that the below graph does a good job of showing the correlation between the the city type/size and the number of rides and average rate.<br />
![Bubble Chart](https://github.com/RudyR32/Pyber_Analysis/blob/master/analysis/Fig1.png) <br />
## Multiple Line Graph Analysis
![Multiple Line Graph of Weekly Fares](https://github.com/RudyR32/Pyber_Analysis/blob/master/analysis/Fig11.png) <br />
The above figure gives a visual representation of the total weekly fares between January and April in the 3 city types(Rural, Suburban and Urban).  Urban cities are by far the largest total fare producers with there total weekly fares peaking around $2500 verses ~$1400 in suburban cities and ~$500 in rural cities.  For comparison sake this equates being urban weekly fares being about 2x those of suburban cities and between 5x and 10x that of rural cities depending on the week.
<br />
## Additional Implications of the Analysis
Without having additional data it is not possible to fully understand all of the factors that go into driver and rider participation.  An example of an additional peice of data that I would like to explore are the durations of the trips.  I would like to make that caveat before I discuss the implications of my findings.  That being said here are the implications of my analysis.  From the Summary Dataframe, the suplus of drivers in urban areas is likely driving down the average fare and inversely the shortage of drivers in rural areas is likely driving up fares in those areas.  From the Multiple Line Graph, there is a peak in Februray week 3 that is consistent across all city types.  It is important that we understand what factors caused this and assess what promotional or non-promotional activities that we can do to captural this level of success in the future.
<br />
## Areas for Future Exploration
In addition to what was mentioned above additional areas that should be explored going forward are:   1. What times during the day riders are using our services, 2. What the affects of increasing and decreasing the fare rate are on driver and rider participation(I sepeculate driver participation is more elastic than rider participation).
## Pyber_Challenge File 
This file contains the code I used to preform this analysis.<br />
![Pyber_Challenge](https://github.com/RudyR32/Pyber_Analysis/blob/master/Pyber_Challenge.ipynb)
