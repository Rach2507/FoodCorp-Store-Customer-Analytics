# 🛒 FoodCorp — Customer & Store Performance Analytics

> **SQL & Tableau Data Analytics Project | Customer Behaviour | KPI Analysis | Store Performance**

## 📊 Project Overview

This project analyses **FoodCorp's customer purchasing behaviour across four stores** to identify which store has the greatest potential for future marketing investment.

The core business problem was not simply to identify the largest-performing store, but to determine **which store has the greatest opportunity for growth** based on customer acquisition, customer activity, retention, purchasing behaviour and churn. FoodCorp can only focus its next major marketing campaign on **one store**, making data-driven store selection critical. 

Using **SQL**, seven key performance indicators (KPIs) were developed from transaction-level receipt data and then visualised in **Tableau** to compare performance across stores.

The analysis ultimately recommends increasing marketing investment in **Store 1**, despite its current weaker performance, because the store shows significant potential for improvement in customer acquisition and retention. 

---

# 🎯 Business Objective

FoodCorp wanted to determine:

> **Which of its four stores should receive the next major marketing investment to maximise future growth?**

Rather than automatically selecting the store with the highest current sales or customer count, the analysis considers:

* 👥 Monthly active customers
* 🔁 Active repeat customers
* 🆕 First-time customers
* 📅 Busiest purchasing days
* ⏱️ Time between customer orders
* 📉 Customer churn
* 📈 Customer cohort retention

These KPIs provide a broader view of **customer acquisition, engagement, retention and growth potential**.

---

# 🧰 Technologies & Tools

### 💻 SQL

SQL was used as the primary analytical tool for transforming raw receipt-level data into business-ready KPIs.

Key SQL capabilities demonstrated include:

* `SELECT`
* `COUNT()`
* `COUNT(DISTINCT)`
* `GROUP BY`
* `ORDER BY`
* `HAVING`
* `INNER JOIN`
* Self joins
* Subqueries
* `MIN()` / `MAX()`
* Date manipulation
* `DATE_TRUNC()`
* `DATE_PART()`
* `DATEDIFF()`
* `YEAR()`
* `MONTH()`
* `CASE` statements
* Cohort calculations

### 📊 Tableau

Tableau was used to transform the SQL outputs into visual business insights.

The report created Tableau visualisations for:

* Active Customers
* Active Repeat Customers
* First-Time Customers
* Busiest Day of the Week
* Time Between Orders
* Churn Rate
* Cohort Analysis  

### 🧠 Analytical Skills

This project demonstrates:

* Data extraction
* Data transformation
* KPI development
* Customer behaviour analysis
* Customer retention analysis
* Churn analysis
* Cohort analysis
* Comparative store analysis
* Data visualisation
* Business recommendation development

---

# 📌 Key Performance Indicators

## 1. 👥 Monthly Active Customers

### What it measures

The number of unique customers purchasing during a given month, analysed by store.

### Business purpose

This KPI helps determine whether a store's customer base is growing or declining and provides an indication of customer response to products and marketing activities.

### Key finding

**Store 3 had the highest number of active customers, while Store 1 had the lowest.** 

---

# 2. 🔁 Active Repeat Customers

### What it measures

Customers who purchased across more than one month.

### Business purpose

Repeat customers provide an indication of:

* Customer loyalty
* Customer satisfaction
* Repeat purchasing behaviour
* Potential customer value

### Key finding

**Store 3 performed strongest, while Store 1 performed weakest in terms of active repeat customers.** 

This makes repeat-customer behaviour particularly important when evaluating Store 1's long-term growth opportunity.

---

# 3. 🆕 First-Time Customers

### What it measures

The number of customers making purchases for the first time during a given period.

### Business purpose

First-time customers provide an indication of:

* Customer acquisition
* Market reach
* Growth potential
* Effectiveness of marketing activity

### Key finding

The analysis showed a similar pattern:

