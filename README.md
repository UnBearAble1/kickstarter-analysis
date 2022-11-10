# Kickstarter Analysis

## Overview of Project

### This analysis of kickstarter data reviewed various criteria to identify trends that have resulted in a successful or non-successful kickstarter campiagn. This analysis reviewed theaters and plays, analyzing criteria including the time frames when they launched, the amounts saught for each project and the percentage of success for projects within defined dollar ranges.

## Analysis and Challenges

### Analysis of Theater Outcomes based on Launch

Our first analysis looked at the outcomes for theater projects and if they were successful, failed, or were cancelled based on the month when they launched for every year within the sample set. The review found that the highest number of successful projects were launched in May with high rates of success in June and July. The highest number of failures were also in May, with June and July also having high numbers of failures. Cancellations spiked in January, but remained low throughout the sample. 

![Theater_Outcomes_vs_Launch](https://github.com/UnBearAble1/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

The second analysis reviewed the percentage of successes, failures and cancellations for plays based upon different buckets of goal amounts. The data show the highest percentage of successful kcikstaters for plays have goals between $0-$4999 with a rate in the low 70%. This range also included the largest total number of projects. Projects between $35000-$44999 also had higher percentages of success at 67%, though these buckets had very low numbers of total projects. The highest numbers of failures were between $45000-$49999 at 0% (though there was only one project in this group), with other significant high rates of failure between $25000-$34999 with nearly 80% failure rates and a relatvely small numbers of projects. There were no cancelled projects in the sample.

![Outcomes_vs_Goals](https://github.com/UnBearAble1/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

There were no significant difficulties in organizing the information requested. While the outcomes based on goals offered some complexity in ensuring the correct logic, it was able to be checked against the sample to ensure completeness. In the analysis, there is difficulty in knowing if the criteria selected is the most appropriate to make decisions. While the date of launch can be useful, traneds over time could also provide insight and limiting the region to the one in which the client wanted to focus their kickstarter could provide more insight. It could also be worth for failed projects to see the difference between the goal and pledged amounts to see the percentage of funding recieved and if the client could secure alterante sources of funding to close any gap.

## Results

* What are two conclusions you can draw about the Outcomes based on Launch Date?
  * The most successful months to launch have historically been in May, June and July and the client can wait to launch their project during these times
  * December is the month with the fewest number of successful launches and should be avoided.

* What can you conclude about the Outcomes based on Goals?
  * Smaller dollar goals are more plentiful and have higher rates of meeting their goals when comapred to goals with higher dollar amounts. While a few amount of large goals are successful, keeping the goal amount lower than $5000 has the highest percentage of success.

* What are some limitations of this dataset?
  * It has not been restricted by region and therefore includes multiple currencies and it is not clear if the pledged amount is in local currency or has been converted to USD. While the $ symbol was used in the column for the pledged data, it was not made clear. Currencies with a lower or higher values versus the dollar can skew results.
  * While the data had the average amount donated, it didnt have the mean amount, which could show if any of these projects skewed and were funded by a small set of larger donors, which could impact how the client could go about raising funds.

* What are some other possible tables and/or graphs that we could create?
  * Limiting analysis to the region where the client wants to focus on.
  * Show the average number of backers and average donation for similar successful projects.
  * Impact of staff pick or spotlight on success or failure for different goal amounts.
  * Changes in success rates and donations over time.
