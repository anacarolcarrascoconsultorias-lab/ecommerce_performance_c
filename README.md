# E-commerce Retention & Cohort Analysis (Option C)

## 📌 Project Overview
This project analyzes **customer retention behavior** in an e-commerce dataset using **cohort analysis**.  
The goal is to understand how long customers continue purchasing after their first order and how retention evolves over time.

Rather than focusing on revenue or customer value alone, this analysis explores **behavioral decay**, repeat purchasing patterns, and long-term engagement.

---

## 🎯 Business Questions
- How many customers return after their first purchase?
- How quickly does retention decline over time?
- Are there meaningful differences between early and later cohorts?
- What does “average retention” look like at Month 1, Month 3, and Month 6?

---

## 🧠 Methodology

### Cohort Definition
- **Cohort Month** = the month of a customer’s **first invoice**
- Customers are grouped by their first purchase month
- Retention is measured by **months since first purchase**

### Cohort Matrix Construction
- Rows: Cohort Month (YYYY-MM)
- Columns: Months Since Cohort (0–12)
- Values: Count of active customers per cohort per month
- Retention % calculated relative to Month 0 (cohort size)

This structure allows clear comparison of retention decay across cohorts.

---

## 📊 Key Metrics (Average Across Cohorts)
- **Month 1 Retention:** ~19%
- **Month 3 Retention:** ~18%
- **Month 6 Retention:** ~13%

These KPIs highlight a **steep early drop-off** followed by a long-tail of retained customers.

---

## 📈 Dashboard Highlights
The dashboard includes:
- Cohort retention heatmap
- Average retention curve over time
- Key retention KPIs for Month 1, 3, and 6

The visualizations emphasize **behavioral patterns**, not just totals.

---

## 🔍 Key Insights
- Most customer churn happens immediately after the first purchase
- A smaller but consistent group of customers remains active long-term
- Retention stabilizes after the early months, forming a predictable decay curve
- Improving early post-purchase engagement would have the largest impact

---

## 🛠 Tools Used
- Google Sheets
- Advanced formulas (`QUERY`, `FILTER`, `COUNTUNIQUE`)
- Cohort analysis & retention modeling
- Data visualization & dashboard design

---

## 📁 Files
- Google Sheets (analysis & dashboard) [HERE](https://docs.google.com/spreadsheets/d/1KfhLBSmYfYIWszZiBQ5lJgKe6jtosoChNvV0B10gUDU/edit?usp=sharing)
- Cohort matrices (counts and retention)

---

## 🚀 Why This Project Matters
Retention analysis is critical for subscription, marketplace, and e-commerce businesses.  
This project demonstrates the ability to:
- Translate raw transactional data into behavioral insights
- Design cohort-based analytical models
- Communicate retention patterns clearly to non-technical stakeholders
