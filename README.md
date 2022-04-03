# An Analysis of Kickstarter Campaigns
_Performing Analysis on Kickstarter Data to Uncover Trends_

# Kickstarting with Excel

## _Overview of Project_

**Fever** has a projected budget of $10,000 and while a crowdfunding effort for a lower amount, $2,885, was close to its goal, it did not succeed. Fortunately, there is data collected on other crowdfunding projects for comparison.

### _Purpose_

To look at similar crowdfunding efforts and explore options for another **Fever** campaign.

## Analysis and Challenges

Taking advantage of a data file from [Kickstarter](https://www.kickstarter.com/), we were able to sort and filter the projects by goals, pledges, locations, categories, time-frames, and levels of success, each with some detail. Kickstarter’s data covered over 4,000 projects and eight years of time (2009-2017), and so we sorted by the theater category for launch date analysis and, more specific, plays, for goals analysis.

### Analysis of Outcomes Based on Launch Date

Checking start- and stop-dates, the successful projects for plays averaged a length of four weeks. With this in mind, we aimed to determine the best month to start. Using a pivot table, we sorted projects by level of success and month of launch date. Triple-digit ‘successful’ results for May and June stuck out immediately, but with a pivot chart we could see that Spring and Summer months could also mean failure. It is possible to determine exact launch dates but this should only be necessary if **Fever** needs a certain date for promotion. 
![This is an image](https://github.com/JaimeStarling/Kickstarter-Analysis/blob/3b12fe9438cccb58da71308dc745e07ce93bf517/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

Setting goals in Kickstarter is another determinate of success, just as conventional fund-raising can be with a matching donor challenge. Too high a goal can guarantee failure, meanwhile, a successful, low goal may have missed out on further donations. We sorted the goals by dollar amounts (less than $1,000, then in an increment of 4K and for the rest, 5K) and tallied the number of campaigns by successful, failed, and canceled. 

We then ran the outcomes by percentage. These percentages were plugged into a pivot chart that at a glance showed contradictions to various assumptions (the higher the goal, the likeliness to fail) about pledges, upon which the outcomes are based. A pivot chart was generated to provide a better grasp of how much to aim for when setting a goal for **Fever**.

### Challenges and Difficulties Encountered

Where creating a better sense of the launch dates was relatively straightforward, there was some trouble-shooting required for creating the goal money amount ranges. The formulas in the table for counting within the ranges now accurately show the correct numbers. Double-checking in a separate spreadsheet with basic sorting and filtering was a great help. There was also some added confusion over the sum of percentage of canceled projects resulting in zero, at least until a return to the dataset showed that no play fundraisers were ever canceled.

## Results

What are two conclusions you can draw about the Outcomes based on Launch Date?

 - While the month of May seems to be the most generous for theater fundraising, it is also the least. It was the most popular month to start a campaign overall, and so the crowdfunding was crowded in this instance, much more a competition with other theater projects for donations. 
 - Where far more factors would be in play, such as publicity of the fundraiser and the ‘pitch’ of the project, **Fever** could do better by relaunching a month earlier than before, which, of course, is May. However, with other data in play, June is still a good month to launch with lessons learned from the previous campaign.

What can you conclude about the Outcomes based on Goals?
 
- A goal of something under $1,000 is far more achievable but **Fever** has already proved to raise more than twice that range. A rounded goal of $3,000 is more feasible and if achieved, looks good in marketing with an accurate ‘30% funded by the public’ or similar wording. Any amount beyond $5,000 becomes significantly more difficult.

What are some limitations of this dataset
 
- Kickstarter is known for repeated donors and especially ‘rewards’ given for donations, such as exclusive products or access, that brings those donors back to the site. Without revealing too much information on the donor, Kickstarter could have provided the number of first-time donors in the mix of each project. While the value of the reward would be difficult to assess, Kickstarter could provide how many people pledged at certain amounts. Such data helps design a more appealing pitch for **Fever** as a Kickstarter campaign. Especially with live theater, it helps to know exactly where a project is happening, and if the rewards are limited to being in or near that location.

![This is an image](https://github.com/JaimeStarling/Kickstarter-Analysis/blob/8d405cbcceb19572f682a110c80bcf0b92f65065/Kickstarter%20Pledge%20Award%20Example.png)

What are some other possible tables and/or graphs that we could create?

- A box plot graph would have revealed the outliers of goals and their resulting pledges for plays. The table and graph in this report shows some extremes in fundraising goals that would have been better ignored/forgiven when seen outside of the bulk of results.
