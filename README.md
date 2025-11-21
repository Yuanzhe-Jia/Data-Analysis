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

- Business Analysis: setting KPIs; drill down KPIs by different dimensions; competitor analysis; financial forecast/break-even.
- Marketing Analysis: vendor anslysis; channel analysis; marketing campaign analysis; ROI definition and calculation; A/B test.
- Product Analysis: funnel/churn anslysis; AARRR; user journey analysis; functionality analysis; A/B test.
- Operation Analysis: content analysis; user persona analysis; user segmentation; user life-time value.
- Financial Analysis: P&L forecast/break-even analysis; balance sheet/profit and loss statement/cash flow statement.

### Data Analysis Framework

Imagine a metric — Average Minutes Per Page — suddenly drops 12% in the last week.
You need to figure out what happened, why, and how to fix.

#### Anomaly Detection

“What changed?” - Detect unusual or unexpected patterns in metrics.

**Method:**
- Statistical thresholds (z-score, IQR)
- Time-series models (ARIMA, Prophet, STL decomposition)
- Control charts (Shewhart, EWMA)
- ML-based detectors (Isolation Forest, One-Class SVM, LSTM Autoencoder)

**Finding:** “The anomaly detector flags that the drop is statistically significant.”

#### Root Cause Analysis

“Where did it happen?” - Identify dimensions, segments, or factors most responsible for anomalies.

**Method:**
- Multivariate drilldowns
- Correlation & variance decomposition
- Decision trees / random forests (feature importance)
- SHAP / LIME explainability
- Clustering and cohort analysis
- Bayesian network reasoning

**Finding:** “The drop mainly affects North American (region) mobile (device) users watching sports (content), starting right after the app update (timing).”

#### Attribution Analysis

“How much did each factor contribute?” - Quantify how much each factor contributes to the issue.

**Method:**
- Heuristic models (first/last-touch, time-decay)
- Regression-based models (OLS, logistic, hierarchical)
- Shapley Value Attribution (game theory)
- Markov Chain Attribution (path-based)
- Analytic Hierarchy Process

**Finding:** “About half the drop came from mobile issues, 1/3 from sports content, and the rest from the app version change.”

#### Casual Inference

“What truly caused it?” - Prove which factors actually caused the issue.

**Method:**
- Randomized Controlled Trials (A/B Tests)
- Propensity Score Matching (PSM)
- Difference-in-Differences (DiD)
- Instrumental Variables (IV)
- Regression Discontinuity (RD)
- Causal Machine Learning (Causal Forests, Double ML, Meta-learners)
- Uplift Modeling

**Finding:** “users with the new app version watched 9% less than matched controls.”