* 🥇 **Store 3** attracted the most customers.
* 🔻 **Store 1** attracted the fewest customers. 

This is an important finding because Store 1's weak customer acquisition represents both a current weakness and a potential opportunity for targeted marketing.

---

# 4. 📅 Busiest Day of the Week

### What it measures

The number of purchases occurring on each day of the week for each store.

### Business purpose

This KPI can support:

* 👨‍💼 Staff scheduling
* 📦 Inventory planning
* 💰 Labour-cost management
* 😊 Customer-service optimisation

### Key finding

**Store 3 consistently recorded higher purchasing activity throughout the week, while Store 1 lagged behind.** 

Understanding these purchasing patterns can help stores allocate staff and inventory more effectively.

---

# 5. ⏱️ Time Between Orders

### What it measures

The time between a customer's first and last purchase.

### Business purpose

This KPI helps FoodCorp understand:

* Customer purchasing frequency
* Potential future purchasing behaviour
* Customer engagement
* Potential churn risk
* Inventory requirements

The report specifically uses the time between first and last purchases as an indicator that can help gauge **future churn rates**. 

---

# 6. 📉 Customer Churn Rate

### What it measures

Customers who stop making purchases during the following quarter.

### Business purpose

Churn analysis helps FoodCorp understand:

* Customer retention
* Customer disengagement
* Effectiveness of campaigns
* Where resources may need to be allocated

### Key finding

An important contrast appeared in the analysis:

> **Store 3 experienced the highest customer churn, while Store 1 experienced the lowest.** 

However, this metric needs to be interpreted alongside customer acquisition and retention.

Store 1's low churn does **not necessarily mean strong performance**, because the store also has a relatively small customer base and weak acquisition.

---

# 7. 📈 Cohort Analysis

### What it measures

Cohort analysis tracks customers from their first purchase and examines whether they remain active over subsequent months.

### Business purpose

This provides insight into:

* Customer retention
* Long-term engagement
* Customer growth
* Store performance
* Retention trends

### Key findings

The analysis found:

* **Store 1 and Store 2** showed relatively consistent customer numbers.
* **Store 3** showed customer growth over time.
* **Store 1** showed a decline in customers over time. 

This provides a stronger indication of long-term customer behaviour than looking only at a single month's customer count.

---

# 🔎 Comparative Store Insights

| KPI                     | Best / Strongest Observation | Key Insight                             |
| ----------------------- | ---------------------------- | --------------------------------------- |
| 👥 Active Customers     | Store 3                      | Largest active customer base            |
| 🔁 Repeat Customers     | Store 3                      | Strongest repeat-customer performance   |
| 🆕 First-Time Customers | Store 3                      | Strongest customer acquisition          |
| 📅 Busy Days            | Store 3                      | Highest purchasing activity             |
| 📉 Churn                | Store 3 has highest churn    | Needs monitoring despite strong growth  |
| 📈 Cohort Retention     | Store 3 shows growth         | Strong long-term customer performance   |
| ⚠️ Overall Opportunity  | **Store 1**                  | Significant opportunity for improvement |

---

# 💡 Key Business Insights

## 🥇 Store 3 — Current High Performer

Store 3 is the strongest-performing store across several customer metrics.

It has:

* The highest active customer count
* Strong repeat-customer activity
* The highest first-time customer acquisition
* High purchasing activity
* Positive cohort growth

This indicates that Store 3 already has a strong customer base and established customer demand. 

However, Store 3 also has the **highest churn**, which means its strong acquisition and retention performance should not lead to complacency. 

---

# ⚠️ Store 1 — The Growth Opportunity

Store 1 consistently underperforms in terms of:

* Customer acquisition
* Monthly active customers
* Repeat customers
* Cohort retention
* Overall customer volume

At first glance, this might make Store 1 appear to be the least attractive investment.

However, the analysis takes a more strategic approach.

