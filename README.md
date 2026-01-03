# Monthly-Financial-Performance-Analysis
A finance-forward analytical case study focused on variance decomposition, cost behavior, and performance drivers that is built to mirror real-world Finance Business Partner and Financial Analyst work.

**Goals and Purpose of this project**

Most financial dashboards stop at what happened.

This project goes further to explain why it happened.

Using a structured variance analysis approach, this case study decomposes financial performance into volume, efficiency, and cost-driver effects**, turning raw numbers into decision-ready insights.

##  Core analytical questions answered

This project was built to answer four executive-level questions:

1. Where is performance deviating from expectations?
2. Is variance driven by volume, efficiency, or cost behavior?
3. Which regions and departments are structural underperformers vs one-off issues?
4. How do costs behave as activity volume scales?

## Key insights

## 1. Revenue variance is structurally concentrated — not random

* Revenue variance analysis by **region and department** shows that underperformance clusters in specific combinations, rather than being evenly distributed.
* This immediately signals **structural issues**, not temporary noise.
* The dashboard highlights the **three worst-performing units**, forcing prioritization instead of broad, unfocused action.

**Insight:** Management should focus intervention on repeat underperformers, not spread effort evenly.

### 2️. Volume vs efficiency separation prevents the wrong conclusions

* Variance was intentionally decomposed into:

  * **Volume-driven effects** (changes in activity levels)
  * **Efficiency-driven effects** (cost per unit behavior)

This avoids a common mistake: blaming teams for efficiency issues that are actually volume-related.

**Insight:** Some negative variances disappear once normalized for volume — proving performance wasn’t operationally weak, just under-utilized.

### 3️. Cost per unit remains flat across volume which is a quiet red flag

A scatter plot of **Cost per Unit vs Activity Volume** revealed:

* No meaningful downward trend as volume increases
* Weak or absent economies of scale
* Cost dispersion remains wide even at higher activity levels

**Insight:** Fixed costs are not being leveraged effectively. Scaling volume alone will not materially improve margins without cost structure changes.

### 4️. Low-volume operations are cost-inefficient by design

By grouping operations into **volume buckets**, we found:

* Low-volume buckets carry disproportionately higher:

  * Labour costs
  * Maintenance overhead
  * Other semi-fixed costs

**Insight:** Cost inefficiency at low volumes is structural, not managerial. Decisions here should be strategic (consolidation, automation, or minimum-volume thresholds).

## 📈 Visualizations included
* Revenue Variance by Region & Department (with worst performers highlighted)
* Cost per Unit vs Activity Volume (with trend interpretation)
* Cost Driver Composition by Volume Bucket (stacked analysis)
* Volume-based segmentation to isolate structural cost behavior

## 🛠️ Tools & techniques

* **Python**
* **Pandas** — data transformation, grouping, variance calculations
* **Matplotlib** — clean, presentation-ready visualizations
* **Jupyter Lab** — reproducible, explainable analysis

Analytical techniques:

* Variance analysis
* Volume vs efficiency decomposition
* Cost driver analysis
* Bucketing and normalization
* Executive-focused data storytelling

## 🧩 What this project demonstrates

✔ Strong finance fundamentals
✔ Business-first analytical thinking
✔ Ability to translate numbers into strategy
✔ Clean, interview-ready storytelling
✔ Real-world FP&A and Finance Partner mindset

This is not a charting exercise — it’s a **decision-support analysis**.


*Built as part of a personal portfolio to demonstrate applied financial analysis skills in a real-world context.*
