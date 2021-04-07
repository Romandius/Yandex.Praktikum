Data-driven business decision-making

Methods and tools for testing hypotheses. Designing experiments. Seasonality. Cohort analysis. A / B testing. Project. Test hypotheses for increasing revenue for a large online store: perform prioritization, conduct an A / B test, and analyze the results.


## Tasks

- Apply the ICE framework to prioritize hypotheses. Sort them in descending order of priority;
- Apply the RICE framework to prioritize hypotheses. Sort them in descending order of priority;
- Plot cumulative revenue by group;
- Plot the cumulative average check by group;
- Plot the relative change in the cumulative average check of group B to group A;
- Plot the cumulative conversion rate by group;
- Plot the relative change in the cumulative conversion of group B to group A;
- Build a point graph of the number of orders by users;
- Calculate the 95th and 99th percentiles of the number of orders per user. Select a border to identify abnormal users;
- Build a point chart of order values;
- Calculate the 95th and 99th percentiles of the cost of orders. Select a boundary for determining abnormal orders;
- Calculate the statistical significance of differences in conversion between groups based on " raw " data;
- Calculate the statistical significance of differences in the average order receipt between groups based on " raw " data;
- Calculate the statistical significance of differences in conversion between groups based on "cleaned" data;
- Calculate the statistical significance of the differences in the average order receipt between the groups based on the "cleared" data;
- Make a decision based on the test results. Solution options: 1. Stop the test, fix the victory of one of the groups. 2. Stop the test, fix the absence of differences between the groups. 3. Continue the test.


## Used libraries:
- *pandas*
- *random*
- *datetime*
- *matplotlib*
- *seaborn*
- *numpy*
- *stats*

## Data

Data was available for analysis:

- brief description of the hypothesis:
- user coverage on a 10-point scale;
- impact on users on a 10-point scale;
- confidence in the hypothesis on a 10-point scale;
- the cost of resources for testing the hypothesis on a 10-point scale. The higher the value, the more expensive the hypothesis test is;
- order ID;
- id of the user who made the order;
- the date when the order was made;  
- revenue from the order;
- the A/B test group that the order was placed in;
- the number of users on the specified date in the specified A/B test group.
