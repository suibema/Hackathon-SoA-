# Hackathon-SoA-

## Project Overview

This analysis focuses on an experiment conducted for a mobile application monetized through paid subscriptions. The experiment involved redesigning the paywall (subscription screen) while keeping the subscription options and prices unchanged. The primary objective was to assess the impact of the new paywall design on user conversions, revenue generation.

## Key Inputs

Subscription Types: Monthly, Quarterly, and Annual subscriptions.

Retention Rates: Provided for each subscription type, covering renewals for two years.

Conversion Data: Information on the conversion rate from a free trial to a paid annual subscription.

Pricing: Price points for each subscription type.

## Key Metrics

Primary Metric

Conversion Rate: The percentage of users who subscribed after viewing the paywall.

Secondary Metrics

Revenue Per User (RPU): Average revenue generated per user. 

Revenue Per Subscriber: Average revenue generated per subscribing user.

Total Revenue: The cumulative revenue from all users.

Retention Rates: The proportion of users who renew their subscriptions.

## Hypothesis

Null Hypothesis (H₀): There is no significant difference in the conversion rate and revenue between the control group (old paywall) and the experimental group (new paywall).

Alternative Hypothesis (H₁): The new paywall design leads to a significant improvement in conversion rate and/or revenue compared to the old paywall.

## Experiment Design

Control and Experimental Groups

Control Group (Group A): Users exposed to the old paywall design.

Experimental Group (Group B): Users exposed to the new paywall design.

## Statistical Tests

Shapiro-Wilk Test: Used to test the normality of revenue distribution for both groups.

Levene’s Test: Used to test the equality of variances between the two groups. The p-value for this test was 0.226, indicating no significant difference in variances.

Mann-Whitney U Test: Since the revenue data did not follow a normal distribution, the Mann-Whitney U test was used to assess the difference between the two groups, resulting in a p-value of 0.022.

## Bayesian Analysis

Posterior Distribution: Distribution of conversion rates for both groups.

Bayesian Probability: The probability that the new paywall (Group B) outperforms the old paywall (Group A) in terms of conversion rate was calculated to be approximately 0.9949.

## Quantitative Analysis

Results Summary

Total Users: Both groups had 1,000 users.

Users Reached Payment Screen: 831 users in Group A and 859 users in Group B.

Subscribed Users: 400 users in Group A and 456 users in Group B.

Total Revenue: 212,700 for Group A and 236,700 for Group B.

Conversion Rate: 40.0% for Group A and 45.6% for Group B.

Revenue Per User (RPU): 212.70 for Group A and 236.70 for Group B.

Revenue Per Subscriber: 531.75 for Group A and 519.08 for Group B.

Revenue per person considering retention rates for two years: 2760, 1570, 1440 for a monthly, quarterly and annual subscriptions accordingly.

## Statistical Test Results

Mann-Whitney U Test: The p-value was 0.022, indicating a statistically significant difference in revenue between the two groups.

Z-Test for Conversion Rates: The Z-score was -2.531, with a p-value of 0.011 for the two-tailed test, showing a significant difference in conversion rates. Bayesian Inference was needed for further analysis to indicate exactly which group performs better.

95% confidence interval for conversion difference (B-A): 0.013-0.099 with mean: 0.0561814. This means that we are 95% confident that the true difference in conversion rates between Group B and Group A lies between 1,3% and 9.9%. Given that this interval does not include zero, it suggests that Group B likely has a statistically significant higher conversion rate compared to Group A.

## Bayesian Inference

Probability that Group B Outperforms Group A: 0.9949, indicating strong evidence that the new paywall design is more effective in converting users.

## Visualizations

1. KDE Plot of Conversion Rates:

Description: The plot shows the distribution of conversion rates for Group A (blue) and Group B (red).

Observation: The distribution for Group B is shifted to the right, indicating a higher conversion rate compared to Group A.

2. Distribution of Conversion Rate Difference (B - A):

Description: The histogram shows the distribution of differences in conversion rates between Group B and Group A.

Observation: Most of the distribution lies above 0, indicating that Group B generally outperforms Group A in terms of conversion rate. The dashed line at 0 reinforces the significance of the positive difference.

## Conclusions

The analysis shows that the new paywall design (Group B) leads to a statistically significant improvement in both conversion rate and total revenue compared to the old design (Group A).

The Bayesian analysis supports the conclusion that the new paywall is superior, with a 99.49% probability that it outperforms the old design in terms of conversion rate.

Surprisingly, revenue per subscriber is higher in group A, although group B is having larger overall revenue. This can be explained by the fact that it has more annual subscribers than in group B. Nevertheless, both quarterly and annual subscriptions yield lower revenues per person over two years (1,570 and 1,440, respectively) compared to monthly (2,760) considering their lower retention rates. 

## Recommendations

Based on the results, it is recommended to adopt the new paywall design for all users, as it demonstrates a clear improvement in conversion rates and revenue generation. Further testing could be conducted to refine the design or to explore its impact on long-term retention and user satisfaction. 

## Further Actions

Continue A/B testing with larger segments or different user demographics to confirm the results.

Collect qualitative feedback from users to understand their preferences and enhance the paywall design further.

Monitor retention rates and ROI over an extended period to ensure the sustainability of the observed improvements.

Future implementation of initiatives to increase the perceived value of quarterly and annual plans throughout their duration to boost retention rates is also a point of consideration.
