# A-B_test_statistics
This is an analysis of an A/B test run by an e-commerce website. Through statistical analysis, I helped determine which version of the web page should the company run.

Based on the data, we have failed to reject the null hypothesis, meaning that the initial web page performed better than the new one. However, this could be a result of change aversion, to make a well-informed decision, the new page should be run for more time, since this experiment had only been running for 5 days when the data was collected.

Statistical Reasoning:
The z-score and p-value from the tests above suggest that conversion rates between the old and new page are not statistically significant. The histogram, on the other hand, shows a decrease in conversion with the new_page compared to the old one.  Furthermore, none of the variables we explored have significant p-values, yet again confirmation that we have not succeeded to reject the null. Lastly, the last test performed with Logistic regression to analyze the relationship between conversion and country didn't provide sufficient evidence to suggest that users from differennt countries see higher/lower conversion. Taking all of this into consideration, we can say that, with the data we have right now, we have **failed to reject the null** 

Suggestions based on outcome:
Based on these results, I would recommend running the new page for a couple more days to collect more data, and if the results continue to be what they are now (or similar), we stick with the old page. 
