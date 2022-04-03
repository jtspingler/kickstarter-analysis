# Kickstarting with Excel

## Overview of Project
Using pivot tables and graphs Excel to visualize campaign outcomes ("successful," "failed," and "canceled") based on launch date from the Kickstarter data set provided.
### Purpose
The purpose of this analysis was to identify trends of multiple campaigns based on factors such as funding goals and launch dates. 
## Analysis and Challenges
This data was relatively clean at first. In order to identify date trends, we converted the timestamps to dates as well as then extracting the year and month from this date. The findings of my analysis can be found [here](https://github.com/jtspingler/kickstarter-analysis), as well as presented below:

![This is an image](https://github.com/jtspingler/kickstarter-analysis/blob/108a4ed89d8059ea826e4c2181063fdd872d9478/Date%20conversion.PNG)

I struggled with grouping the Months as their names rather than the numerical representation. 

![This is an image](https://github.com/jtspingler/kickstarter-analysis/blob/fca25a1668a607d4303c86bdac57b897b34c38a4/succ%20v%20failed%20pivot.PNG)

### Analysis of Outcomes Based on Launch Date
Based on the data graphed below, it is clear that the best time to launch a campaign is during and around the month of June. There is not a ton of variance regarding failed campaigns and regardless of the time of year, this data set hovered around 40 failed campaigns each month. This data set also did not have much variance as it related to the cancelled campaigns and in fact the cancelled campaigns hovered around zero throughout the year. I'm curious what sort of value this metric is providing us. Besides the successful outcomes trend in the middle of the year, the only other trend I notice is that successful outcomes have a significant drop off (-33%) at the end of the year.

![This is an image](https://github.com/jtspingler/kickstarter-analysis/blob/54dc854264083a7964ffadce94d6aaa4a699c811/Theater_Outcomes_vs_Launch.PNG)

### Analysis of Outcomes Based on Goals
Based on the data graphed below, campaigns are most likely to be successful with fundraising goals that are less than $1,000 and from $35,000 - $45,000. The next observation that pops out to me is that any fundraising goals greater than $45,000 have a signficant chance of failing. It seems that the sweet spot for the most success are goals less than $20,000 as this is the point where success and failures intersect. For goals between $20,000 and $35,000 the likelihood of failures vs success is 4 times as great. If it were me I would aim for a smaller fundraising goal, as the data beyond $20,000 is fairly inconclusive.

![This is an image](https://github.com/jtspingler/kickstarter-analysis/blob/fcc51790df39cce4094960b9b543f38c07775fd2/Outcomes%20based%20on%20Goals.PNG)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

I would reccommend to launch a campaign during the summer and would advise against launching one in December. We need to look at the data differently if we want to understand why these plays are failing. 

- What can you conclude about the Outcomes based on Goals?

It is best to start small with your fundraising goal and avoid hefty goals larger than $45,000. We cannot draw any conclusions about the cancelled shows based on goals as there are no trends.

- What are some limitations of this dataset?

We are only looking at one subcategory. This is definitely a limitation, as seeing plays may be more popular during the summer. I would want to test this assumption further.

- What are some other possible tables and/or graphs that we could create?

It would be interesting to cut this data based off of the average donation and see how that might have contributed towards success or not. I would suspect that plays with a higher average donation amount would have a better chance of being successful. I would think that someone who donated a larger amount would be more inclined to see the play and tell others to do the same.
