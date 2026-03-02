# Consumer-Demand-Analysis

Identified that a 37% revenue decline that was misleading, not demand loss, but a drop in order value driven by bulk-order anomalies and product mix shifts.

Built an end-to-end Excel analysis model to diagnose revenue volatility, warehouse concentration risk, and portfolio performance using only structured tables, pivots, and business logic validation.

This analysis reframed leadership’s perception from “shrinking demand” to unstable revenue composition and operational concentration risk.

# ****The Problem (Situation)****

A B2B enterprise software company observed:
1. Severe month-over-month revenue volatility
2. Revenue decline (2018–2019)
3. Inconsistent demand patterns across warehouses
4. Uncertainty about product portfolio performance

Leadership needed to understand whether the business was actually declining or being misread due to data anomalies.

# My Task

From leardship observations, I wanted to determine:

1. What is truly driving revenue volatility
2. Whether the decline reflects demand loss or value compression
3. Which warehouses and product categories pose strategic risk
4. What leadership should act on immediately

# **What I Did (Action — Excel Only)**

1. Cleaned 50,000 order records and validated 45,789 order records using Excel Tables
2. Calculated revenue using structured formulas (Order Demand × Unit Value)
3. Built Pivot Tables for:
   Revenue trends (monthly & yearly)
   Warehouse contribution analysis
   Product category performance

# What I Found (Key Insights)

1. The 37% Revenue Decline Was Misleading
Order volume remained flat, indicating value compression, not demand collapse.

2. A Single Anomaly Distorted Executive Perception
October 2018 generated ~$99B — ~2.8× the normal monthly average.
Without this spike, 2019 performance suggests stable or slightly growing baseline demand.

3. Extreme Operational Concentration Risk
One warehouse (Cedar Park) generated ~76% of total revenue, creating a single point of failure.

4. Product Portfolio Imbalance
Worksuite 1000 had 82% of revenue while BI Stack had only 4.8% despite strong order volume. This signals potential underpricing or weak positioning of the BI product line.

5. Revenue Volatility Driven by Bulk Orders
Order demand ranged from 1 to 2,000,000 units, meaning a small number of enterprise deals disproportionately shaped revenue trends.

# The Decision I Owned (Critical Recommendation)

I recommended that leadership stop using raw YoY revenue comparisons and instead adopt a normalized baseline analysis excluding outlier bulk-order months before making strategic cost or expansion decisions.

Why this mattered:
Acting on the raw -37% decline could trigger unnecessary cost cuts in a business that was operationally stable but statistically distorted.

# Business Impact (Result)

1. Reframed the narrative from “declining business” to unstable revenue composition
2. Highlighted a single-warehouse dependency risk (76%) requiring contingency planning
3. Identified AOV decline as the true performance driver, not customer loss
4. Provided a scalable Excel model for ongoing executive KPI tracking

Most importantly, the analysis prevented misinterpretation of performance trends driven by one-time enterprise bulk orders.

# Tools (Only What Materially Mattered)

1. Excel
2. Structured Tables (Ctrl+T) for dynamic modeling
3. Pivot Tables for multi-dimensional analysis
4. Advanced formulas for revenue logic
