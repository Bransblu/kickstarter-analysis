

# Kickstarting with Excel

## Overview of Project

Performing analysis on Kickstarter data to discover trends from 2009-2017

### Purpose

Determine how different campaigns fared in relation to launch dates and funding goals. The project includes creating and displaying visualization for **Outcomes Based on Launch Date** and **Outcomes Based on Goals**. The purpose of this data is to learn why some Kickstarters succeed and fail.


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Pulling both the outcome data and launch data from the worksheet, a PivotTable and chart were created. This was to narrow down the relationship between when a campaign was launched and whether the campaign succeeded, failed, or was canceled. The table and the chart helped visualize the data.

![Launch_Pivot_Table.png](https://github.com/Bransblu/kickstarter-analysis/blob/main/Images/Launch_Pivot_Table.png?raw=true)

![Theater_Outcomes_vs_Launch.png](https://github.com/Bransblu/kickstarter-analysis/blob/main/Images/Theater_Outcomes_vs_Launch.png?raw=true)


### Analysis of Outcomes Based on Goals

Goal ranges were implemented to organize and sort goal data in relation to outcomes. The goal ranges where set from less than $1000 to over $50,000, with 10 ranges in between. The counts of successful, failed, canceled, and total outcomes were displayed in relation to goal ranges. In addition, the percentage of successful, failed, and canceled campaigns were calculated to better analyze the trends.

![Outcomes_vs_Goals.png](https://github.com/Bransblu/kickstarter-analysis/blob/main/Images/Outcomes_vs_Goals.png?raw=true)


### Challenges and Difficulties Encountered

The specific challenges presented were mostly technical and human error. There were challenges faced when organizing data for **Outcomes Based on Goals**, specifically referring to pledge data instead of goal data. This is was due to human error. Another challenge during the project was creating rows in the middle of the spreadsheet instead of adding at the end, ultimately creating incorrect referrences to rows.

![Screenshot excel2.png](https://github.com/Bransblu/kickstarter-analysis/blob/main/Images/Screenshot%20excel2.png?raw=true)

* The $D:$D range (goal row) was originally set to $E:$E and displayed incorrect data. 
* UPDATE: Didn't initially include "play" subcategory into COUNTIFS function.


## Results

- **What are two conclusions you can draw about the Outcomes based on Launch Date?**

Succuessful campaigns for the theater category were the most volatile based on launch dates. The max value for successful campaigns occured in May and June (111 and 100). The minimum value for successful campaigns occured in December (37). This data shows that the most successful launch dates occur from April through July. This data also illustrates that canceled Kickstarters have little or no correlation with launch date. Failed Kickstarters follow a similar trend with successful campaigns.

- **What can you conclude about the Outcomes based on Goals?**

There are some clear trends regarding campaign outcomes and the relation to campaign goals. First, the greater the goal amount, the lower the successful outcomes were. Successful outcomes were 71% at a goal less than $1000 while the successful outcomes were only 19% at $50,000 or greater. Failed outcomes increased with the greater the goal amount. Failed outcomes occured at a 25% rate at less than $1000 while occuring 58% of the time with a goal of $50,000 or greater. 

- **What are some limitations of this dataset?**

Outliers hold back the data. For example, the top pledge was 3Doodler for $2,344,134 while the following top pledges didn't even equal $2,000,000 together. On the other side of the data, the bottom 400 pledges are all 0. The currency and country data helps avoid incorrect exchanges, but the data could easily be miscalculated if comparing two different currencies without acknowledging the difference.

- **What are some other possible tables and/or graphs that we could create?**

A table showing the correlation between a campaign being designated as a staff pick vs. a spotlight campaign in relation to outcomes would be a valuable tool to see the impact of those designations. Another possible table/chart combination could include a deeper dive into technology subcategories to determine which were the most successful and profitable campaigns. A chart showing the backer count, pledge, and average donation could help show more trends. 

----
















