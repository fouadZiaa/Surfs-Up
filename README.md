# Surfs-Up
Mod 9 Surfs Up Challenge

Environment and Software:
 - **Python**
 - **Jupiter Notebook**
 - **PostxQL and PgAdmin**

Software:
   -  **SQLlite**   
   -  **SQL** 
   -  **Flask Web Server**


## Project Overview
This analysis requires a quick build, quick turnaround data frame that pulls information from available Hawaiian Weather websites.  

### Purpose  
The purpose of this analysis is to help W. Avy, a famous surfer and investor make important business decisions about opening an ice cream 
shop with surf gear, called "Surf n' Shake Shop" on the island of Oahu.  The location is important because climate can vary on the island.  W. Ivy 
wants to be prepared by knowing weather history and patterns in the area where the shop might be located. A perfect place for the shop is where 
there is the right balance of warm temperatures and sunny days throughout the year.  The data-driven decisions that Avy will make, will be 
based on temperature and rainfall for the past 7 years from 2010-2017, specifically June and December. These 2 months have a big enough gap in between to ensure that weather conditions are good year-round.   

The analysis consists of 2 parts:   
 - Temperature Statistics analysis for June and December for 2010-2017.
 - Rainfall analysis for June and December for 2010-2017.

### Results
The analysis focuses on the temperature and rainfall from six different weather stations in Oahu, HI from 2010 thru 2017 for the months of June and December.


The first 2 charts show the statistics for June and December – tobs   

1.	**Data**
     -	There are less data points for December (1517 data points) than June (1700 data points).
2.	**Dispersion of the data**
     -	Temperatures are more spread out in December 
     -	June’s mean is 79.94 F and the median is 75.00 F.
     -	December’s mean is 71.04 F and median is 71.0 F.
<p align="center">
   <img width="300" height="300" src="Resources/june temps.png">
</p>   
<p align="center">
<p align="center">
   <img width="300" height="300" src="Resources/dec temps.png">
</p>   
<p align="center">
Tables showing June and December temperature Statistics 
</p>

###  Comparison of the Rainfall for June and December:
The analysis focuses on the temperature and rainfall from six different weather stations
On Oahu, Hawaii from 2010-2017 of June and December.  

1.	**Data**
     -	There are less data points for December again (1405 data points) than June (1574 data points).
2.	**Dispersion of the data**
     -	Rainfall quantity is more spread out in December than June.  
     -	June’s mean is 0.13 inches and the median is 0.02 inches.
     -	December’s mean is 0.21 and median is 0.03.
     -	Maximum rainfall in December is 6.42 inches and 4.43 in June. 
     -	Minimum rainfall in December is 0 inches and 0 inches in June too.   
 <p align="center">
   <img width="300" height="300" src="Resources/June Precip.png">
</p>   
<p align="center">
 <p align="center">
   <img width="300" height="300" src="Resources/Dec precip.png">
</p>   
<p align="center">
Tables showing June and December Precipitation Statistics 
</p>

### Summary 
The data frame tables above give us a quick view of the weather in area, but to fully understand the trends, additional
formats and analysis can be helpful.  



### 2 Additional Queries and Charts - Box and Whisker Plots to Visualize the Statistics 
The analysis focuses on the temperature and rainfall from six different weather stations.  

The first **box and whiskers chart** shows how the mild and steady temperatures are year-round. There is very little
distribution of data and very few outliers.   
<p align="center">
   <img width="400" height="350" src="Resources/temp whisker.png">
</p>   
<p align="center">
Box and Whisker plot showing June and December Temperature Statistics 
</p>
 
The second **box and whiskers chart** is impacted by the outliers.    Additional information is needed to really get the the facts.  

<p align="center">
   <img width="400" height="350" src="Resources/precip whisker.png">
</p>   
<p align="center">
Box and Whisker plot showing June and December Precipitation Statistics 
</p>



The following **Line Chart** provides a better idea of seasonal Precipitation for both June and December.  Avy can make some smart decisions
from this compilation of summaries and charts.  In 2010 there was a rare case of above average rainfall, however in years beyond,  
precipitation leveled out and was very consistent from 2011-2017.  
<p align="center">
   <img width="700" height="300" src="Resources/Avg Precip Line Graph.png">
</p>   
<p align="center">


