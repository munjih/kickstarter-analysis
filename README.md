# kickstarter-analysis
Analysis on Kickstarter campaign data

## Louise is interested in starting a campaign for theater.

- In the US, 912 Kickstarter campaigns were launched in the "Theater" category. 525 of these campaigns were successful. Within this category, the "Plays" subcategory had the highest number of launches. Among the 671 campaign for plays, 412 were successful, 250 failed and 9 are live. 
![Category outcomes](https://github.com/munjih/kickstarter-analysis/blob/master/Parent%20Category%20Outcomes%20chart.png)

- In Great Britain, 604 Kickstarter campaigns were launched. Among the subcategories, "Plays" had the most number of campaigns. 238 campaigns out of the 314 were successful. 
![Subcategory outcomes GB](https://github.com/munjih/kickstarter-analysis/blob/master/Subcategory%20outcomes_GB.png)

- Campaign outcomes were more successful when the campaign was launched in the late spring to mid-summer (May-July).
![Launch date analysis](https://github.com/munjih/kickstarter-analysis/blob/master/Outcomes%20based%20on%20launch%20date.png)

The trend was similar for the theater category campaigns as well.
![Launch date category analysis](https://github.com/munjih/kickstarter-analysis/blob/master/Subcategory%20outcomes%20based%20on%20launch%20date.png)

- Comparison of successful and failed campaigns in US, we could deduce that failed campaigns tend to have higher goals than the successful ones. Also, we could tell from the distribution of goals that the median goal amount is rather closer to the lower quartile of the interquartile range. 

**Advise for Louise**
Theater is a pretty popular category among the Kickstarter campaigns both in the US and Great Britain. The campaigns launched late spring to mid-summer seems to be more successful compared to campaigns launched during the winter months. It seems better to keep the goal lower for a more successful outcome. 

### Challenge
Louise’s play Fever came close to its fundraising goal in a short amount of time and we would like to know how this correlates with other Kickstarter campaigns. 

- First, we wanted to analyze if the success rate correlates with the goal amount when the campaigns for the "Plays" subcategory was launched. Overall, the percentage of successful campaigns were higher when the goal amount was on the lower side (<$25,000), however, the outcome does not completely correlate with the goal amount as campaigns with higher goals ($35,000-$45000) also showed a pretty high success rate. 
![Outcomes based on goal](https://github.com/munjih/kickstarter-analysis/blob/master/Outcomes%20based%20on%20Goal.png)

- Second, we analyzed the outcome based on the launching date for the "Theater" category. As shown, the outcome shows a tendency of being more successful when launched between May and July compared to the winter months. 
![Outcomes based on launching date](https://github.com/munjih/kickstarter-analysis/blob/master/Outcomes%20based%20on%20launch%20date.png)

- The two analyses performed gives us some suggestion that for a play, it is better to keep the goal below $25,000 and launch the campaign during late spring to mid-summer for an ultimate success. 

- The outcomes based on launching date gives us an idea if actual launching date correlates with its outcomes. We can compare Louise's launching date to this chart and find the correlation. The first analysis involving the goal amount does not show significant correlation with the outcomes. Rather, I think comparing relationship of the number of backers or the average pledge amount to the outcomes should give us more information if Louise's campaign behaved similar to the other campaigns. Also, analyzing the duration of campaign vs. outcomes might also provide some useful information in finding the correlation of Louise's campaign to the others. 
