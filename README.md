# Ai-powered-data-analytics-project
Built an AI-Powered Sales &amp; Profitability Analytics Dashboard, using Tableau Agent and AI-assisted techniques for data profiling, cleaning, analysis, KPI creation, and visualization, with manual validation to ensure accurate business insights

# AI-Powered Sales & Profitability Analytics

An end-to-end Data Analytics project focused on analyzing sales performance, profitability, discount impact, regional contribution, and product returns using **Tableau Desktop, Tableau Agent, Excel, and AI-assisted analytics techniques**.

The key objective of this project was to demonstrate how AI can support a Data Analyst across the complete analytics workflow while ensuring that all AI-generated suggestions are manually validated.

---

## Project Overview

This project analyzes a retail sales dataset containing transaction, customer, product, regional, pricing, profitability, return, and delivery information.

The workflow covers:

**Raw Data → AI-Assisted Profiling → Data Cleaning → Validation → KPI Creation → Analysis → Visualization → Dashboard → Business Insights**

A major focus of this project was using **Tableau Agent and AI-assisted techniques** to accelerate profiling, calculations, analytical logic, and visualization development.

---

## Business Objectives

The analysis was designed to answer key business questions such as:

- How much revenue and profit is the business generating?
- What is the overall profit margin?
- Which categories generate stronger profitability?
- How is revenue distributed across regions?
- How do discounts affect profitability?
- Which category and region combinations have higher return rates?
- How are sales and profit changing over time?

---

## Dataset

The raw dataset contains approximately **2,500 sales transactions** with fields related to:

- Orders
- Customers
- Products
- Categories
- Regions
- Sales Channels
- Quantity
- Unit Price
- Discounts
- Sales
- Cost
- Profit
- Payment Mode
- Customer Segment
- Returns
- Delivery
- Ratings
- Sales Representatives

The raw data also contained intentionally introduced data-quality issues to simulate a real-world analytics workflow.

---

## Data Quality Issues Identified

During profiling, issues identified included:

- Duplicate records
- Missing customer names
- Missing regions
- Missing payment modes
- Missing costs
- Missing ratings
- Mixed date formats
- Inconsistent category names
- Region casing and spacing inconsistencies
- Invalid quantity values
- Invalid discount percentages
- Unit price outliers
- Sales outliers
- Invalid delivery-day values
- Invalid rating values
- Missing return reasons for returned orders
- Return reasons incorrectly populated for non-returned orders

Negative profit values were retained because they can represent genuine loss-making transactions rather than data errors.

---

## AI-Assisted Workflow

AI was used as an analyst productivity tool rather than as a replacement for analytical judgement.

### Data Profiling

Tableau Agent and AI-assisted analysis were used to:

- Explore the dataset
- Identify potential data-quality issues
- Detect inconsistencies
- Review missing values
- Identify potential anomalies
- Suggest useful areas for further investigation

### Data Cleaning

AI-assisted logic was used to define cleaning rules such as:

- Removing exact duplicates
- Standardizing dates
- Standardizing category and region values
- Handling missing customer names
- Handling missing payment modes
- Reconstructing missing cost values where possible
- Validating ratings
- Validating delivery days
- Correcting return-reason logic
- Flagging suspicious values instead of automatically deleting them

All cleaning rules were manually reviewed before being applied.

### Data Analysis

Tableau Agent was used to help accelerate:

- KPI creation
- Calculated fields
- Profitability analysis
- Return-rate calculations
- Discount grouping
- Visualization generation
- Analytical exploration

AI-generated outputs were manually checked before being included in the final dashboard.

---

## Key KPIs

The final dashboard contains five major KPIs:

| KPI | Value |
|---|---:|
| Total Revenue | ₹90.20M |
| Total Profit | ₹19.87M |
| Profit Margin | 22.03% |
| Return Rate | 11.68% |
| Average Order Value | ₹36,079 |

---

## Tableau Calculations

### Profit Margin %

```text
SUM([Profit]) / SUM([Sales])
