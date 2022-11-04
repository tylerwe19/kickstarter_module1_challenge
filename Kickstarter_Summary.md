# Kickstarting with Excel

## Overview of Project

This analysis of the Kickstarter data visualizes the success & fail rates of theater and play campaigns. It observes the success & fail rates over time and how success & fail rates of campaigns evolve across various goal ranges.

### Purpose

This analysis will help Louise compare the performance of her play, Fever, to the performance of other plays and theater productions. This analysis will provide insight into her interest of how success and fail rates change over time and goal range. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Below is a visualization showing the monthly number of successful, failed, and canceled theater campaigns from 2009 to 2017. You'll notice:
 1. Theater campaigns typically experience the most success during May. In fact, April-July is a stretch of months where campaigns see higher success rates.
 2. During the fall and winter, especially beginning at October, theater campaigns experience less success. Surprisingly, February is an abnormal winter month where theater productions have historically reaped more success. Additional research should be conducted to understand why February experiences this success.

![Theater_Outcomes_vs_Launch.png](https://github.com/tylerwe19/kickstarter_module1_challenge/blob/main/resources/Theater_Outcomes_vs_Launch.png)
---

### Analysis of Outcomes Based on Goals

Below is a visualization that shows success/fail rates of play campaigns across various ranges of goals established. 

![Outcomes_vs_Goals.png](https://github.com/tylerwe19/kickstarter_module1_challenge/blob/main/resources/Outcomes_vs_Goals.png)
---

 * Campaigns that set goals of less than $15K tend to experience more success than campaigns that set goals above $15K. The success rate is higher than the fail rate for campaigns that set goals between $35K-45K; however, the number of campaigns in this goal range is very small. There are hundreds of play campaigns that set goals of less than $15K and a majority succeed in attaining their goal, which leads to the confident conclusion/recommendation that it is best to set goals below $15K.

To dive deeper into the data please go to the Kickstarter Excel Workbook:
[kickstarter_challenge](https://github.com/tylerwe19/kickstarter_module1_challenge/blob/main/Kickstarter_Challenge.xlsx).

---

### Challenges and Difficulties Encountered
#### Challenges
 * I had a little difficulty initially figuring out the COUNTIFS function to count the number of campaigns per Goal Range. 
 * I had some challenges figuring out exactly what I wanted to conclude about the data. The Theater Outcome Based on Launch Date graph was able to show the months that had the highest volume of theater campaigns, but it could not help us compare success and fail rates. In order to determine the most successful months, I had to create the success/fail rates off to the side to determine effective months.

#### Limitations of this Data
 * The data is a little stale, with the most recent End Date occurring in 2017 which is 5 years ago. It would be nice to confirm the observations above with more recent data.
 * This data does not have demographic information about the backers or intended backers. It would be interesting to have data about the backers who pledged money for each campaign and compare Louise's targeted backer for Fever to a theater production that was most similar to her play.

### Other Possible Tables/Graphs
 * I would be very interested in revisualizing the "Outcomes Based on Goal" graph. I would like to see a Donut Chart for each Goal Range, which would enable us to see the Success and Fail Rate for each Goal Range and in the center would display the total number of campaigns per Goal Range. The number of campaigns above the Goal of $25K become very small leading me to hesitate about drawing conclusions on this data. There are hundreds of campaigns below the Goal of $25K which gives me more confidence in drawing conclusions about these campaigns.
 * I think it would be interesting to see a clustered bar graph of Avg Donation for each Goal Range and each Goal Range would be broken by success/fail, so we could see the Avg Donation for Successful and Failed campaigns whithin each goal range. 

---
