# An Analysis of Kickstarter Campaigns
## Performing analysis on Kickstarter data to uncover trends.
---
### Summary 
#### I have partnered up with Louise, an up and coming playwright, to help her start a crowdfunding campaign for her play, Fever. She is currently estimating a budget of over $10,000, possibly up to $12,000, to produce the play in the United States. In addition, she is interested in musicals in Great Britain. I have organized, sorted, and analyzed crowdfunding data in Excel to help determine which factors make a project’s campaign most successful. The data insights have helped me to provide Louise with the information she needs to mirror a successful campaign. 
---
### Analysis
#### In order to begin drawing conclusions from the dataset, I have conditionally formatted the outcomes to easily identify which campaigns were successful, live, failed, or canceled. In addition, the percentage funded of each campaign has been conditionally formatted so Louise will be able to recognize how close each campaign was to reaching its funding goal. These conditional formats will aid Louise in further analyzing the data once I have provided her with my conclusions.  
---
#### Since Louise is specifically interested in creating a funding campaign for plays, the “Category and Subcategory” column has been split into “Parent Category” and “Subcategory” to include more data for further analysis of theater campaigns. Taking a look into which parent categories did or did not perform well in the United States, a pivot chart of Parent Category Outcomes in the U.S. was created and can be viewed below. 
---
![](Parent%20Category%20Outcome.png)
---
#### The chart demonstrates that in general, a theater Kickstarter campaign in the U.S. is successful. This is good news for Louise. However, since the campaign will be for a play, it is important to identify whether or not plays can have successful Kickstarter campaigns as well. An additional pivot chart was created that concentrated on the subcategories (musical, plays, spaces) of theater to investigate further.  
---
![](Theater%20Subcategory%20Outcomes%20in%20the%20US.png)
---
#### The Theater Subcategory Outcomes in the U.S. chart demonstrates that plays are the most successful form of a theater Kickstarter campaign in the United States. However, Louise is also interested in musicals in Great Britain. 
---
![](Theater%20Subcategory%20Outcomes%20in%20Great%20Britain.png)
---
#### Unfortunately for Louise, the Theater Subcategory Outcomes in Great Britain reveals that musicals are not as successful as plays.  
---
#### Now that Louise knows she is on track to have a successful play Kickstarter campaign in the U.S., I will be taking a further look into which factors contribute most to a successful or failed campaign. To do this, I have analyzed the measures of central tendency for the successful and failed play Kickstarter campaigns in the United States. 
---
![](Theater%20Play%20Measures%20of%20Central%20Tendancy.png)
---
#### Observing the table above, it can be seen that failed Kickstarter campaigns have much higher fundraising goals than successful campaigns. However, at this moment, we do not know if money is a contributing factor. The mean and median failed pledged amounts are much lower thant those of the successful pledges, incdicating Louise will need to take in additional considerations other than money. If the median pledges of the failed campaigns had been similar to the successful campaigns, then it would have been possible that the fundraising goal was too high.  
---
#### I have looked into launch date as being one of the driving forces of a successful versus unsuccessful campaign.  
---
![](Outcomes%20Based%20on%20Launch%20Date%20for%20Theater%20Kickstarter%20Campaigns.png)
---
#### Looking at the years 2014 to 2016, it can be observed that the most successful campaigns were held between the months of May and June, and the likelihood of a successful campaign decreases the closer the launch date approaches the end of the year; December would not be a recommended time for Louise to launch her campaign. 
--- 
#### Referring back to the measures of central tendancy, the mean of each distribution is around the 3rd quartile, demonstrating the data follows similar distributions in each subset (goal & pledged / successful & failed). The standard deviations are also larger than the means, indicating everything below the mean is “close” to the center and larger values are driving these deviations. The driving forces (outliers) can be seen in the Box and Whisker Plot: Successful Play Outcomes in the U.S. below.  
---
![](Box%20and%20Whisker%20Plays%20US.png)
---
#### In a box and whisker plot, the box shows the interquartile range (IQR). An “X” inidicates the mean and a line through the box indicates the median. The whiskers show the extreme values that fall within 1.5 x IQR. Finally, the outliers (values greater than 1.5 x IQR) are shown as dots.   
---
#### Since the mean goal and mean pledged amounts are about $5,000 and Louise is estimating over $10,000, she may want to investigate plays with higher goals further. Successful plays with goals greater than $10,250 and pledges exceeding $11,672 are considered outliers of the data set. How this will effect Louise’s campaign will need to be determined. 
---
#### Similarly as above, I have also looked into musicals in Great Britain. Specifically, Louise is interetsed in musicals in Great Britain and currently has an estimated budget of £4,000. 
---
![](Box%20and%20Whisker%20Musical%20GB.png)
---
#### The box and whisker plot shows that the mean goal is £4,000, however the mean pledged is only about £1,000. It would be best if Louise could drive down her costs, especially since even the median goal of musicals in Great Britain is £2,000 and outside the 3rd quartile of what was actually pledged to the campaigns.  
---
### Conclusion
#### I recommend that Louise start a theater Kickstarter campaign for plays in the United States. Previous campaigns have shown us that play Kickstarters tend to be successful. We will however need to further investigate the probability of success since her fundraising goal of $10,000 - $12,000 is greater than the mean and median pledged amounts for similar campaigns. 
---
#### It was also discovered that one of the driving factors in a successful campaign is the launch date. I recommend that Louise launch her campaign in either the month of May or June and stay away from launching her campaign close to December.     
---
#### In addition, I recommend that Louise reconsider launching a musical in Great Britain. It was observed that plays tend to be more successful compared to musicals in this country. Also, the mean campaign pledges for musicals in Great Britain is £1,000, indicating £4,000 is most likely too large of a goal amount. 
---
### Challenge 
---
#### I have reviewed the Kickstarter campaign data further and have additional updates for Louise. Further analysis has revealed that money is a driving factor of campaign success. Also, May is the best month to start a theater Kickstarter campaign. 
---
#### The outcomes (successful, failed, or canceled) of all theater-play campaigns have been evaluated based on goal fundraising amounts. In the plot below, it can be observed that the highest probability of a successful campaign is for those that have a goal of less than $5,000, with a percent of success at about 75%. The percentage of successful campaigns then drops to about 55% after $5000, and decreases by an additional 10% once goal amounts reach $24999. Although there is an increase of campaign success for those with goals above $25000, the number of campaigns with goals that high is much less. Therefore, the data may be inaccurate due to the smaller sample size. Louise should be cautious of the success rates for campaigns with goals above $25000. 
---
![Outcomes_Based_on_Goals](Folder/Outcomes%20Based%20on%20Goals.png)
---
#### Louise’s play campaign falls within the goal range of $10000 to $14999, which has a percentage of success of 54%. To help make sure Louise’s plan is on the successful side, it should be launched in the month of May. A plot of theater campaign outcomes and their launch dates has been plotted below. From the plot, it can be observed that May has the highest number of successful campaigns. For further analysis, Louise should narrow down her observations to look at the number of successful plays specifically in the U.S., where she is planning on starting her campaign. 
---
![Outcomes_Based_on_Launch_Date](Folder/Outcomes%20Based%20on%20Launch%20Date.png)
---
#### Overall, Louise is on track for a successful campaign. Although her goal amount is higher than the mean and median successful pledge amounts, there is still a 54% chance of success. Also, her chances of success are increased if she launches the campaign in May and stays away from launching it close to the end of the year. I recommend that Louise also consider narrowing her search of launch dates specifically to plays in the United States. Another additional factor I would suggest Louise investigate is duration of campaign. If a campaign is too short, it may decrease her chances of success. Finally, the number of backers could also impact her chances of success. 
