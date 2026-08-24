# Monthly-Marketing-Performance-Report
<img width="1383" height="986" alt="image" src="https://github.com/user-attachments/assets/bb63d906-a539-4b42-b6bc-d2ebbfdc1725" />
# Monthly Marketing Performance Report

An interactive **Tableau dashboard** for analyzing marketing performance across channels, geographies, and device operating systems.

The dashboard helps evaluate marketing efficiency, identify underperforming and high-performing segments, and translate analytical findings into actionable budget and campaign recommendations.

**Tool:** Tableau
**Dashboard:** [Tableau Public — Monthly Marketing Performance Report](https://public.tableau.com/app/profile/viktoriia.kazniienko/viz/Marketing_17791308941530/Marketing?publish=yes)

---

## 📊 Project Overview

The goal of this project was to build a marketing performance monitoring dashboard that answers key business questions:

* How much was spent on marketing and how much revenue was generated?
* Are marketing investments paying off?
* Which channels perform best and worst?
* Which geographical markets generate the highest returns?
* How does performance differ across device operating systems?
* Where should the marketing budget potentially be reallocated?

The dashboard combines high-level KPIs with trend analysis and detailed segmentation by **channel, geography, and device OS**.

---

## 🎯 Key KPIs

The dashboard tracks five core marketing metrics:

| KPI               | Definition                               | Purpose                            |
| ----------------- | ---------------------------------------- | ---------------------------------- |
| **Total Spend**   | Total marketing expenditure              | Measures investment volume         |
| **Total Revenue** | Revenue attributed to marketing activity | Measures generated revenue         |
| **ROAS**          | Revenue / Spend                          | Measures advertising efficiency    |
| **CVR**           | Paying users / Total users               | Measures conversion quality        |
| **CAC**           | Spend / Acquired users                   | Measures customer acquisition cost |

Each KPI card also displays the **Month-over-Month (MoM)** change to track recent performance dynamics.

---

## 📈 Dashboard Structure

### 1. KPI Overview

The top section provides a quick overview of:

* Total Spend
* Total Revenue
* ROAS
* CVR
* CAC
* MoM changes

This section is designed to quickly identify positive or negative changes in marketing performance.

---

### 2. ROAS & Spend Trend

A combined monthly chart shows:

* **Spend** as bars
* **ROAS** as a line

The chart covers the full 2025 year and helps identify situations where marketing investment increases while efficiency decreases.

This allows potential seasonal patterns and long-term performance trends to be identified.

---

### 3. Top Channel by ROAS

A dedicated KPI highlights the channel with the highest ROAS for the selected period.

For December 2025:

**Email — 2.28x ROAS**

Email was the only analyzed channel with ROAS above 1x, making it the strongest-performing channel in the dataset.

---

### 4. Spend & Revenue by Channel

A grouped bar chart compares **Spend** and **Revenue** for:

* Email
* Google
* Meta
* TikTok

ROAS is displayed as an additional label.

This visualization makes it possible to evaluate both:

* the **scale** of a channel;
* its **efficiency**.

Looking only at ROAS can be misleading because a channel may have a high ROAS while operating with a very small budget.

---

### 5. ROAS by Geography & Channel

A heatmap shows ROAS across:

**Geographies:**

* UA
* PL
* DE
* US
* UK

**Channels:**

* Email
* Google
* Meta
* TikTok

This helps identify high- and low-performing combinations of market and acquisition channel.

For example, Email performs particularly well in the UK, while TikTok demonstrates very low ROAS across the analyzed geographies.

---

### 6. Conversion & Revenue by Device OS

Two horizontal bar charts compare:

* Conversion Rate (CVR)
* Average Revenue per User (ARPU)

across:

* Android
* iOS
* Web

The analysis shows relatively similar CVR between operating systems, while **iOS demonstrates the highest ARPU** in the analyzed dataset.

---

# 🔎 Key Findings

The following findings are based on the December 2025 dashboard snapshot.

### Overall Marketing Performance

| Metric        | December 2025 |
| ------------- | ------------: |
| Total Spend   |   **2.22M ₴** |
| Total Revenue |   **72.1K ₴** |
| ROAS          |     **0.42x** |
| MoM Revenue   |       **+4%** |
| MoM ROAS      |      **-22%** |

The overall ROAS of **0.42x** indicates that attributed revenue was lower than advertising spend during the analyzed period.

At the same time, revenue increased by **4% MoM**, while ROAS declined by **22%**, indicating that marketing efficiency deteriorated despite revenue growth.

---

## 📌 Channel Performance

| Channel    |      ROAS | Assessment                    |
| ---------- | --------: | ----------------------------- |
| **Email**  | **2.28x** | Highest-performing / above 1x |
| **Google** | **0.94x** | Close to breakeven            |
| **Meta**   | **0.31x** | Underperforming               |
| **TikTok** | **0.09x** | Critically underperforming    |

### Main observation

**Email is the only analyzed channel with ROAS above 1x.**

Google is close to breakeven, while Meta and TikTok generate substantially lower returns relative to spend.

---

## 🌍 Geography Insights

Email demonstrates the strongest performance across all analyzed geographies.

The highest Email ROAS was observed in:

**UK — 3.14x**

Other strong Email results included:

* US — 2.77x
* DE — 2.69x
* PL — 2.06x
* UA — 1.26x

TikTok was the weakest-performing channel across all analyzed geographies.

---

## 📱 Device Insights

The analysis of device operating systems showed:

* **iOS** — highest ARPU
* **Android** — medium ARPU
* **Web** — lowest ARPU

CVR differences between operating systems were relatively small, suggesting that the main difference between segments is associated with revenue per user rather than conversion rate.

The results provide a hypothesis for further investigation of iOS users, particularly in terms of retention and LTV.

---

# 💡 Recommendations

Based on the observed performance, the following actions were proposed.

| Channel    | Recommendation                             | Rationale                             |
| ---------- | ------------------------------------------ | ------------------------------------- |
| **Email**  | Test increasing budget by 30–50%           | Highest ROAS at 2.28x                 |
| **Google** | Maintain budget and run optimization tests | ROAS of 0.94x is close to breakeven   |
| **Meta**   | Reduce spend by ~20%                       | ROAS of 0.31x                         |
| **TikTok** | Stop or significantly reduce spend         | ROAS of 0.09x across analyzed markets |

Additional recommendations:

* Investigate scaling opportunities for Email in **UK and US**.
* Review the performance of **UA** separately due to consistently lower results.
* Explore more targeted campaigns for **iOS** users because of their higher ARPU.
* Monitor CAC and ROAS when reallocating budget rather than increasing spend solely based on historical ROAS.

---

# ⚠️ Assumptions & Limitations

### TikTok Attribution

The very low TikTok ROAS across all geographies may indicate either:

1. genuinely poor channel performance; or
2. attribution limitations.

For example, a last-click attribution model may not capture assisted or view-through conversions.

Therefore, TikTok performance should be additionally validated using alternative attribution approaches before making a final decision to completely discontinue the channel.

### ARPU vs. LTV

The dashboard compares **Average Revenue per User (ARPU)** across operating systems.

Higher ARPU does not automatically mean higher LTV. A separate retention and lifetime value analysis would be required before making long-term targeting decisions.

### Budget Scaling

Historical ROAS alone is not sufficient to determine the optimal budget increase. Before significantly scaling a channel, marginal ROAS, CAC, and potential diminishing returns should also be evaluated.

---

# 🛠️ Tools

* **Tableau Public** — dashboard development and interactive data visualization
* **Data analysis** — KPI calculation, trend analysis, segmentation and performance comparison

---

# 📷 Dashboard Preview

The dashboard provides interactive filters for:

* Month
* Channel
* Device OS
* Geography

Users can move from a high-level KPI overview to detailed channel, geography, and device-level analysis.

---

# 🚀 Business Value

This project demonstrates a data-driven approach to marketing and product analytics:

**Raw Data → KPIs → Segmentation → Performance Analysis → Business Insights → Recommendations**

The dashboard is designed not only to visualize marketing data, but also to support decisions around:

* marketing budget allocation;
* channel optimization;
* campaign performance;
* geographic targeting;
* customer acquisition efficiency.

---

## 👩‍💻 Author

**Viktoriia Kazniienko**
[Tableau Public](https://public.tableau.com/app/profile/viktoriia.kazniienko)
