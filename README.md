# Data Analysis


### Introduction

Data Analysis is the process of collecting, cleaning, and interpreting data to gain insights that can be used to make better decisions. 
It is a broad field that encompasses a variety of techniques and tools, including statistics, machine learning, and artificial intelligence.

### Data Analysis Goal

The goal is to turn raw data into actionable insights. 
Businesses can make better decisions about how to allocate resources, improve products and services, and target their marketing efforts, based on data analysis insights.

- By understanding how users interact with apps, you can improve user engagement and retention.
- By understanding which features are driving purchases, you can optimize the monetization strategy.
- By identifying and fixing bugs, you can improve the overall efficiency of your apps.
- By having access to data insights, you can make better deicsions for development and marketing.

### Data Analysis Type

- Business Analysis: KPI setting; KPI drilldowns; competitor analysis.
- Marketing Analysis: vendor anslysis; channel analysis; marketing campaign analysis.
- Product Analysis: funnel/churn anslysis; AARRR; user journey analysis; functionality analysis; A/B test.
- Operation Analysis: content analysis; user persona analysis; user segmentation; user life-time value.
- Financial Analysis: forecast/break-even analysis; balance sheet, profit and loss statement, cash flow statement.

### Data Analysis Framework

Imagine a metric — Average Minutes Per Page — suddenly drops 12% in the last week.
You need to figure out what happened, why, and how to fix.

#### Anomaly Detection

“What changed?” - Detect unusual or unexpected patterns in metrics.

**Method:**
- Statistical Thresholds (Z-score, IQR)
- Time-series Models (ARIMA, Prophet, STL)
- Control Charts (Shewhart, EWMA)
- ML-based Detectors (Isolation Forest, One-Class SVM, LSTM)

**Example:** “The anomaly detector flags that the drop is statistically significant.”

#### Root Cause Analysis

“Where did it happen?” - Identify dimensions, segments, or factors most responsible for anomalies.

**Method:**
- Multivariate Drilldowns
- Correlation & Variance Decomposition
- Feature Importance
- SHAP / LIME
- Clustering & Cohort Analysis
- Bayesian Network Reasoning

**Example:** “The drop mainly affects North American (region) mobile (device) users watching sports (content), starting right after the app update (timing).”

#### Attribution Analysis

“How much did each factor contribute?” - Quantify how much each factor contributes to the issue.

**Method:**
- Heuristic Models (First/Last-touch, Time-decay)
- Regression Models (OLS, Logistic)
- Shapley Value Attribution
- Markov Chain Attribution
- Analytic Hierarchy Process

**Example:** “About half the drop came from mobile issues, 1/3 from sports content, and the rest from the app version change.”

#### Casual Inference

“What truly caused it?” - Prove which factors actually caused the issue.

**Method:**
- Randomized Controlled Trials (A/B Tests)
- Propensity Score Matching
- Difference-in-Differences
- Instrumental Variables
- Regression Discontinuity
- Causal Machine Learning (Causal Forests, Double ML)
- Uplift Modeling

**Example:** “Users with the new app version watched 9% less than matched controls.”
