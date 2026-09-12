# 05 — Data Cleaning

## Goal
Learn how to identify, investigate, and fix common data-quality problems.

## What to Learn
1. Missing values
2. Duplicate records
3. Incorrect data types
4. Numeric conversion
5. Date conversion
6. String cleaning
7. Inconsistent categories
8. Invalid values
9. Outliers
10. Data validation

## Important Pandas Tools
```python
df.isna()
df.dropna()
df.fillna()
df.duplicated()
df.drop_duplicates()
df.astype()
pd.to_numeric()
pd.to_datetime()
```

## Practice
- Find missing values
- Detect duplicate records
- Fix incorrect data types
- Standardize text categories
- Validate values against expected rules
- Investigate unusual observations

## Completion Goal
You should be able to take a messy dataset and make it analysis-ready while being able to explain what you changed and why.
