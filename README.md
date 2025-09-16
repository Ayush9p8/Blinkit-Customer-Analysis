# Blinkit Customer Analysis

This project explores how a customer’s **first negative review** impacts their subsequent buying behavior on **Blinkit**, a leading Indian quick-commerce platform delivering groceries and essentials. Using a synthetic dataset from Kaggle, the analysis applies data preparation, visualization, and statistical methods to uncover **behavioral patterns and business insights**.

---

## 📊 Project Overview

* **Goal:** Understand the effect of negative reviews on customer spending.
* **Dataset:** Synthetic Blinkit dataset (customers, orders, reviews) from Kaggle.
* **Tools:** Python (Pandas, NumPy), Excel, Matplotlib/Seaborn.
* **Key Metric:** Average Order Value (AOV) before vs. after the first negative review.
* **Methods:** Data cleaning, merging tables, sentiment filtering, paired t-test, visualization.

---

## 🔑 Methodology

1. **Data Preparation**

   * Merged customers, orders, and reviews.
   * Identified each customer’s **first negative review**.
   * Created 30-day windows: **Before Review, Review Day, After Review**.

2. **Metrics**

   * Calculated **Average Order Value (AOV)** before vs. after review.
   * Additional descriptive metrics: review participation, sentiment distribution.

3. **Visualization**

   * Boxplots and charts comparing AOV before vs. after reviews.
   * Distribution of ratings and review categories (delivery vs. product quality).

4. **Statistical Testing**

   * Applied **paired t-test** on before/after AOV.
   * Reported one-tailed p = 0.048 → suggested significant increase in AOV.

---

## 📈 Key Findings

* **High Review Participation:** \~86% of customers left reviews; \~33% were negative.
* **Sentiment vs. Spending:** Minimal correlation (–0.007) between review sentiment and spending.
* **Review Topics:**

  * Delivery dominates overall reviews.
  * **Product quality** is the main driver of negative sentiment.
* **Ratings Distribution:** Average rating ≈ 3.3; product-related reviews skew lowest.
* **Post-Review Spending:**

  * 55% of customers **increased their AOV** (Rs 735 → Rs 868).
  * \~30% churned (stopped ordering within 30 days).
* **Business Insight:** Negative reviews don’t always reduce revenue — but product quality issues cause risk for a minority.

---

## ⚠️ Limitations

* Dataset is **synthetic** (not actual Blinkit data).
* Sentiment classification taken as ground truth.
* **First negative review** treated as key event (may not reflect all behavior).
* 30-day window may miss longer-term effects.
* **One-tailed test** → significance claim (p = 0.048) is marginal; two-tailed test would not be significant.
* Lacks **control group** (e.g., customers without reviews).
* Focus only on AOV, ignoring frequency and lifetime value.

---

## 🚀 Recommendations

* **Improve Product Quality:** Tackle packaging, freshness, and supplier issues.
* **Customer Recovery:** Proactively engage \~30% at-risk customers after negative feedback.
* **Feedback Monitoring:** Use text analytics for real-time complaint tracking.
* **Retention Strategy:** Segment customers (spending ↑ vs. churn) and tailor interventions.
* **Leverage Convenience:** Highlight Blinkit’s speed and reliability to maintain loyalty.

---

## 🔮 Future Enhancements

* Use **real Blinkit data** (with seasonality, diversity).
* Expand metrics: order frequency, lifetime value, churn probability.
* Apply **two-tailed tests** or regression models for robustness.
* Add **control groups** (customers with positive/no reviews).
* Build interactive dashboards (Power BI, Tableau, Streamlit).
* Enhance storytelling with time-series, heatmaps, and Sankey charts.

---

## 📂 Portfolio Opportunities

* Publish a **blog post / case study**: “Do Negative Reviews Hurt Sales?”
* Create an **interactive dashboard** for customer review analysis.
* Share a **clean Jupyter Notebook** with reproducible code.
* Develop **slides/infographics** summarizing findings.
* Record a **video walkthrough** of methods & insights.

---

## 🛠️ Tech Stack

* **Languages:** Python (Pandas, NumPy, Matplotlib, Seaborn)
* **Tools:** Excel, Jupyter Notebook
* **Stats:** Paired t-test, descriptive statistics

---

## 📌 Key Insight

> Negative reviews don’t automatically reduce customer spending.
> Many continue ordering — but **product quality is the top driver of dissatisfaction** and the main churn risk.

---

