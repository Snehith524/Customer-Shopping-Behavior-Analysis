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
