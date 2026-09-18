# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

Customer behavior is one of the most important factors influencing retail business decisions. Understanding how customers purchase products, respond to discounts, use subscriptions, choose shipping methods, and interact with different product categories can help businesses improve their marketing, customer retention, and sales strategies.

For this project, I developed an end-to-end **Customer Shopping Behavior Analysis** workflow using a customer shopping dataset. Instead of treating the dataset as just a collection of records, I approached it as a realistic **retail business analytics scenario**:

> **"If I were working as a Data Analyst for a retail company, how could I use customer transaction data to understand purchasing behavior and provide actionable insights to business stakeholders?"**

The project starts with a raw CSV dataset and progresses through:

**Raw Data → Python → MySQL → SQL Analysis → Power BI → Business Insights → Report → Presentation**

The final outcome is an interactive Power BI dashboard supported by SQL analysis, a detailed analytical report, and a business-focused presentation.

---

## 🎯 Business Scenario

Imagine a retail company that has collected thousands of customer shopping records but does not have a clear understanding of its customers.

The management team wants answers to questions such as:

- Which customer groups generate the most revenue?
- Do male and female customers contribute differently to revenue?
- Do customers using discounts still make high-value purchases?
- Which products receive the best customer ratings?
- Does shipping method relate to spending?
- Do subscribers actually spend more than non-subscribers?
- Which products rely most heavily on discounts?
- How can customers be segmented based on purchase history?
- What products are most popular within each category?
- Are repeat buyers more likely to subscribe?
- Which age groups contribute the most revenue?

As a Data Analyst, my objective was to transform raw customer data into meaningful information that could help answer these business questions and support better decision-making.

---

## 💡 Why I Chose This Project

I wanted to build a project that demonstrates more than basic data cleaning or visualization.

Instead of creating isolated charts, I designed the project around a complete analytics workflow similar to how a Data Analyst would approach a real business problem.

The project was designed to demonstrate my ability to:

1. Understand a business scenario.
2. Identify relevant business questions.
3. Work with raw customer data.
4. Prepare and inspect data using Python.
5. Store structured data in a relational database.
6. Write SQL queries to solve business questions.
7. Translate analytical results into business insights.
8. Build an interactive Power BI dashboard.
9. Document the analysis in a professional report.
10. Present the findings as a business story.

This approach helped me treat the dataset as the starting point of a **business case study rather than simply a dataset for visualization**.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| 🐍 Python | Data loading, inspection and preparation |
| 🐼 Pandas | Data manipulation and analysis |
| 🗄️ MySQL | Relational database storage |
| 🔍 SQL | Business analysis and querying |
| 🔗 SQLAlchemy | Python-to-MySQL database connection |
| 🔌 PyMySQL | MySQL database driver |
| 📊 Power BI | Interactive dashboard and visualization |
| 📝 Microsoft Word / PDF | Analytical report |
| 📽️ PowerPoint | Project presentation |
| 🔧 Git & GitHub | Version control and project documentation |

---

## 📂 Dataset

The dataset contains **3,900 customer shopping records** and **18 attributes** describing customer demographics, purchases, product information, reviews, discounts, subscriptions, shipping, payment methods, and purchase history.

### Important Attributes

| Column | Description |
|---|---|
| Customer ID | Unique customer identifier |
| Age | Customer age |
| Gender | Customer gender |
| Item Purchased | Product purchased |
| Category | Product category |
| Purchase Amount (USD) | Amount spent on purchase |
| Location | Customer location |
| Size | Product size |
| Color | Product color |
| Season | Purchase season |
| Review Rating | Customer review rating |
| Subscription Status | Whether customer is subscribed |
| Shipping Type | Shipping method |
| Discount Applied | Whether discount was applied |
| Promo Code Used | Whether promotional code was used |
| Previous Purchases | Number of previous purchases |
| Payment Method | Payment method used |
| Frequency of Purchases | Purchase frequency |

---


# 📊 Power BI Dashboard

The final stage of the project was to transform the SQL analysis into an interactive **Power BI dashboard**. The dashboard was designed from a business-user perspective, focusing on customer purchasing behavior, revenue contribution, product categories, subscription status, shipping preferences, and customer demographics.

Rather than presenting SQL results as standalone numbers, the dashboard brings the analysis together into an interactive visual interface that allows stakeholders to explore different customer segments and identify important patterns.

