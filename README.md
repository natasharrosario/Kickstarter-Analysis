# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this challenge was to help the client, a playwrite, who wants to start a crowdfunding campaign for her play determine what specific factors make these types of campaigns successful. This was done by organizing, sorting, and analyzing data from previous campaigns in Excel to help the client model her own campaign to other successful ones in the same category. 

This project specifically looked at the outcome of a campaign (i.e. successful, failed, or cancelled) in relation to the campaign's launch date and fundraising goal, as well as what category and subcategory each campaign belonged to. There is some additional research on plays shown at the Edinburgh Festival Fringe that the client requested information about.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To analyze the outcomes of different campaigns based on their launch date, a pivot table was created that showed the number of successful, failed, cancelled, and total number of campaigns for each month from 2009 to 2017, filtering for campaigns in the "theater" category. A line chart was then created in order to visualize the results
 based on the campaign's launch date and outcome. 
 
 <img width="770" alt="Theater_Outcomes_Based_On_Launch_Date" src="https://user-images.githubusercontent.com/113553238/193124022-795e50fb-7a28-4de0-92e6-cf8ae5c04843.png">

### Analysis of Outcomes Based on Goals

To analyze the outcomes of different campaigns based on their fundraising goal, an Excel worksheet was created to display the number of successful, failed, cancelled, and total number of campaigns for different dollar-amount ranges of the campaigns' fundraising goals, as well the percentage of successful, failed, and cancelled campaigns in each range, filtering for campaigns in the "plays" subcategory. A line chart was then created in order to visualize the results based on the campaign's fundraising goal and outcome.

<img width="895" alt="Play_Outcomes_Based_On_Campaign_Goals" src="https://user-images.githubusercontent.com/113553238/193124114-58545df6-372f-4b0f-8bbc-11dd2b71d7d7.png">

### Challenges and Difficulties Encountered

The original dataset is a bit large, so keeping everything organized while still being able to understand what the data is actually saying could present a challenge if not approached with an attentive and refined eye. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Theater campaigns are more likely to be successful when launched in May or June, after which the success rate will continue to fall until March of the next year. Campaigns are most likely to fail when launched during the holiday season, especially during the month of December. 

- What can you conclude about the Outcomes based on Goals?

Play campaigns are most likely to succeed when the fundraising goal is kept under $5,000, and most likely to fail when the fundraising goal exceeds $45,000.  

- What are some limitations of this dataset?

A limitation of this dataset is that it is highly quantitative. While we can see how well campaigns did based on fundraising goals, pledges, launch date, country, etc., it is difficult to draw conclusions about why the campaigns were or were not successful, or what influenced backers to make certain pledges. We risk overlooking important behavioral patterns or relationships that influenced the success of failure of certain campaigns. 

Additionally, I do not believe that a line chart is the best method to present data on outcomes based on campaign goals, as line charts are typically used to display data over a period of time. Because, in this case, campaign goals are being measured by dollar-amount ranges rather than by units of time, a graph that displays quantitative ranges, such as a histogram, might be better suited to visualize this data.

- What are some other possible tables and/or graphs that we could create?

To alleviate some of the risk qauntitative data like this poses, it could be helpful to seek feedback from backers explaining their decision-making process and create a table that displays recurring themes for successful and failed campaigns, in order to better understand why they donated certain amounts and for which campaigns. 

It might also be helpful to look more closely at not only the launch date of campaigns, but also their deadlines, in order to determine how long or short of a time the client's campaign should last to achieve the highest rate of success. This could be done by inserting a new column, "Campaign Length", and creating a histogram with ranges to measure campaign length on the x-axis, percentage on the y-axis, and using "successful" and "failed" as two variables to be measured. This information would mirror the table, functions, and graph used in the "Outcomes Based on Goals" worksheet (with the implication that the line chart is substituted with a histogram).
