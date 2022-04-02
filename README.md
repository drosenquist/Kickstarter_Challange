# Kickstarter_Challange
Analysis of theater Kickstarter campaigns

# Overview of Project
Comparing theater Kickstarter fundraising campaigns by launch date and success at reaching their campaign goal.

## Purpose
The purpose of this project was to analyze different Kickstarter fundraising campaigns and how they performed based on their launch date and at reaching their fundraising goal. The analysis is to be used to make a recommendation to Louise for future use in determining the optimal time to launch a fundraising campaign that has the highest possibility of reaching its goal.

# Analysis and Challenges

## Analysis
To compare campaign outcomes, a pivot table was created and filtered to view information for theater Kickstart campaigns. A line graph was created using the pivot table, shown below.

### Outcomes Based on Launch Date
The analysis showed that May had the greatest number of successful campaigns with 111 followed by June, July, and August with 100, 87, and 72 successful campaigns, respectively. April and August had nearly the same number of successful campaigns, 71 versus 72, respectively. The number of failed campaigns were nearly the same each month during the May through August period, averaging 50 (rounded) per month compared to 92 (rounded) on average successful campaigns each month.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/101379969/161399565-090e9aaa-f1c3-4783-8156-630f3abef559.png)

### Outcomes Based on Goals
The Kickstarter goals were broken down in 12 ranges. The COUNTIFS function was used to count the number of campaigns that had fundraising goals within the ranges. Then, the percentage of successful, failed, and canceled campaigns were calculated for each of the ranges.

Out of the 1046 theater campaigns analyzed, those that had fundraising goals less than $4999 had the greatest percentage of successful campaigns, 74% on average.  50% to 80% of campaigns that had a fundraising goal between $15,000 and $34,999 failed.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/101379969/161399726-f8cdf24a-e0b9-4fe8-b1f0-bff3ecc21a10.png)


## Challenges
Translating dates to a standard MM/DD/YYY format from an EPOCH/UNIX time stamp was a new process for me. I’ve worked with date and times in a single field before in Excel and on numerous occasions have had to separate the two. It wasn’t a completely new process for me but the formula used to translate the EPOCH/UNIX time stamp was new to me. 

# Results
The best time to launch a Kickstarter campaign is late Spring/early Summer, with May being the best month followed by June and July. December was the worst month with nearly just as many campaigns failing as those that were successful. 

Plays with a fundraising goal of under $5000 had a high percentage of meeting their goal, 76%. 

The data set lists fundraising goals in their local currency. A fundraising goal of 1,000 U.S. dollars is not the same as 1,000 British pounds sterling. Also, currency rates fluctuate overtime and some of the data analyzed is from 2009 and not adjusted for inflation.

The analysis of outcomes based on goals is categorizes the outcomes by month, but doesn’t break down the results by year. There could’ve been some years were more campaigns failed than were successful overall due to other circumstances like global economic downturns that resulted in people being less likely to commit to fundraisers. To see if the outcomes based on goals holds true from year to year, it might be helpful to repeat the same analysis (using both tables and charts to analize and present the data) but on a yearly basis to see if it uncovers any additional insight. Also, comparing types of plays to see if a type or types of plays are more successful at meeting their fundraising goals than others, which can be done with a pivot table and presented using a graph, could be helpful in determing what kind of play to launch or determine chance of success of meeting funraising goal.
