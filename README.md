# Python for Data Analysis

A practical, data-analysis-focused Python learning path designed to build the Python skills needed to work with real datasets.

## Learning Goal

Learn Python specifically for the Data Analyst workflow:

**Get data → Understand data → Clean data → Transform data → Analyze data → Visualize data → Find insights**

The focus is on learning concepts through datasets, exercises, and progressively larger analysis projects.

## Learning Structure

### 01. Python Foundations

Build the Python foundation required for data analysis.

Topics:
- Python syntax and basic concepts
- Variables
- Operators
- Data types
- Type conversion
- Strings
- Lists
- Tuples
- Dictionaries
- Sets
- Conditional statements
- `for` and `while` loops
- Functions
- Basic list comprehensions

The goal is practical fluency rather than learning Python as a general-purpose programming language.

### 02. Python for Working With Data

Learn how Python works with data and external files.

Topics:
- Importing libraries
- File paths
- CSV files
- Excel files
- Dates and basic date handling
- Basic error handling
- Understanding Python objects
- DataFrame and Series concepts

### 03. NumPy

Learn the NumPy concepts that support numerical analysis and Pandas.

Topics:
- Arrays
- Dimensions and shape
- Data types
- Indexing and slicing
- Vectorized operations
- Basic numerical aggregation
- `np.array()`
- `np.mean()`
- `np.median()`
- `np.sum()`
- `np.min()`
- `np.max()`
- `np.std()`

### 04. Pandas Fundamentals

Develop the core DataFrame skills used in Python data analysis.

Topics:
- Series and DataFrames
- Loading CSV and Excel data
- Inspecting datasets
- Selecting columns and rows
- Filtering data
- Sorting data
- Creating columns
- Renaming columns
- Removing rows and columns
- Aggregation
- `groupby()`
- `value_counts()`
- `unique()` and `nunique()`

Important inspection methods:

```python
df.head()
df.tail()
df.shape
df.columns
df.info()
df.describe()
df.dtypes
df.nunique()
```

### 05. Data Cleaning

Learn how to identify and fix common data-quality problems.

Topics:
- Missing values
- Duplicate records
- Incorrect data types
- Numeric conversion
- Date conversion
- String cleaning
- Inconsistent categories
- Invalid values
- Outliers
- Data validation

Important Pandas tools include:

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

### 06. Data Transformation & Analysis

Use Pandas to answer analytical questions and create useful derived metrics.

Topics:
- Grouping and aggregation
- Multiple aggregations
- Merging datasets
- Concatenating datasets
- Pivot tables
- Ranking
- Percentage calculations
- Running totals
- `shift()`
- `rolling()`
- Analytical transformations

Core examples:

```python
df.groupby("Category")["Sales"].sum()

pd.merge(customers, orders, on="customer_id")

pd.pivot_table(df, values="Sales", index="Category", aggfunc="sum")
```

### 07. Data Visualization

Learn to communicate analytical results clearly with Python.

#### Matplotlib

- Bar charts
- Line charts
- Scatter plots
- Histograms
- Box plots
- Titles and labels
- Legends
- Figure sizing

#### Seaborn

- Bar plots
- Count plots
- Histograms
- Box plots
- Scatter plots
- Line plots
- Heatmaps

Focus on choosing the right visualization for the analytical question.

| Analytical question | Useful chart |
|---|---|
| Compare categories | Bar chart |
| Show a trend over time | Line chart |
| Show a distribution | Histogram |
| Show a relationship | Scatter plot |
| Examine spread and outliers | Box plot |
| Examine correlations | Heatmap |

### 08. Exploratory Data Analysis

Bring the complete workflow together using real datasets.

A typical analysis should follow:

**Dataset → Understand → Inspect → Clean → Transform → Analyze → Visualize → Find patterns → Communicate insights**

A project notebook can follow this structure:

```text
1. Business Question
2. Import Libraries
3. Load Dataset
4. Understand Dataset
5. Data Quality Checks
6. Data Cleaning
7. Exploratory Analysis
8. Visualization
9. Key Findings
10. Business Recommendations
```

## Learning Method

Each concept should follow this cycle:

1. Understand the concept.
2. Run a small example.
3. Understand the output.
4. Modify the example.
5. Solve a small problem.
6. Apply the concept to a real dataset.

The emphasis is on **learning by analyzing data**, not simply completing syntax exercises.

## Recommended Practice Flow

```text
Learn a concept
      ↓
Small exercise
      ↓
Use it on a dataset
      ↓
Combine it with previous concepts
      ↓
Build analysis
      ↓
Repeat
```

## Project Progression

Practice should gradually move from small exercises to complete analyses.

Suggested progression:

1. Small structured datasets
2. Sales analysis
3. Customer analysis
4. Multi-table analysis
5. Messy real-world datasets
6. Exploratory Data Analysis projects
7. Market research / survey data analysis

## Tools Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Data Wrangler for dataset inspection
- PyGWalker for interactive exploration when useful

## Repository Structure

```text
python-for-data-analysis/
├── README.md
├── 01-python-foundations/
├── 02-python-for-data/
├── 03-numpy/
├── 04-pandas/
├── 05-data-cleaning/
├── 06-data-transformation-analysis/
├── 07-data-visualization/
└── 08-exploratory-data-analysis/
```

The repository will grow progressively as each stage is learned and practiced.