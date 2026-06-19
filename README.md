# Superstore Business Intelligence Dashboard

An interactive Power BI dashboard that analyzes retail sales and profitability for a fictional company called Superstore. The goal is simple: figure out where the business is actually making money, and where it isn't.

 [View the full PDF version of the dashboard](https://github.com/rooshankumar/Superstore-Business-Intelligence-Dashboard/blob/main/Superstore%20PowerBi.pdf) — no Power BI required
 [Download the raw dataset](https://github.com/rooshankumar/Superstore-Business-Intelligence-Dashboard/blob/main/Datasets/Superstore.csv)

---

## Why This Project

Most companies look at sales and assume that's the whole story. It isn't. A region or product can have huge sales and still lose money once discounts and costs eat into the margin. This dashboard was built to answer one core question:

**"Where is Superstore actually profitable, and where is it just busy?"**

---

## What's Inside

The dashboard has 3 pages, each answering a different business question.

### 1. Executive Overview
A high-level snapshot for someone who has 30 seconds to understand the business.

![Executive Overview](Dashboard%20Screenshots/Executive%20Overview.jpg)

**What it shows:**
- Total Sales: $2.3M
- Total Profit: $286K (a 12.47% profit margin — thinner than it looks at first glance)
- Order volume, quantity sold, and average discount given
- Sales and profit trend over time, by quarter

**Key takeaway:** Profitability improved steadily from 2014 to 2017, but the margin stays tight — discounting is clearly eating into profit somewhere. That "somewhere" is what the next two pages dig into.

---

### 2. Regional Profitability Analysis
A geographic breakdown — which regions and states are actually worth investing in.

![Regional Analysis](Dashboard%20Screenshots/Regional%20Analysis.jpg)

**What it shows:**
- Sales and profit by region and state, shown on a US map
- Segment-level profitability (Consumer vs Corporate vs Home Office)
- Top-performing cities by sales

**Key takeaway:** The West region leads in both sales and profit — it's the model performer. Central, on the other hand, has strong sales but noticeably weaker profit. Same effort, less return. That's a flag for leadership to investigate pricing or discount practices in that region.

---

### 3. Product Analysis
This is where the real story is — sales volume and profit don't always move together.

![Product Analysis](Dashboard%20Screenshots/Product%20Analysis.jpg)

**What it shows:**
- Sales by category and sub-category
- Revenue vs profit comparison per sub-category
- Category-level profit trends over time

**Key takeaway:** Technology drives the largest share of sales, with Phones as the single highest revenue-generating sub-category. But several sub-categories that sell well actually generate comparatively low profit — meaning the business is moving a lot of product without keeping much of the money. These are the exact sub-categories worth a closer look on discount strategy.

---

## How I Built It

1. **Data Cleaning** : Loaded the raw CSV into Power Query, fixed date formats, checked for nulls and duplicates
2. **Data Modeling** : Built DAX measures for Total Sales, Total Profit, Profit Margin, Average Discount, and Order Count
3. **Dashboard Design** : Built all 3 pages with a consistent color system, KPI cards, and interactive slicers (Region, Segment, Category)
4. **Insight-First Approach** : Every visual was chosen to answer a specific business question, not just to "show data"

---

## Tools Used

- **Power BI Desktop** : dashboard build, DAX measures, data modeling
- **Power Query** : data cleaning and transformation
- **Excel** : initial data exploration

---

## Dataset

The Superstore dataset is a widely-used retail dataset containing order-level transaction data: Sales, Profit, Quantity, Discount, Customer details, Product details, and Region/State/City information.

[View raw dataset](https://github.com/rooshankumar/Superstore-Business-Intelligence-Dashboard/blob/main/Datasets/Superstore.csv)

---

## What This Project Demonstrates

- Translating raw transactional data into KPIs that matter to a business
- Spotting the gap between "high sales" and "high profit" — a core skill in business analysis
- Building clean, interactive dashboards meant for non-technical stakeholders to use
- DAX measure design and data modeling fundamentals

---

## About Me

**Roshan Kumar**
BCA Student (9.2 CGPA) | Aspiring Data Analyst / Business Analyst
Founder of [PublicGermany](https://publicgermany.vercel.app) — a self-built admissions platform managing 105+ students

 isthisroshan@gmail.com
[LinkedIn](https://linkedin.com/in/rooshaankumar) · [GitHub](https://github.com/rooshankumar) · [Portfolio](https://rooshankumar.netlify.app)
