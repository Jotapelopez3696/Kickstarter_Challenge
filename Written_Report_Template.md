# Kickstarting with Excel

## Overview of Project
This is a Data Analysis of Kickstarter campaign of theaters and plays. Includes the graphics and tables of two possible variable that affect the outcome of the campaign: the goal amount and the launch date.

### Purpose
The main purpose of the challenge was to introduce us in the word of excel and, management of data and visualization of our findings. The way was to analyze the Theaters campaigns of kick starters to achieve a decent analysis In order to do so, we began with two hypothesis.

- Does the outcome of the project depends on the launch date? 

- Does the outcome of the project depends on the goal amount? 

We filter and present our data looking for those findings.

## Analysis and Challenges

The first step was check if there was a tendence in the outcomes based on the launch date. For this make an analysis base on the launch date and cluster it by months in order to check for seasonality. 


The second step needed an auxiliary column that cluster the kick starters by a range of amount goal. This was hard because there was no way to be automatized so it was written one by one. Next, using the count.ifs function I count the number of projects successful, failed and canceled clustered by the range. Then with simple statistics I check the percentage for each outcome and each level of range.


### Analysis of Outcomes Based on Launch Date
! [Excel Outcomes by launch date](image_1.PNG)
The best month for star a kickstarter was June and in all the months there was more succesful campaigns. The worst mont was december , in that month only 2 more campaigs were succesful tan failed.

### Analysis of Outcomes Based on Goals
! [Excel Outcomes based on goal](image_2.PNG)
In this part the unit was percentage of projects rather than a simple count, this give us more faculty to compare the outcomes. We can see a negative marginal rate of proportion as the goal increases in the successful projects. This remains until the range of 15000 to 19999 where the ratio was the same. After that we can observe how the gap increase and reach a max. pont in the range of 25000 to 29999. After that there is more successful campaigns and reach a local maximum on successful campaign in the ranges of 35,000 to 39,999 and 40,000 to 44,000. At the end of the data the gap increases, and we see a great disparity of failed and successful campaigns, were there ir more failed projects. 

### Challenges and Difficulties Encountered

There was no a challenge bout I would like to incorporate more control variables. We can´t conclude that the month or the amount are causality for the outcomes. Maybe is a combination of both or maybe more variables. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
June is the best month and december the worst

- What can you conclude about the Outcomes based on Goals?

The best is low budget campaigns or go directly to the range of 35,000 to 45,000. More than that increase the failure ratio
- What are some limitations of this dataset?
Quality variables that explai us some qualitative facts of the campaigs, algo more quantitative control data to increase power in our analysis.

- What are some other possible tables and/or graphs that we could create?

Same kinf of graphics based on the country or the deadline. Also combination of two variables in a bubble chart.

