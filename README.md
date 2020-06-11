# An Analysis of Kickstarter Campaigns
## Performing analysis on Kickstarter data to uncover trends.
---
## Summary 
#### I have partnered up with Louise, an up and coming playwright, to help her start a crowdfunding campaign for her play, Fever. She is currently estimating a budget of over $10,000, possibly up to $12,000, to produce the play in the United States. I have organized, sorted, and analyzed crowdfunding data in Excel to help determine which factors make a project's campaing most successful. The data insights have helped me to provide Louise with the information she needs to mirror a successful campaign. 
---
## Analysis
#### In order to begin drawing conclusions from the dataset, I have conditionally formatted the outcomes to easily identify which campaigns were successful, live, failed, or canceled. In addition, the percentage funded of each campaign has been conditionally formatted so Louise will be able to recognize how close each campaign was to reaching its funding goal. These conditional formats will aid Louise in further analyzing the data once I have provided my conclusions. 
---
#### Since Louise is specifically interested in creating a funding campaign for plays, the "Category and Subcategory" column has been split into "Parent Category" and "Subcategory" to include more data for further analysis of theater campaigns. Taking a look into which parent category did or did not perform well in the United States, a pivot chart of Parent Category Outcomes in the U.S. was created and can be viewed below. 
---
![](Parent%20Category%20Outcome.png)
---
#### The chart demonstrates that in general, a theater Kickstarter campaign in the U.S. is successful. This is good news for Louise. However, since the campaign will be for a play, it is important to identify whether or not plays can have successful Kickstarter campaigns. An additional pivot chart was created that concentrated on the subcategories (musical, plays, spaces) of theater to investigate further. 
---
![](Theater%20Subcategory%20Outcomes%20in%20the%20US.png)
---
#### The Theater Subcategory Outcomes in the U.S. chart demonstrates that plays are the most successful form of a theater Kickstarter campaign in the United States. However, Louise is also interested in musicals in Great Britain. 
---
![](Theater%20Subcategory%20Outcomes%20in%20Great%20Britain.png)
---
#### Unfortunately for Louise, the Theater Subcategory Outcomes in Great Britain reveals that musicals are not as successful as plays. 
---
#### Now that Louise knows she is on track to have a successful play Kickstarter campaign in the U.S., I will be taking a further look into which factors contribute most to a successful or failed campaign. To do this, I have anlayzed the measures of central tendancy for the successful and failed play Kickstarter campaigns in the U.S.
---
![](Theater%20Play%20Measures%20of%20Central%20Tendancy.png)
---
#### Observing the table above, it can be seen that failed Kickstarter campaigns have much higher fundraising goals than successful campaigns. However, money is not necessarily a contributing factor. The mean and median pledged amounts are much lower than the successful pledges, indicating Louise will need to take in additional considerations other than money. If the median pledges of the failed campaigns had been similar to the successful campaigns, then it would have been possible that the fundraising goal was too high. 
---
#### I have looked into launch date as being one of the driving forces of a successful versus unsuccessful campaign. 
---
![](Outcomes%20Based%20on%20Launch%20Date%20for%20Theater%20Kickstarter%20Campaigns.png)
---
#### Looking at the years 2014 to 2016, it can be observed that the most successful campaigns were held between the months of May and June, and the likelihood of a successful campaign descreases the closer the launch date approaches the end of the year; December would not be a recommended time for Louise to launch her campaign. 
--- 
#### Referring back to the measures of central tendancy, the mean of each distribution is around the 3rd quartile, demonstrating the data follows similar distributions for both goals and pledges of successful and failed campaigns. The standard deviations are also larger than the means, indicating everything below the mean is "close" to the center and larger values are driving these deviations. The deviations can be seen in the Box and Whisker Plot: Successful Play Outcomes in the U.S. below. 
---
![](Box%20and%20Whisker%20Plays%20US.png)
---
#### In a box and whisker plot, the box shows that interquartile range (IQR). On the plot, an "X" indicates the mean and a line through the box indicates the median. The whiskers show the extreme values that fall within 1.5xIQR. This chart shows that mean values of the goal and pledged amounts are about $5,000. However, it can also be seen that there are multiple "outliers" that recieved their fundraising goal. 
---
#### Louise is also interested in Great Britain and currently has an estimated budget of £4,000. Similarly as above, I have also looked into musicals in Great Britain. 
---
![](Box%20and%20Whisker%20Musical%20GB.png)
---
#### The plot shows that the mean goal is £4,000, however the mean pledged is only about £1,000. It would be best if Louise could drive down her costs. The median goal of musicals in Great Britain is £2,000, which is still outside the 3rd quartile of amouonts pledged. 
---
## Conclusion
#### I recommend that Louise start a theater Kickstarter campaign for plays in the United States. Although Louise is predicting that the play will cost $10,000 to $12,000, which is greater than the mean and median amounts pledged, the data indicated that money is not necessarily a driving factor in campaign success. There have been multiple other successful campaigns that were considered "outliers" in the dataset. One of the driving factors discovered, is launch date. I recommend that Louise launch her campaign in either the month of May or June, and stay away from launching her campaign close to December. 
---
#### In addition, I recommend that Louise reconsider launching a musical in Great Britain if she cannot drive down the costs. It was observed that plays tend to be more successful than musicals in Great Britain. Also, the mean campagn pledges for musicals is £1,000. In addition, there are not many outliers, which indicated that £4,000 is too hight of a goal amount. 
