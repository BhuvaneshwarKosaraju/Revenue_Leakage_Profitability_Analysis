# Revenue Leakage & Profitability Analysis

## Problem Statement
Strong sales performance does not always translate into healthy profitability.
This project analyzes retail transaction data to identify profit leakage, uncover loss-making product segments, and recommend actions to improve margins.

## Dataset
- Source: Sample Superstore Dataset
- Each row represents a single product line item within an order
- Key columns include Sales, Profit, Discount, Category, and Sub-Category
- Approximately 10,000 retail transactions

## Tools Used
- Python
- pandas
- matplotlib

## Key Insights
- ~19% of transactions were loss-making despite strong overall sales
- Furniture generated high revenue but contributed the lowest profit
- Tables were the primary source of loss, losing ~₹0.08 per ₹1 earned due to heavy discounting
- Loss rates increased significantly at higher discount levels

## Business Recommendations
- Limit aggressive discounting for Tables (especially beyond 20–25%)
- Review pricing and cost structure for high-volume SKUs
- Apply targeted interventions for loss-making Bookcases instead of blanket discounts

## Outcome
This analysis demonstrates how profit-focused analytics can uncover hidden revenue leakage and support high-impact business decisions.
