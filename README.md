# Kickstarting with Excel

## Overview of Project

*Fever* nearly met it's fundraising goals in a short amount of time. Did this have anything to do with the date that the project was launched? This analysis is meant to understand how other campaigns on Kickstarter fared in relation to their launch dates and fundraising goals. 

### Purpose

The goal is to visualize and analyze campaign outcomes based on their launch dates and fundraising goals.

## Analysis and Challenges

Based on our dataset it is clear that there is a statistically positive outcome for campaigns that look to raise anywhere between 1 and $19,999 and launch during the summer months.

However, a clear blind spot of the available data is the lack of canceled plays in our dataset. 

![Analysis_1.png](https://github.com/craig-clemens/kickstarter-analysis/blob/main/Anaylsis_1.PNG)

This indicates that our dataset is either incomplete or, alternatively, canceled plays on Kickstarter are incredibly rare. Outside of this shortcoming, our dataset is fairly expansive and offered us enough information to answer our questions: when is the best time to start a campaign, and what percentage of plays succeed or fail?

### Analysis of Outcomes Based on Launch Date

May, June, and July are statistically the most effective months to launch a campaign, as visualized in the graph below:

![Theater_Outcomes_vs_Launch.png](https://github.com/craig-clemens/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

It would be inadvisable to start a campaign in the winter months as a larger percentage of total campaigns fail during this time. This could be that spending around the holiday season impedes a theater consumers ability to also spend on Kickstarter campaigns. Or alternatively, the colder weather suppresses charitable giving to plays. 

Additionally, it would seem that the raw number of campaigns diminish over the winter months, reaching their nadir in the months between November and March. This represses the total percentage of successful campaigns overall while the number of failed campaigns remains relatively constant throughout the year. This may also have to do with the holiday season or inclement weather as production companies are less likely to produce campaigns during this season. 

### Analysis of Outcomes Based on Goals

When analysing the graph below:

![Outcomes_vs_Goals.png](https://github.com/craig-clemens/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)

we can see that there is a clear intersection of Percentage Successful and Percentage Failed in the $15,000 to $19,999 range. Most all lessor ranges are statistically successful while most higher ranges statistically fail. An outlier of this trend is the two ranges spanning $35,000 to $44,999. Based on our analysis I would claim that this is a statistical outlier as there are very few data points that skew this result.

### Challenges and Difficulties Encountered

Two main challenges are prevalent throughout, both are related to the data set: 

1) Our lack of data resulting in cancelled plays. Again, this may be due to insufficient data or could actually be indicative of a trend. Without sufficient data, however, it is difficult to tell.

2) The lack of data points in the upper dollar-amount ranges of our data leaves us with data that seems to be an outlier of our trends. I would argue that this is due to a lack in raw data inputs. If there were a normalized (n) for each dollar-amount range, I would suspect that there would be a direct correlation to the outcome.

## Results

In conclusion, regarding the launch date the data suggests that the most successful campaigns launch in the summer months (May, June, and July) while a higher percentage fail during the winter. However, as the raw numbers of campaigns also diminish during the winter, it skews the percentage as the number of failed campaigns remain relatively the same throughout (=/-20 or so campaigns).

Regarding goals, the data is quite clear: a campaign is most likely to be successful if it asks for less than $19,999

The clear lack of any data relating to canceled plays and failed plays in the $30,000 - $44,999 ranges leaves us with outliers to our trends and forces us to guess at why campaigns are cancelled or might be successful or fail in these ranges.

To better understand our outliers I would suggest also creating a graph to examine the outliers in our dataset. A box & whisker chart for our Outcomes Based on Goals would help us clearly identify our outliers and visualize trends with more clarity. 

