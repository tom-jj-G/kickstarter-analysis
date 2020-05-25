# An Analysis of Kickstarter Campaigns
## Performing analysis on Kickstarter data to uncover trends
### Lessons

![](Images/Outcomes%20by%20launch%20date%20worldwide.png)

![](Images/Outcomes%20by%20subcategory%20in%20the%20US.png)

---
### Challenge
*Note: in case of display error, cf. image "Outcomes based on Goal for plays' kickstarter campaigns worldwide.png" in the folder Images.*
![Outcomes based on Goal for plays' kickstarter campaigns worldwide](Images/Outcomes%20based%20on%20Goal%20for%20plays'%20kickstarter%20campaigns%20worldwide.png)

Based on of our dataset and the chart above, we could assess there is no clear correlation between Goal amount and its outcomes.
Nevertheless, we could observe 5 different trends:
- Until 5 k$, a play is more likely to be successful
- Between 5 k$ and 20 k$, the odds are almost identical
- From 20 k$ until 30 k$, a fail campaign is more likely to occurs
- From 35 k$ to 40 k$, the chance of success seems higher
- Past 45k$, a failure is again more expected

We need to balance our analysis as it comes with some flaws:
- 85% of our dataset concerned campaign with a goal aim strictly less than 10 k$
- No cancelled campaign was present in the dataset with it is unlikely to be representative of a perfect sample. Successful and failed rates should have been impacted in an uncertain manner

In order to enhance our analysis:
- Additional "big amount" goal (>= 10 k$) should be added in order to have a less skewed dataset. A histogram could be used to visualize the data repartition
- For each outcome, box plot charts could be use in order to remove outliers and strengthen our analysis
- Of course, filtering plays by country or even adding a subcategory to plays could refine our analysis (assuming amount of data remains consequent)


*Note: in case of display error, cf. image "Outcomes based on launch date for theater's kickstarter campaigns worldwide.png" in the folder Images.*
![Outcomes based on launch date for theater's kickstarter campaigns worldwide](Images/Outcomes%20based%20on%20launch%20date%20for%20theater's%20kickstarter%20campaigns%20worldwide.png)

Also based on of our dataset and the chart above, we could assess that the months of May, June and July are the best time to launch a theater kick-starter campaign. 
The different gap between each outcome line is almost identical expect for these months where the successful rate is higher.

The results should not be considered as flawless:
- Theater subcategories are various and go from plays/musicals to spaces which could mislead the results 
- Year of launches has not been taken as a discriminant factor and some trends might appear and disappear year after year
- Duration of campaign could also be a huge factor of success for the campaign. The longer they are, the more successful they might be

In order to tinker our analysis, we could:
- Use percentages instead of counts as they might be more relevant for pulling out trends (in association with a histogram to visualized data repartition)
- Trim data by campaign length (4 standard intervals based on the quartiles of dataset campaign length) using stacked columns to better visualized campaign length influence 
- Filtering graph by year or make 3 charts for the 3 last years for instance
- Finally, filtering by country or subcategory could also refine our analysis (assuming amount of data remains consequent) so does eliminate outliers
