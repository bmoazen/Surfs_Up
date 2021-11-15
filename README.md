# Surfs_Up Analysis
# Overview of Analysis
We were tasked with using SQLite to analyze weather data from several stations in Oahu, Hawaii in order to make informed recommendations involving the sustainability of a proposed surf and ice cream shop.  We specifically looked at data from the months of June and December.

## Resources
Data Source: hawaii.sqlite<br />
Software: Python 3.6.1, Visual Studio Code 1.38.1<br />

## Results
The table below shows the five-number summary for both June and December
![alt text](https://github.com/bmoazen/Surfs_Up/blob/main/June%20and%20Dec%20Table.PNG?raw=true)<br />
<br />
Shown below are box plots of temperatures for the months of June and December.<br />
![alt text](https://github.com/bmoazen/Surfs_Up/blob/main/June%20and%20Dec%20Temps.png?raw=true)<br />

## Summary
The average temperature of June is 77 degrees, which is a very desirable surfing temperature as well as a reasonable temperature for ice cream sales.  However, while the average temperature of December is still over 70 degrees, the 25th percentile of temperatures dips into the 60s, which may be too cool for ice cream sales even though there may still be surfers on the beach.  Furthermore, the minimum temperature recorded during December (60 degrees) is well below what many would consider comfortable surfing weather and definitely won't attract many ice cream buyers. Overall, though, since it does look like there would still be sales in December (albeit probably much lower than in peak months), it may be reaosnable to assume this business could be sustainable year-round.<br />
<br />
A multi-year temperature analysis would most certainly help here, as it is not possible to determine if the year shown here is abnormal compared to other years.  Also, average rainfall should also be taken into account, as surfing and ice cream sales would be greatly affected by precipitation, regardless of daily temperature.
 
