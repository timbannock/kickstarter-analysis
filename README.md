# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends.
## Overview of Project
Analyze Kickstarter campaigns relevant to Louise proposed campaign.
### Purpose
Analyze Kickstarter campaigns in the Theater>Plays categories based on Launch Date, Goal, and Outcomes to provide with useful data to determine the best course of action regarding her proposed campaign.
## Analysis and Challenges
After downloading all Kickstarter campaign information, we cleaned the data in order to better separate category/subcategory, to convert the launch and end dates to MM/DD/YYYY format, and to separate out the years for better ability to filter data.
### Analysis of Outcomes Based on Launch Date
Visualize campaign outcomes (“successful,” “failed,” and “canceled”) based on launch date. This provides a look at better times of the year to launch a campaign.
### Analysis of Outcomes Based on Goals
Visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. Thsi provides a look at what funding goals tend to have better success.
### Challenges and Difficulties Encountered
It took a little time to put together the formulas for the different goal ranges in the Outcomes Based on Goals, and required some work to sort the ranges in the PivotTable in order to get a proper overview.
## Results
Here are the results of looking at this data.
### What are two conclusions you can draw about the Outcomes based on Launch Date?
* Inarguably, the most successful campaigns begin in the summer months.
* Late Nov/Dec appears to be the worst time to launch a campaign, which makes sense because many folks will have their money tied up in holiday shopping/gifting rather than fundraising. ![See the chart here](https://github.com/timbannock/kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png)
### What can you conclude about the Outcomes based on Goals?
* Lower goals tend to be much more achievable. ![See the chart here](https://github.com/timbannock/kickstarter-analysis/blob/master/Outcomes_vs_Goal.png)
### What are some limitations of this dataset?
* Because we "mashed" all years together and instead sorted by month for our analysis on launch date, we may be missing some trends with regard to larger economic changes in any given year (or more recent years).
* We are not looking at the breakdown of individual Kickstarter campaign budgets, and so we don't know how much marketing of a Kickstarter campaign directly impacts success/failure of a campaign.
### What are some other possible tables and/or graphs that we could create?
* We may want to do a deeper dive into backer counts and average donations to get a better sense of some benchmarks we'd want to set for a campaign, so we know how to handle different reward tiers.
* We may want to look at campaign length a bit better, which would give some milestones to set during our campaign.
* We definitely want to look at location more to see how much that plays a role in success/failure.
