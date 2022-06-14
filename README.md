# Kickstarting with Excel

## Overview of Project

### Purpose
Louise, an up and coming playwright, wants to start a crowdfunding campaign to help fund her play *Fever*. She is interested in understanding what factors can make the campaign a success.Within this analysis we will be exploring cowdfunding data to see if there is relationships between outcomes for different campaigns and individual goals as well ad the outcomes based on the campaign launch dates.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
From the Crowdfunding data, the Launch Date of all the campaigns within the dataset were stratified by monthes of the year from (2009 to 2017) to identify any trends for successful, failed or canceled campaigns present throughout the year.

-Within the last 8 years, there were 1,369 crowdfunded theater campaigns started (active campaigns without an end date were excluded).
* 839 were successful.
* 493 failed.
* 37 were canceled.

A line chart was generated to visualize the outcomes by month.

![Theater Outcomes Based on Launch Date Line Chart](https://github.com/mcgibbenyd1/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
To understand whether the campaign goal influenced the outcome of the campaigns the data was categrorized by outcome of the campaign and by the campaign's goal.
* Outcomes of campaigns for plays (Successful, Failed, and Canceled) were categorized within 12 different goal ranges

The results were graphed on a line chart and displayed as a percentage

![Outcomes Based on Goals Line Chart](https://github.com/mcgibbenyd1/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

* The analysis of Outcomes Based on Launch Date reviews if campaigns were successful or not based on starting the campaign during a particular month of the year during the year range, 2009 to 2017. This analysis should be visualized as a pivot chart rather than a line chart. It should be reviewed dynamically with ease of filtering rather than the requirement of an additional breakdown of the dates in order to extract the month of the launch date. Additionally, line charts within this analysis would require additional work filtering in order to graph a separate year of data. 
* The analysis of Outcomes Based on Goals posed a challenge when filtering by the goal ranges based on particular criteria and only with play campaigns of certain goal amounts.  

## Results

#### What are two conclusions you can draw about the Outcomes based on Launch Date?
1. The month of May is the best month to begin a Theater crowdfunding campaign to have the historically best chance to meet your goal successfully.
2. In every month of the year besides December there has been more successful Theater campaigns started than failed and canceled Theater campaigns.

#### What can you conclude about the Outcomes based on Goals?
1. There is at least a 50% chance of having a successful campaign with a campaign goal set less than $20,000 and/or between $35,000 to $44,999. 

#### What are some limitations of this dataset?
* There is a limited description of what all the variables represent. Every successful campaign has a value of TRUE under Spotlight.
* The timing the data was pulled is assumed to be 3/15/2017 based on the difference of oldest live campaign and the most recent failed campaign. Possible skewed data for early monthes. Only the years 2009 to 2017 are represented.
* The campaigns all have varying timespans of active campaign time.
* Campaigns are denoted by ($) but the currency varies by country and is not specified if the campaign goal was converted in relationship to the currency conversion with currency ranges being possibly skewed based on exchange variations. 
* Backer donation times not specified for an understanding of popular donation monthes

#### What are some other possible tables and/or graphs that we could create?
1. Number of campaign backers per Campaign Parent/Subcategory
2. Origin of Campaign by Campaign Parent Category 
3. Campaign Outcome based number of campaign backers 
4. Campaign Outcome based on length of campaign 
