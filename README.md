# 🛒 Ecommerce Customer Churn & RFM Analysis

## 📂 Dataset
Brazilian E-Commerce Public Dataset by Olist —
[🔗 Download from Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 📌 Overview
99K+ ecommerce orders. 90% churn rate.

This project digs into **why customers are leaving** and uses **RFM Segmentation** to find who can still be saved — built entirely in PostgreSQL, Python, and Power BI.

---

## 🛠️ Tech Stack
- **PostgreSQL** — 9 tables joined via SQL to build master dataset
- **Python & Pandas** — RFM scoring & churn segmentation
- **Power BI** — DAX measures + Power Query + 3-page dashboard

---

## 📈 Numbers That Matter
| Metric | Value |
|--------|-------|
| Total Customers | 99K |
| Active Customers | 9.4K |
| Churn Rate | 90.51% |
| Revenue Lost | 14M |

> Customers inactive for **more than 90 days** were marked as Churned.

---

## 👥 Customer Segments

| Segment | Count |
|---------|-------|
| 🌱 Potential Loyalist | 24,078 |
| 🔴 At Risk | 24,058 |
| 💛 Loyal | 16,605 |
| 💀 Lost | 15,699 |
| 🔘 Others | 11,765 |
| 👑 VIP | 7,236 |

---

## 🔍 Key Insights

**🔴 At Risk (24%) — Biggest Problem**
- Shopped regularly before — but suddenly went silent
- High frequency in past but recency has dropped sharply
- Most likely to churn permanently if not contacted within weeks

**🌱 Potential Loyalist (24%) — Biggest Opportunity**
- Recent customers who visited only once or twice
- They had a decent experience — just need a reason to return
- One good offer at the right time can convert them into loyal buyers

**👑 VIP (7%) — Most Valuable**
- Only 7% of total customers but driving 40-50% of revenue
- High recency, high frequency, highest spend — your best customers
- Losing even a few VIPs can significantly impact total revenue

**💛 Loyal (17%) — Your Backbone**
- Come back regularly and trust the brand
- Not spending as much as VIPs — but extremely consistent
- Best candidates to be pushed into VIP with right incentives

**💀 Lost (16%) — Hard to Recover**
- Came long ago — never returned — low frequency too
- Delivery experience was likely poor from the start
- Very low ROI on marketing — budget better spent elsewhere

**🔘 Others (12%) — Undefined**
- Did not clearly fit into any RFM segment
- Mixed behavior — need deeper individual level analysis
- Could belong to any segment after re-scoring

---

## 🚨 Root Cause of Churn
After analyzing delivery data across all segments —
**Late deliveries are the #1 reason customers are not coming back.**

Churned customers (At Risk + Lost) showed significantly higher
delivery delays compared to active segments.

> Fix logistics first — no campaign will work if delivery experience is broken.

---

## 💰 Revenue Concentration
Top 20% of customers are driving the majority of total revenue.

> Losing one VIP customer = Losing revenue of 5 regular customers.
> Retention budget should always prioritize the top 20%.

---

## 📊 Dashboard

### Executive Overview
![Overview](screenshots/ECOMMERCE%20PAGE%201.png)

### RFM Segmentation
![RFM](screenshots/ECOMMERCE%20PAGE%202.png)

### Revenue Analysis
![Revenue](screenshots/ECOMMERCE%20PAGE%203.png)

---

If you found this project interesting or have feedback, feel free to connect on [LinkedIn](https://www.linkedin.com/in/sohil-khalifa-5246052b9/) or raise an issue in this repo!
