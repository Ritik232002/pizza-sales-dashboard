# 🍕 Pizza Sales Dashboard — Business Analysis

An end-to-end sales analysis project built to answer practical business questions from pizza transaction data using **Excel, SQL, and Power BI**.

The goal is not just to display KPIs, but to turn transactional sales data into a clear business story: **how the business is performing, which products drive revenue, which products underperform, what categories and sizes contribute most, and when demand is highest.**

---

## 📌 Business Problem

Raw transaction data can show what was sold, but it does not immediately explain what the business should pay attention to.

This analysis was designed to answer questions such as:

- Which products generate the most revenue?
- Which products contribute the least?
- Which pizza category contributes the most revenue?
- Which pizza size drives revenue?
- Which days have the highest order volume?
- How does order volume change across months?

The dashboard combines these answers into an interactive Power BI view for faster business interpretation.

---

## 📊 Business Questions & Findings

### 1. How is the business performing overall?

**Answer:**

- **Total Revenue:** 817.86K
- **Total Orders:** 21.35K
- **Total Pizzas Sold:** 49.57K
- **Average Order Value:** 38.31
- **Average Pizzas per Order:** 2.32

These KPIs provide the baseline for evaluating product, category, size, and time-based performance.

<img width="680" height="105" alt="01_overall_kpis" src="https://github.com/user-attachments/assets/a279ebc3-cc34-4fb8-a0f9-4221af50a311" />


---

### 2. Which pizzas generate the most revenue?

**Answer:**

The highest-revenue pizza in the analysis is **Thai Chicken Pizza**, generating approximately **43.43K** in revenue.

Other strong performers include:

<img width="215" height="140" alt="02_top_revenue_pizzas" src="https://github.com/user-attachments/assets/8b3d694a-6ccb-47c5-9e14-aced8349866a" />


This identifies the products with the strongest revenue contribution in the analyzed period.

---

### 3. Which pizzas underperform on revenue?

**Answer:**

Examples of lower-revenue products include:

- **Brie Carre Pizza:** ~11.6K
- **Green Garden Pizza:** ~14.0K
- **Spinach Supreme Pizza:** ~15.3K

These products are useful candidates for deeper investigation into demand, pricing, menu placement, and product mix.

<img width="215" height="135" alt="03_bottom_revenue_pizzas" src="https://github.com/user-attachments/assets/68b8a2c0-40a1-4e0f-8799-a3f93134d6f5" />

---

### 4. Which pizza category contributes the most revenue?

**Answer:**

The **Classic** category contributes the largest share of revenue at **26.91%**.

Revenue contribution by category:

| Category | Revenue Share |
|---|---:|
| Classic | 26.91% |
| Supreme | 25.46% |
| Chicken | 23.96% |
| Veggie | 23.68% |

The category mix is relatively balanced, with Classic leading by a small margin.

<img width="215" height="165" alt="04_category_revenue" src="https://github.com/user-attachments/assets/e90dbbd4-9e21-423b-bd06-14002d86bf9b" />

---

### 5. Which pizza size drives revenue?

**Answer:**

**Large pizzas** generate the highest revenue contribution at **45.89%**.

The combined contribution of **Large + Medium pizzas is 76.38%**, making these two sizes the dominant part of the revenue mix.

| Size | Revenue Share |
|---|---:|
| Large | 45.89% |
| Medium | 30.49% |
| Small | 21.77% |
| XL | 1.72% |
| XXL | 0.12% |

<img width="230" height="165" alt="05_size_revenue" src="https://github.com/user-attachments/assets/a26c6d4a-68c8-42e8-839a-88e46044b2db" />

---

### 6. Which day generates the most orders?

**Answer:**

**Friday** records the highest order volume at approximately **3,538 orders** among the displayed weekdays.

**Sunday** records the lowest at approximately **2,624 orders**.

The day-level trend helps identify differences in demand across the week and can support operational planning such as staffing and preparation capacity.

<img width="325" height="150" alt="06_daily_orders" src="https://github.com/user-attachments/assets/f935acca-a25d-46bb-bb29-2287ffad36a8" />

---

### 7. Which months have the highest and lowest order volumes?

**Answer:**

- **July:** highest monthly order volume at approximately **1,935 orders**
- **September:** lowest monthly order volume at approximately **1,661 orders**

This shows variation in monthly demand within the analyzed period. With one year of data, these differences should be treated as observed variation rather than proof of recurring seasonality.

<img width="335" height="150" alt="07_monthly_orders" src="https://github.com/user-attachments/assets/3d68f949-4d1b-4232-a7c7-9d3ca840bc79" />

---

## 🔎 What the Analysis Tells the Business

The analysis provides a practical view of where sales are concentrated:

- Revenue is concentrated across a group of stronger-performing products.
- Classic pizzas have the largest category revenue share, although the category mix is relatively balanced.
- Large and Medium sizes account for most revenue.
- Order demand varies across weekdays and months.
- Lower-performing products can be isolated for further investigation instead of treating the menu as one uniform portfolio.

The dashboard therefore acts as a **decision-support layer over the raw transaction data**, rather than simply presenting charts.

---

## 🛠️ Tools & Workflow

**Excel** → data inspection, validation, and preprocessing  
**SQL** → aggregation, filtering, grouping, KPI calculations, product/category/size/time analysis  
**Power BI** → interactive dashboard and business storytelling  
**GitHub** → project versioning and documentation

### Workflow

```text
Raw Transaction Data
        ↓
Data Validation & Preparation (Excel)
        ↓
Business Analysis & Aggregation (SQL)
        ↓
Interactive Dashboard (Power BI)
        ↓
Business Findings & Recommendations
```

---

## 📂 Repository Structure

```text
pizza-sales-dashboard/
│
├── Dataset/
├── SQL Queries/
├── Power BI Dashboard/
├── Dashboard Screenshots/
├── Project Report/
└── README.md
```

---

## 📈 Dashboard Pages

### Executive Overview

Provides the core KPIs and high-level demand trends needed to understand overall performance.

### Product Performance

Compares products across revenue, quantity sold, and order contribution to identify stronger and weaker performers.

---

## 🎯 Skills Demonstrated

- Excel data preparation and validation
- SQL querying and business aggregations
- KPI development
- Power BI dashboard design
- Product performance analysis
- Category and size mix analysis
- Time-based sales analysis
- Business-focused data storytelling

---

## 👨‍💻 Author

**Ritik Khare**  
Aspiring Data Analyst | SQL | Excel | Power BI
