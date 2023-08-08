# PROJECT: Hypothesis prioritization and AB test analysis.

## DATA:
- A table with hypotheses for increasing the revenue of an online store and parameters: Reach, Impact, Confidence, Effort.
- Table with order data, including information on income, date and division into groups. Table with data on the number of visitors for each day by group.
 
## THE GOAL OF THE PROJECT:
increase of online store revenue.

**During the study, the following work was done:**
- Prioritization of hypotheses to increase revenue. ICE and RICE frameworks are applied. The change in the prioritization of hypotheses when using RICE instead of ICE is considered. An explanation for this change is given.
- Run an A/B test and analyze the results.
Graphs of cumulative revenue by groups, cumulative average check by groups, the relative change in the cumulative average check of group B to group A, the cumulative average number of orders per visitor by groups, the relative change in the cumulative average number of orders per visitor of group B to group A and a dot plot of quantity orders by user.
The 95th and 99th percentiles of orders per user were calculated. A boundary has been selected to identify anomalous users.
A scatter plot of order costs has been constructed. Make inferences and assumptions.
The 95th and 99th percentiles of order value were calculated. Drawn border to detect anomalous orders.
We calculated the statistical significance of differences in the average number of orders per visitor between groups according to raw data, the statistical significance of differences in the average number of orders between groups according to raw data, the statistical significance of differences in the average number of orders per visitor between groups according to cleaned data, the statistical significance of differences in the average number of orders between groups according to the cleared data.
It was decided to stop the test and fix the "victory" of group B, since the decrease in the check by 0.6%, which has no statistical significance, is fully offset by an increase in the number of orders by 15.3%.

## Main acquired skills:
Preprocessing and exploratory analysis and data visualization. Prioritization of hypotheses. Analysis of the AB test.

## Libraries used:
Pandas, Numpy, SciPy, Matplotlib, Datetime.

## Status:
Completed
