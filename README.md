# Module-1-Challenge

## Overview of Project
Louise would like to know how different Theater campaigns fared in relation to their launch dates and their funding goals. 
### Purpose
We want to compare all the theater campaigns and how they did compared to the months they launched. We then want to compare how a campaign did compared to goal $ amount. This will allow Louise to plan out future campaigns with a better chance of success.
## Analysis and Challenges
We compared all the parent category Theater campaigns and whether they were successful, failed, or canceled based on the month they launched their campaign on Kickstarter. We then compared subcategories Plays to see if their was a correlation to the $ amount they were asking for, to whether they were successful, failed, or canceled. The challenges that arose is that we don’t know if their were special deals/advertisements for certain campaigns made by Kickstarter to support theater or plays on their website. We also 
### Analysis of Outcomes Based on Launch Date
The analysis of outcomes based on launch date showed that in May there was a high spike in successful campaigns. The theater campaigns success would slowly go down until September. We can conclude with some level of certainty that if you started your theater campaign in May you would have a much higher success rate then starting in December. We unfortunately do not know the exact reason for this spike but since there is a slow drop off each month after May, we can conclude that this was not a one off occurrence and that the summer is a stronger season to start your theater campaign in. 

<img src="https://user-images.githubusercontent.com/113380751/208989947-a1f25259-8c17-479a-8f02-df214823cee4.png" width=50% height=50%>

### Analysis of Outcomes Based on Goals
The analysis of outcomes based on goals shows that play campaigns with lower goals have a higher chance to be successful then those with higher goals. The graph shows us that until the $15,000 - $19,999 range, successful campaigns were more likely to be successful. The graph going past that however is not as reliable since after the $20,000 - $24,999 range the total number of campaigns in those categories were less then 20, and it is not a large enough sample size to come to a conclusion on if any higher goals are worth doing. We can say everything before that however has some level of relevance with all levels between $0 - $9,999 having over 150 projects recorded, meaning they are much stronger sample sizes and making the data much stronger. I recommend trying to keep your goal below $20,000 as that dollar amount seems to be the threshold for when you have 50% chance to have a successful campaign, and anything larger is less likely to succeed.

<img src="https://user-images.githubusercontent.com/113380751/208989986-8d43deff-47a9-40d1-9e9a-c72d4fd885b3.png" width=50% height=50%>

### Challenges and Difficulties Encountered
During this Analysis, I had downloaded the excel sheet provided to me, but it download correctly and left out many of the play data causing my initial “outcomes based on goals” analysis to be skewed. But after some outside help I was able to get it up and running and transferred my formulas to the corrected data excel sheets. Another difficulty I ran into during the “outcomes based on goals” analysis was not invducing the conditional that it had to be subcategory play for it to be counted. This was a easy fix with the conditional(Kickstarter!Q:Q,"plays").
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The conclusion we can come to is that if you start your campaign in May you are very likely to have a successful campaign. However if you start a campaign in December, you may have less competition for campaign plays, but they are much more likely to fail.
- What can you conclude about the Outcomes based on Goals?

That your goal must be under $20,000 if you want to have a good chance at getting your play funded.

- What are some limitations of this dataset?

The limitations is that the dataset doesn’t include outside advertisements by the campaigns, and it doesn’t include if their were any specials happening on the website that may have enticed people to donate more money.

- What are some other possible tables and/or graphs that we could create?

For a stronger analysis of all the data you may want to look into how being spotlighted may effect your campaign. Another graph that would be much harder to make would be to see if their were any buzzwords that the successful/failed campaigns had and try to include those into your blurb about your campaign.
