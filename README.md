# Evaluating Reminder Push Notifications on InstaCart Orders

## Project Overview

Digital platforms frequently use push notifications to increase customer engagement and encourage repeat purchasing behavior. However, ineffective notification strategies can negatively impact user experience and create notification fatigue, making it important to measure whether these interventions produce meaningful business impact.

This project evaluated whether reminder notifications encouraging users to reorder previously purchased products increased overall order activity on InstaCart. Using an end-to-end A/B testing framework in R, the analysis simulated a randomized experiment to measure the causal effect of reminder notifications on customer purchasing behavior.

The objective of the project was to demonstrate how experimentation and statistical analysis can help businesses evaluate product features, optimize customer engagement strategies, and support evidence-based decision-making.

Examples of business applications include:

* Measuring whether product features increase user engagement
* Evaluating the effectiveness of customer retention strategies
* Supporting data-driven marketing decisions
* Quantifying the revenue impact of platform interventions
* Reducing uncertainty in product experimentation

This project demonstrates how causal inference and experimentation frameworks can be applied to real-world business problems in consumer technology platforms.

---

## Project Links

📈 Click here to view the experimental analysis report and visualizations

💻 View the experimental analysis code here

---

## Methodology

The analysis was conducted using the InstaCart Online Grocery Basket Analysis dataset available through Kaggle. The project simulated a randomized controlled A/B test designed to measure the impact of reminder push notifications on future ordering behavior.

Users were assigned into treatment and control groups:

* The treatment group received reminder notifications encouraging reorders of previously purchased products
* The control group did not receive the intervention

To validate the experimental setup, balance checks were performed to confirm comparability between groups prior to treatment evaluation. Regression analysis and statistical inference techniques were then used to estimate the treatment effect and quantify the impact of notifications on user ordering behavior.

Confidence intervals were used to evaluate the reliability and statistical significance of the estimated effects. Visualizations were also incorporated throughout the analysis to compare treatment outcomes and communicate experimental findings.

The workflow mirrors how experimentation frameworks are commonly implemented in industry product analytics and growth experimentation environments.

---

## Findings

The analysis found that reminder notifications increased overall ordering activity relative to the control group.

The final experimental results estimated that:

* Reminder notifications increased orders by approximately <strong>0.198 additional orders per user</strong>
* 95% confidence interval: <strong>0.193–0.202</strong>

Although the per-user increase appears modest individually, the effect becomes operationally meaningful at platform scale where even fractional increases in customer activity can generate substantial revenue impact across millions of users.

The analysis also demonstrates the importance of controlled experimentation when evaluating product features, as measured effects may differ substantially from intuition or observational assumptions.

---

## Recommendations

Based on the findings, reminder notification systems could be used strategically to improve customer engagement and encourage repeat purchasing activity while maintaining a positive user experience.

The observed increase in ordering behavior suggests that personalized reorder reminders may provide measurable business value when implemented thoughtfully at scale. Platforms could potentially use similar experimentation frameworks to optimize customer engagement strategies and evaluate future product interventions.

Potential business applications include:

* Increasing repeat purchasing behavior through targeted notifications
* Improving customer retention and platform engagement
* Evaluating personalized marketing strategies using experimentation
* Testing different notification timing and frequency strategies
* Supporting evidence-based product and growth decisions

Future improvements to the experimental framework could include user segmentation analysis, long-term retention measurement, personalization strategies, and evaluation of potential notification fatigue effects across different customer groups.

The project demonstrates how experimentation and causal inference can help businesses quantify the impact of operational and marketing decisions before large-scale implementation.
