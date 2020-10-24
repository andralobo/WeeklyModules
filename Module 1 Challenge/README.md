# Kickstarting with Excel

## Overview of Project
Louise organizes fundraisers and would like an analysis to be completed to understand how different fundraisers performed based off their launch date and fundraising goals.  Data for all the past fundraisers is included in the Kickstarter_Challenge excel file. This file includes all the necessary data and will be used to complete an analysis and provide a written report with findings along with visualizations.

## Purpose
The purpose of this analysis is to find out what makes fundraisers successful to help Louise plan more successful fundraisers in the future.  By comparing outcomes based off launch date and by goals we will be able to determine the best date to plan a fundraiser along with the goals amounts that had the best performance. 

## Analysis and Challenges
Using the data in the Kickstarter_Challenge excel file two sets of data were created to be used for the analysis. 
1.	Theater Outcome vs Launch Date <br>
For this analysis we modified the data and the “Date Creation Conversion”, “Parent Category” and “outcomes” were pulled into a pivot table and grouped by month.  This shows the number of successful, failed and canceled fundraisers by month.  By creating this chart we are able to filter the results by year and by Parent Category so the results can be compared by years and other Categories. The chart and graph below shows the outcome for all Theatre fundraisers year to date broken down by month. By grouping the fundraisers by their month of launch date we were able to see which months had a better success over the months that had more failures and cancellations.  

<img src="https://github.com/andralobo/Module1-Challenge/blob/main/Outcomes_vs_Goals_Data.png?raw=true"> 
<img src="https://github.com/andralobo/Module1-Challenge/blob/main/Outcomes_vs_Goals_Data_Data.png?raw=true"> 

2.	Outcomes Based on Goals<br>
For this analysis we used the fundraising Goal value and broke it down by the number of successful, failed and canceled fundraisers for the subcategory plays.  The data was grouped by goal ranges so it was easier to display the results.  The data was filtered to only use Theatre fundraisers so the results would represent only Fundraisers that would be in the same category. The percentages for each of the outcomes were calculated so that the success, failure and canceled rate is better represented. Below is a chart that was created to show the goal ranges and the number and percentage of successful, failed and cancelled fundraisers.

<img src="https://github.com/andralobo/Module1-Challenge/blob/main/Theater_Outcomes_by_Launch_Date_Data.png?raw=true"> 
<img src="https://github.com/andralobo/Module1-Challenge/blob/main/Theater_Outcomes_by_Launch_Date.png?raw=true"> 

### Analysis of Outcomes Based on Launch Date
The months with number of successful fundraisers was May and June and those months also had the higher number of failed fundraisers. If you calculate the success rate for those 2 months had the highest success rate overall and that is the trend across all categories not just for Theatre Fundraisers.
The results show that December had the lowest number of successful fundraisers and the highest rate of failed fundraisers.  
The number of canceled fundraisers in January is very high compared to the rest of the months.

### Analysis of Outcomes Based on Goals
There were no canceled fundraisers in this dataset.  The most common goal amount as in the range of 1000 to 4999 and there were no cancelled fundraisers in this dataset.  The fundraisers with their goal set less than 1000 and from 1000 to 5000 had the highest success rate and the lowest failure rate.
 
### Challenges and Difficulties Encountered
When reviewing the goals for all the theatre fundraisers there was a cancelled event (id 2960) that had a goal of 30 million which was significantly higher amount than any other fundraiser.  This could be an error or the reason the event was cancelled

## Results

### Conclusion based of Outcomes based on Launch Date
Louise should plan future fundraisers for May and June to have a successful fundraiser because they show to have the highest number of successes.
Fundraisers should never be planned for December because they have the lowest number of successes and defiantly not in January because their successes are low and the cancelations are the highest.  

### Conclusion based off Outcomes based on Goals
Louise should plan her fundraisers with a goal ranging from 0 to 4999 or from 35000 to 44999 because those ranges have the highest success rate.  

### Limitations of this dataset
-	Demographics of the donors to determine who to target
-	Cities of the fundraisers to determine the best location for a fundraiser
-	There wasn’t enough data for the Outcome based off goals table.  The majority of the fundraisers had a - goal from 0 to 14999.
-	The reason for the failures would be helpful to determine why fundraisers fail.
-	It the organizer the fundraiser to see that has any impact of the outcome

### Other possible tables and/or graphs that could be created
-	Creating a chart based off the country Louise was planning on organizing her fundraiser to see if that had any impact


