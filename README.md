# Kickstarting with Excel

## Overview of Project

### Purpose: The Purpose of this project is analyze the outcomes of Kickstarter campaigns based upon the launch date and the goals. We are hoping to inform Louise of any trends from previous Kickstarter campaigns that might help guide her in how to best utilize Kickstarter campaigns in the future. We will be using features of Microsoft Excel, such as pivot tables, pivot charts, a variety of formulas, and table-editing features to complete this analysis.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
    - We are viewing the outcomes of theater Kickstart campaigns based upon the month of the year the Kickstarter campaign was launched. We first created a pivot table using our data in the kickstarter worksheet from the dataset Louise provided us. Using that pivot table, we filtered the Parent Category to theater, used outcomes as the columns and launch date months as the rows. We then created a chart based upon our pivot table which displays the amount of successful Kickstart campaigns relative to the month they were launched in. That chart is included below
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/96350388/147893802-1b126bc6-d480-4980-bbd0-ca4491bfef82.png)

### Analysis of Outcomes Based on Goals
    - We are viewing the outcomes of plays Kickstarter campaigns based upon the dollar amount the campaign's goals were set at. We were provided 12 ranges to sort the goals within. The first range was for goals less than $1,000, the next range was for goals between $1,000 - $4,999, then each new range started with the previous range's maximum threshold as the minumum and the maximum was $4,999 greater than the minimum. The last range was for any goal larger than $50,000. We then used COUNTIFS and SUM formulas to determine the number of Kickstarter campaigns for plays that were successful, failed, or canceled, then used the total of all Kickstarter campaigns for plays to determine percentages of the campaigns that were successful, failed, or canceled. We created a chart to represent the percentage data
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/96350388/147893792-ebed19e6-921b-4a26-9a0f-fa355eb1a61f.png)

### Challenges and Difficulties Encountered
    - When creating the pivot table to analyze the Outcomes Based on Launch Date portion of this assignment, it took a few tries moving around variables on the chart to find everything's proper placement
    - For the Outcomes Based on Goals section, I first was under the impression I had not entered my formulas correctly for canceled data, as it was showing up as 0 for all entries. I verfied by filtering the actual dataset and comparing my work to the chart shown in the Challenge 1 Assignment
    - Quite frankly, this is my first time ever using github and I am nervous about every button I click on there hoping to ensure this Challenge is uploaded correctly

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - Conclusion 1: Most successful theater Kickstarter campaigns were launched in May, followed by June and July, respectively. Late spring and early summer seem to be the best time to launch a Kickstarter campaign for theater projects
    - Conclusion 2: After May, the number of successful Kickstarter campaigns for theater projects drops month after month (with October being the only exception) for the remainder of the year. Therefore, launching a campaign after May can likely expect a lower success rate the later in the year the launch date is after May.

- What can you conclude about the Outcomes based on Goals?
    - Generally speaking, the higher the goal of the Kickstarter campaign for plays, the more likely the campaign is to fail. The exception to this comes from campaigns with goals between $25,000 and $39,999. The aforementioned trend reverses for that goal range, so as campaign goals increase from $25,000 to $39,999, the success rate increases.
    - Strictly speaking, Kickstarter campaigns for plays have succeeded more often than failed when the goals were within the following ranges: $0 - $19,999 and $35,000 - $44,999. Kickstarter campaigns for plays have failed more often than succeeded when the goals were within the following ranges: $20,000 - $34,999 and any goal greater than $45,000 

- What are some limitations of this dataset?
    - This data set has a lot of variables, which makes it difficult to draw conclusions with certainty, as you need to run statistical analysis with many of these variables in order to know which variables may or may not actually be impacting your data of interest
    - There is a mix of qualitative and quantitative data in the set, and the data needed a lot of cleaning up before some general analyses could be run

- What are some other possible tables and/or graphs that we could create?
    - We could analyze successful vs unsuccessful campaigns on a yearly basis, to see if there are trends year-to-year (i.e. maybe Kickstarter became a more or less popular crowdsourcing platform over the years)
    - Outcomes vs Countries could have a good amount of interesting data which could help focus campaigns locally in different countries
    - There are an abundance of different Parent Categories vs Subcategory charts/tables that could be created