Store 1's low churn rate should not be interpreted as strong customer retention because the store has a comparatively small customer base. The report therefore considers Store 1's weak customer acquisition and declining cohort performance as evidence of a **significant opportunity for improvement through targeted marketing investment**. 

---

# 🎯 Final Business Recommendation

## Invest Marketing Budget in Store 1

The final recommendation is to **increase marketing spend on Store 1**.

The reasoning is based on Store 1's significant growth opportunity rather than its current performance.

### Recommended strategy:

**1. 🚀 Increase customer acquisition**

Use targeted marketing campaigns to attract new customers to Store 1.

**2. 🔁 Improve repeat purchasing**

Use customer-retention strategies to convert new customers into repeat customers.

**3. 📈 Increase monthly active customers**

Set measurable targets for growth in active customers.

**4. 🧠 Learn from higher-performing stores**

Store 1 should analyse and adopt successful practices from Store 3, Store 2 and Store 0.

**5. 💰 Measure campaign impact**

Track active customers, repeat customers and retention after the marketing investment to determine whether the campaign is producing sustainable growth.

The report recommends that Store 1 use the additional marketing investment to attract customers and increase both **monthly active customers and active repeat customers**. 

---

# 🔄 Analytical Workflow

```text
                RAW RECEIPT DATA
                       │
                       ▼
              🔍 SQL DATA ANALYSIS
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
      Customer      Purchase      Store
      Analysis      Behaviour    Analysis
          │            │            │
          └────────────┼────────────┘
                       ▼
                  📊 7 KPIs
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
     Customer       Retention       Store
     Activity       & Churn       Comparison
        │              │              │
        └──────────────┼──────────────┘
                       ▼
                📈 TABLEAU
                VISUALISATION
                       │
                       ▼
                💡 BUSINESS
                  INSIGHTS
                       │
                       ▼
             🎯 MARKETING DECISION
                       │
                       ▼
               INVEST IN STORE 1
```

---

# 🧪 SQL Analytical Techniques

This project demonstrates practical SQL skills including:

### Data Aggregation

```sql
COUNT()
COUNT(DISTINCT)
MIN()
MAX()
```

### Date Analysis

```sql
DATE_TRUNC()
DATE_PART()
DATEDIFF()
YEAR()
MONTH()
```

### Data Filtering

```sql
WHERE
HAVING
CASE
```

### Data Relationships

```sql
INNER JOIN
SELF JOIN
SUBQUERIES
```

### Customer Analytics

The SQL analysis was used to calculate:

* Customer activity
* Repeat purchasing
* First-time customers
* Purchase frequency
* Churn
* Customer cohorts

---

# 📊 Tableau Dashboard & Visualisation

SQL outputs were visualised in Tableau to make the analysis easier to interpret from a business perspective.

The visualisation layer covered:

📌 Active Customers
📌 Active Repeat Customers
📌 First-Time Customers
📌 Busiest Day of the Week
📌 Time Between Orders
📌 Churn Rate
📌 Cohort Analysis

---

### 🗄️ Data Extraction & Transformation

* Writing analytical SQL queries
* Joining datasets
* Filtering data
* Aggregating transactional records
* Creating calculated metrics

### 📊 KPI Development

* Translating business questions into measurable KPIs
* Defining KPI formulas
* Comparing KPIs across business units

### 👥 Customer Analytics

* Customer acquisition analysis
* Repeat-customer analysis
* Customer retention
* Churn analysis
* Cohort analysis
* Purchasing behaviour

### 📈 Data Visualisation

* Tableau dashboard development
* Comparative analysis
* Trend identification
* Business-focused reporting

### 🧠 Business Intelligence

* Identifying underperforming locations
* Identifying growth opportunities
* Comparing store performance
* Translating analytical results into strategic recommendations

### 🎯 Decision Support

The project demonstrates how data can be used to answer a practical business question:

> **Where should FoodCorp invest its next marketing budget?**

---

> 💡 **Data analysis is not just about describing what happened — it is about using evidence to decide what should happen next.**
