# 06 — Data Transformation & Analysis

## Goal
Use Pandas to transform datasets and answer real analytical questions.

## What to Learn
1. Grouping and aggregation
2. Multiple aggregations
3. Merging datasets
4. Concatenating datasets
5. Pivot tables
6. Ranking
7. Percentage calculations
8. Running totals
9. `shift()`
10. `rolling()`
11. Derived analytical metrics

## Core Examples
```python
df.groupby("Category")["Sales"].sum()

pd.merge(customers, orders, on="customer_id")

pd.pivot_table(df, values="Sales", index="Category", aggfunc="sum")
```

## Practice
- Combine customer and transaction data
- Calculate category-level KPIs
- Rank products or customers
- Calculate shares and percentages
- Compare current values with previous periods
- Build running and rolling calculations

## Completion Goal
You should be able to transform raw tables into useful analytical datasets and calculate common business metrics.
