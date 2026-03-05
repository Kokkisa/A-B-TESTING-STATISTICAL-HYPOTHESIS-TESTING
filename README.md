# A-B-TESTING-STATISTICAL-HYPOTHESIS-TESTING
Design, analyze, and interpret A/B tests using statistical methods. #          Determine if changes actually improve business metrics.
[README_project8.md](https://github.com/user-attachments/files/25756174/README_project8.md)
# 🧪 A/B Testing & Statistical Hypothesis Testing

## Overview
Statistical analysis project covering the complete A/B testing workflow: hypothesis formulation, test selection (Z-test, T-test, Chi-square), power analysis, confidence intervals, effect size, and multiple testing correction. Demonstrates rigorous statistical decision-making for product and business experiments.

**Built by:** Nithin Kumar Kokkisa — Senior Demand Planner with 12+ years in manufacturing operations & supply chain analytics.

---

## Business Problem
Companies make hundreds of product decisions — new checkout pages, recommendation algorithms, button colors, pricing changes. Without A/B testing, these decisions are based on gut feeling. This project demonstrates how to statistically validate whether a change actually improves business metrics or if observed differences are just random noise.

## Three Test Scenarios

### Scenario 1: Checkout Page Redesign (Z-Test)
- **Question:** Does the new checkout page increase conversion rate?
- **Test:** Z-test for proportions (binary outcome: converted/not)
- **Groups:** 5,000 control + 5,000 treatment visitors

### Scenario 2: Recommendation Algorithm (T-Test)
- **Question:** Does the new algorithm increase average order value?
- **Test:** Independent samples t-test (continuous outcome: dollar amount)
- **Metric:** Average order value (AOV)

### Scenario 3: Button Color Impact (Chi-Square)
- **Question:** Does button color affect purchase behavior?
- **Test:** Chi-square test of independence (categorical × categorical)
- **Groups:** Red vs Blue vs Green buttons

## Key Concepts Demonstrated

| Concept | Description |
|---------|-------------|
| Hypothesis Testing | H₀/H₁ framework, p-values, significance levels |
| Z-Test | Comparing proportions (conversion rates) |
| T-Test | Comparing means (revenue, order values) |
| Chi-Square | Testing independence of categorical variables |
| Confidence Intervals | Range of plausible effect sizes |
| Effect Size (Cohen's d) | Practical vs statistical significance |
| Power Analysis | Calculating required sample size before testing |
| Bonferroni Correction | Adjusting for multiple comparisons |
| Common Pitfalls | Peeking, novelty effect, Simpson's paradox |

## Visualizations

| Chart | Insight |
|-------|---------|
| Conversion Rate Comparison | Side-by-side A/B group performance |
| Z-Test Normal Curve | Rejection regions and observed statistic |
| Distribution Overlap | T-test visual comparison of group means |
| Chi-Square Results | Purchase rates by button color |
| Power Curve | Sample size vs detection probability trade-off |

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **SciPy** (stats module: Z-test, T-test, Chi-square)

---

## About
Part of a **30-project data analytics portfolio**. See [GitHub profile](https://github.com/Kokkisa) for the full portfolio.

**Previous Projects:**
- [Project 1 — Demand Forecasting with Prophet](https://github.com/Kokkisa/demand-forecasting-prophet)
- [Project 2 — ARIMA vs Prophet vs ETS](https://github.com/Kokkisa/forecasting-model-comparison)
- [Project 3 — Customer Churn Prediction with SHAP](https://github.com/Kokkisa/customer-churn-prediction)
- [Project 4 — SQL Business Analytics](https://github.com/Kokkisa/sql-business-analytics)
- [Project 5 — Interactive Sales Dashboard](https://github.com/Kokkisa/sales-analytics-dashboard)
- [Project 6 — Sentiment Analysis NLP](https://github.com/Kokkisa/sentiment-analysis-nlp)
- [Project 7 — Customer Segmentation K-Means](https://github.com/Kokkisa/customer-segmentation-kmeans)