---

## 📌 Dashboard Overview

The Power BI dashboard provides a consolidated view of customer shopping behavior using:

- 📍 KPI Cards
- 📊 Bar Charts
- 🍩 Donut Chart
- 🎛️ Interactive Slicers
- 🔎 Category Filters
- 👥 Customer Segmentation
- 👴 Age-Based Analysis

The dashboard is designed to answer key business questions identified during the SQL analysis and convert analytical results into an easily understandable business view.

---

## 📈 Key Performance Indicators

The dashboard highlights three primary KPIs that provide an immediate overview of the dataset.

| KPI | Value | Description |
|---|---:|---|
| 👥 Customer Records | **3.9K** | Total purchase records represented in the dataset |
| 💰 Average Purchase Amount | **$59.76** | Average recorded purchase amount |
| ⭐ Average Review Rating | **3.75 / 5** | Overall average customer review rating |

These KPIs provide a quick snapshot of the overall transaction and customer behavior before moving into detailed analysis.

> **Note:** The 3.9K figure represents records in the dataset. It should not automatically be interpreted as 3.9K unique customers unless Customer ID uniqueness is verified.

---

## 🎛️ Interactive Filters

The dashboard contains interactive slicers that allow users to dynamically explore customer behavior.

### 🔄 Subscription Status

Users can filter the dashboard based on subscription status:

- **Yes** — Subscribed customers
- **No** — Non-subscribed customers

This allows stakeholders to compare purchasing behavior between subscribers and non-subscribers.

### 👥 Gender

The dashboard allows users to filter customers by:

- **Male**
- **Female**

This supports gender-based comparisons of purchasing and revenue patterns.

### 🛍️ Product Category

Customers and purchases can be analyzed across:

- **Clothing**
- **Accessories**
- **Footwear**
- **Outerwear**

This allows stakeholders to investigate category-level sales and revenue performance.

### 🚚 Shipping Type

The dashboard provides filtering based on shipping method:

- **Standard**
- **Express**
- **Free Shipping**
- **Next Day Air**
- **2-Day Shipping**
- **Store Pickup**

This makes it possible to explore whether purchasing behavior differs across shipping preferences.

---

# 📊 Dashboard Visualizations

## 1. 🔄 Subscription Status

A donut chart displays the distribution of purchase records by subscription status.

The dashboard shows approximately:

- **73% Non-Subscribers**
- **27% Subscribers**

### Business Interpretation

The majority of records are associated with non-subscribers, indicating that subscription adoption is considerably lower than the non-subscriber share represented in the dataset.

This can help a retail business investigate opportunities for:

- Subscription promotion
- Customer retention
- Loyalty programs
- Subscriber conversion

---

## 2. 💰 Revenue by Category

The **Revenue by Category** visualization compares the total recorded purchase revenue generated across product categories.

The categories include:

- Clothing
- Accessories
- Footwear
- Outerwear

### Key Observation

**Clothing generates the highest recorded revenue**, followed by Accessories, Footwear, and Outerwear.

### Business Interpretation

The category-level revenue comparison helps identify which product categories contribute the most to overall recorded sales value.

This information can support decisions related to:

- Inventory planning
- Product promotion
- Category management
- Marketing allocation

---

## 3. 🛒 Sales by Category

The **Sales by Category** visualization compares the number of recorded purchases across product categories.

### Key Observation

**Clothing has the highest sales volume**, followed by Accessories and Footwear.

### Business Interpretation

Comparing sales volume with revenue provides a more complete understanding of category performance.

For example:

```text
Sales Volume
     +
Revenue
     ↓
Category Performance


# 🔄 Project Workflow

The project follows an end-to-end data analytics pipeline:

```text
                RAW DATASET
                     │
                     ▼
             Python / Pandas
                     │
                     ▼
          Data Inspection & Validation
                     │
                     ▼
              MySQL Database
                     │
                     ▼
               SQL Analysis
                     │
                     ▼
             Business Questions
                     │
                     ▼
               Power BI
                     │
                     ▼
          Interactive Dashboard
                     │
          ┌──────────┴──────────┐
          ▼                     ▼
     Analytical Report      Presentation
          │                     │
          └──────────┬──────────┘
                     ▼
              Business Insights

