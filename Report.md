# Kickstarting with Excel

## Overview of Project
An analysis to determine to what extent a campaign's success is contingent on it's launch date and fundraising goal. 
### Purpose
To analyze the relationship between a campaign's launch date and funding goal on it's overall success. 
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
![Outcomes Based on Launch Date](https://github.com/nleva25/Kickstarter-Analysis/blob/main/Resources_for_Challenge/Theater_Outcomes_vs_Launch.png)
The data in the chart plots the number of successful, failed and canceled theater campaigns per month of launch. The analysis tries to determine if there is a relationship between the launch date of a theater campaign and it's overall fundraising success. The data in the chart has been filtered by the campaign parent category (theater) from the Kickstarter dataset and displayed during the month of the campaign launch date. While the number of failed and canceled outcomes appeared to be relatively consistent across all months with no clear trend, the number of successful campaigns seemed to peak in May with a slow and steady decline throughout the rest of the year.  
### Analysis of Outcomes Based on Goals
![Outcomes Based on Goals](https://github.com/nleva25/Kickstarter-Analysis/blob/main/Resources_for_Challenge/Outcomes_vs_Goals.png)
The data in the chart displays the percentage of total successful, failed and canceled campaigns according to specific fundraising goal intervals. The analysis tries to determine if there is a relationship between the fundraising goal for each campaign and it's overall success. The data in the chart has been filtered from the Kickstarter dataset to display the campaign outcome (successful, failed, canceled), goal amount (based on intervals found on x-axis) and subcategory (plays). Once the total amount of campaigns matching **each** of this criteria was tallied, it was displayed as a percentage of total successful, failed and canceled campaigns and plotted according to it's respective fundraising goal interval. 
### Challenges and Difficulties Encountered
Challenges that could arise during this analysis include: 
1) Incorrect data ranges when displaying Pivot Charts
2) Incorrect Pivot Table organization, filters, headers
3) Improper Excel function syntax when sorting Outcomes based on Goal data, incorrect criteria ranges
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1) There doesn't appear to be a trend between a campaign's launch date and whether or not it will fail or be canceled. 
2) Most successful campaigns were launched in May with a steady decline througout the rest of the year (except for a slight uptick in October). If you would like to launch a successful campaign it would be best to start it in May. 
- What can you conclude about the Outcomes based on Goals?
1) The data appears to suggest that the higher the fundraising goal, the more likely the campaign is to fail. Similarly, the more modest the goal, the more likely the campaign will be a success! 
- What are some limitations of this dataset?
1) There are some large fundraising goals for some campaigns, which may skew an average figure
2) Most of the data belongs to only 2 countrys: US and GB
- What are some other possible tables and/or graphs that we could create?
1) A graph analyzing the average amount pledged per backer per subcategoy to determine if there is a more popular subcategory.
2) A graph analzying the fundraising goal per Parent Category to determine which is the most costly category. 
