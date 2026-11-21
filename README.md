# Credit Card Customer & Risk Analytics

## 1. Project Overview

This project focuses on analyzing credit card customer behavior, repayment patterns, billing activity, and default risk using Python, MySQL, and Microsoft Excel.

The objective is to transform raw customer-level financial data into meaningful business insights that can support credit risk monitoring and data-driven decision-making.

## 2. Business Problem

Credit card companies face financial risks when customers delay repayments or fail to repay outstanding balances.

Understanding customer repayment behavior and identifying high-risk customer segments can help financial institutions strengthen their credit risk monitoring strategies.

This project explores customer-level data to understand repayment trends, identify patterns associated with payment defaults, and develop actionable business recommendations.

## 3. Project Objectives

- Analyze customer repayment and billing behavior.
- Examine payment delays and default patterns.
- Understand relationships between credit limits, bill amounts, and repayment amounts.
- Identify customer segments with higher default rates.
- Develop business insights and recommendations for credit risk monitoring.
- Present key findings through an interactive Excel dashboard.

## 4. Dataset

**Dataset:** Default of Credit Card Clients

**Source:** UCI Machine Learning Repository

**Dataset ID:** 350

**Dataset Link:** https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

The dataset contains 30,000 customer records and 23 explanatory features, covering demographic information, credit limits, repayment status, bill amounts, and payment amounts.

It also contains a target variable indicating whether a customer defaulted on payment in the following month.

**Data limitation:** The dataset represents credit card clients in Taiwan and is based on historical data from 2005. Findings will be interpreted within this context and will not be presented as representative of current Indian banking customers.

## 5. Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data cleaning, exploration, and analysis |
| Pandas & NumPy | Data manipulation and numerical analysis |
| Matplotlib | Data visualization |
| MySQL | SQL-based business analysis |
| Microsoft Excel | Dashboard development and reporting |

## 6. Project Workflow

1. Understand the business problem and dataset.
2. Perform data inspection and quality checks.
3. Clean and prepare the dataset using Python.
4. Conduct exploratory data analysis (EDA).
5. Load structured data into MySQL.
6. Write SQL queries to answer business questions.
7. Build an Excel dashboard to communicate findings.
8. Develop business recommendations and document conclusions.

## 7. Repository Structure

```text
credit-card-customer-risk-analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
├── sql/
├── excel_dashboard/
├── reports/
├── docs/
│
├── requirements.txt
├── README.md
└── .gitignore
```

## 8. Expected Deliverables

- Reproducible Python analysis notebooks.
- Documented SQL queries.
- Interactive Excel dashboard.
- Business insights and recommendations.
- Project documentation.

## 9. Project Status

**Current stage:** Project setup and documentation.

Analysis, SQL development, and dashboard implementation will be added as the project progresses.

---

*This project is developed as a practical data analytics portfolio project, emphasizing business understanding, data quality, analytical reasoning, and clear communication of findings.*