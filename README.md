# An Analysis of Kickstarter Campaigns
Performing analysis on KickStarter data to uncover trends
## Parent Category Outcomes
First we will analyze categories of crowdfunding campaigns and the trends of their outcomes.  By looking at only the parent categories in our dataset, we can easily see that Theater campaigns are the most prevalent.  Within the theater category there are a large number of successful campaigns, but also quite a few that have failed.  We will want to look at other variables that may affect the outcome.
![parentcategorygraph](https://github.com/alysonrussell/kickstarter-analysis/blob/master/Chart_Parent%20Category%20Outcomes.png)
## Outcomes Based on Launch Date
When we look at launch date as a variable in crowdfunding campaigns, we can make a few conclusions about trends.  Overall, the Theater category sees a high rate of successfully funded campaigns.  However, we can conclude that early summer seems to be the best time of year to launch a theater campaign, with a particularly high rate of success for campaigns launched in May.  Failed and cancelled campaigns do not seem to have any trends that coordinate with a certain month or season, but there are the least number of successful campaigns launched in December.
![launchdategraph](https://github.com/alysonrussell/kickstarter-analysis/blob/master/launchdategraph.png)
## Descriptive Statistics
Next, we can take a look at trends using statistical averages.  This will give us some concrete numbers to start looking at as we develop the ideal goal for this project.  For this section, we will be looking at campaigns in the US only, with a parent category of Theater and a subcategory of Plays.

|                            | Successful | Failed  |
|:----------------------------|:------------:|:---------:|
| Mean Goal                  | $5,049     | $10,554 |
| Median Goal                | $3,000     | $5,000  |
| Mean Pledged | $5,602     | $559 |
| Median Pledged     | $3,168     | $103 |

The above table shows us that failed campaigns in this subset have an average goal of more than double the goal of successful campaigns.  This warns us not to set the goal too high.  Since the median in successful campaigns is much closer to the mean than in failed campaigns, we would conclude that the data in failed campaigns is also skewed by more outliers.  We could confirm this by looking at other Measures of Central Tendency, like the Standard Deviation.  We also see that there is a vast difference in the pledge amounts between the Successful and Failed campaigns.
## Goals and Pledged Amounts
To provide insight on a future musical project in Great Britain, we have created the below analysis on those trends.  Using £4,000 as an estimated cost of production, I would suggest trying to reduce that budget in order to guarantee crowdfunding success.  £4,000 would be considered an outlier based on the amounts pledged.
![boxandwhisker](https://github.com/alysonrussell/kickstarter-analysis/blob/master/launchdategraph.png)
