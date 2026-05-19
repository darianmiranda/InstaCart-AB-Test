# Evaluating Reminder Push Notifications on InstaCart Orders

## Project Overview

Digital platforms frequently use push notifications to increase customer engagement and encourage repeat purchasing behavior. However, ineffective notification strategies can negatively impact user experience and create notification fatigue, making it important to measure whether these interventions produce meaningful business impact.

This project evaluated whether reminder notifications encouraging users to reorder previously purchased products increased order activity on InstaCart. Using an end to end A/B testing framework in R, the analysis uses a randomized experiment to measure the causal effect of reminder notifications on customer purchasing behavior.

<br>

Full R code Rmd file can be found [here](https://github.com/darianmiranda/InstaCart-AB-Test/blob/main/abtesting.Rmd)

Full R code html file can be found [here](https://github.com/darianmiranda/InstaCart-AB-Test/blob/main/abtesting.html)

View the data [here](https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset)

---

## Methodology

The analysis was conducted using the InstaCart Online Grocery Basket Analysis dataset. The project simulated a randomized controlled A/B test designed to measure the impact of reminder push notifications on future ordering behavior.

Users were assigned into treatment and control groups:

* The treatment group received reminder notifications encouraging reorders of previously purchased products
* The control group did not receive the intervention

To validate the experimental setup, balance checks were performed to confirm comparability between groups prior to treatment evaluation. Regression analysis was then used to estimate the treatment effect and quantify the impact of notifications on user ordering behavior. Confidence intervals were used to evaluate the reliability and statistical significance of the estimated effects. 

Visualizations were also incorporated throughout the analysis to compare pre-treatment variables across groups and also to communicate experimental findings.

---

## Findings

The analysis found that reminder notifications increased overall ordering activity relative to the control group.

The final experimental results estimated that:

* Reminder notifications increased orders by approximately <strong>0.198 additional orders per user</strong>
* 95% confidence interval: <strong>0.193–0.202</strong>

<br>

<img width="2000" height="1200" alt="plot_incremental_order" src="https://github.com/user-attachments/assets/96b469c6-b88f-4077-adca-4aa2f3b473a2" />

<br>

Although the per user increase appears modest individually, the effect becomes operationally meaningful at platform scale where even fractional increases in customer activity can generate substantial revenue impact across millions of users.

---

## Recommendations

Based on the findings, reminder notification systems could be used strategically to improve customer engagement and encourage repeat purchasing activity while maintaining a positive user experience. The observed increase in ordering behavior suggests that personalized reorder reminders may provide measurable business value when implemented thoughtfully at scale.

Future improvements to the experimental framework could include evaluating heterogeneous treatment effects across different customer behaviors, measuring longer term retention impacts, and testing alternative notification timing or personalization strategies.

