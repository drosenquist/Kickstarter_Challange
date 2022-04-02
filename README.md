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
The analysis showed that May had the greatest number of successful campaigns with 111 followed by June, July, and August with 100, 87, and 72 successful campaigns, respectively. April and August had nearly the same number of successful campaigns, 71 versus 72, respectively. The number of failed campaigns were nearly the same each month during the May through August period, averaging 50 (rounded) per month compared to 92 (rounded) on average successful campaigns each month. Campaigns that started in the last four months of the year had the

### Outcomes Based on Goals
The Kickstarter goals were broken down in 12 ranges. The COUNTIFS function was used to count the number of campaigns that had fundraising goals within the ranges. Then, the percentage of successful, failed, or canceled campaigns were calculated for each of the ranges.

Out of the 1046 theater campaigns analyzed, those that had fundraising goals less than $4999 had the greatest percentage of successful campaigns, 74% on average.  50% to 80% of campaigns that had a fundraising goal between $15,000 and $34,999 failed.

## Challenges
Translating dates to a standard MM/DD/YYY format from an EPOCH/UNIX time stamp was a new process for me. I’ve worked with date and times in a single field before in Excel and on numerous occasions have had to separate the two. It wasn’t a completely new process for me but the formula used to translate the EPOCH/UNIX time stamp was new to me. 

