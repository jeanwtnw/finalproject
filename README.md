# Exploring airline safety by comparing and analyzing the number of incidents and fatalities for each airline from 1985-1999 and 2000-2014
##### *American Airlines, Delta Air Lines, JetBlue, Thai Airways, All Nippon Airways, and 50 more...*

## Patarathana Wattanawong

I found this data on FiveThirtyEight Github Data Repository. It's labeled as airline-safety.csv, and I downloaded it as a .csv file.  
[https://github.com/fivethirtyeight/data/blob/master/airline-safety/airline-safety.csv]

## Data Interrogation using Google Sheets 

**Summary of Raw Data:** 

![Infographic of Summary of airline-safety.csv](https://i.imgur.com/TBKTs5O.png) 

This infographic shows and explains all the columns of raw data that exist in this .csv file. In order to interrogate these sets of data, I imported them into Google Sheets. Then, I created Pivot tables and applied Filter options in order to form a general sense for which airlines are safe and which ones aren't. 

First, I organized the list of airlines in Google Sheets by sorting them from A-Z to familiarize myself with the data and get a sense of the 55 airlines in this data set. After that, I began to create pivot tables on the number of incidents and fatalities.

Finally, I generated charts based off of data from these pivot tables before beginnning my process of analysis. 





The first line chart that I made is to show a general comparison between the number of incidents, disregarding fatalities, for each airline for the two time periods: 1985 - 1999 and 2000 - 2014. 



![Line-chart showing a comparison between the number incidents between 1985 - 1999 and 2000 - 2014](https://i.imgur.com/QOq0ikA.png)

Based on this chart, I can draw some conclusion that the majority of the airlines listed improved their safety protocols and methods over time because the number of incidents for each airline decreased from the period 1985-1999 to 2000-2014. In other words, the number of incidents of 1985-1999 were greater than the number from 2000-2014. This is with the exception of Egypt Air, Malaysian Airlines and Saudi Arabian Airlines that have had an increase in number of incidents between 2000-2014 in comparison to their numbers from 1985 - 1999. 

Additionally, one other anomaly that should be observed is also Aer Lingus airline of Ireland, which had a significant number of incidents between 1985-1999 in comparison to all the other airlines. This is probably because of some other significant event that was happening between 1985 and 1999 at that time.  



Moving on, in the pivot table that I displayed below, I selected data columns "airline", "number of incidents 1985-1999" and "number of incidents 2000-2014". Then, I applied the Filter option for number of incidents for both time periods to only display values Greater Than or Equal to 14. My reasoning for choosing 14 incidents as a filter is because both time periods stretch over 14 years. Assuming there are no anomalies, these airlines have had more than 1 incident per year. In this aviation business, it is important to put weight on each incident because there are a lot of associated risks that could easily lead to fatalities.                                   

![Pivot table on Google sheets to compare number of incidents between 1985 - 1999 and 2000 - 2014](https://i.imgur.com/ZVcPsmf.png)

From this pivot table, I am able to specifically say that American Airlines, Delta Air Lines and United Airlines have had 14 or more number of incidents in both time periods. It is not to be concluded that these airlines are the least safe out of all the ones listed in the whole .csv file as these three airlines are also considered major airlines, especially for flying domestically here in the States. In addition, it is possible these incidents may not have been as serious as for there to be any fatalities. However, it can be said, though, that these airlines, as frequently as they may provide flights, still encounter incidents that could be because of many reasons like the company's management system or the aircrafts itself. 

To further explore the airline safety, my next pivot table compares the Top 4 airlines with fatality numbers greater than 100 in both time periods. In this pivot table, I chose the columns "airlines", "fatalities 1985-1999" and "fatalities 2000-2014". Then I set the filter for Greater Than or Equal to 100 for number of fatalities. 

![Pivot table on Google Sheets to compare Top 4 airlines with fatality numbers greater than 100 between 1985 - 1999 and 2000-2014](https://i.imgur.com/j0woH2z.png)

The bar-chart below illustrates this pivot table.

![Bar-chart showing a comparison of Top 4 airlines not to fly with based on number of fatalities](https://i.imgur.com/RKB2Ide.png) 

From this data, I recognize that Air India, American Airlines, China Airlines and United Airlines have resulted in fatality numbers greater than 100 in both time periods. Therefore, it can be generally said that these airlines may be considered somewhat unsafe, though there may be other factors to also take into consideration. 

Based on general analysis, American Airlines and United Airlines are the two airlines that have had a higher number of incidents and fatalities than other airlines listed. Since they are both recognized as major airlines, it may also be because they provide more number of flights throughout each year that their number of incidents and fatalities are greater than those of other airlines. 

To form a more accurate conclusion, there could be an investigation into the specific types of incidents, also for when and how each incident occurred. 



To end on a positive note, the poster below shows airlines that rank the highest in terms of the lowest number of incidents and fatalities from both 1985-1999 and 2000-2014.


![Final poster to show the most safe airlines today](https://i.imgur.com/hOhRYFl.png)
