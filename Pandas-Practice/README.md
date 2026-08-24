# Pandas Practice

A structured collection of hands-on practice notebooks covering **Pandas for Data Analysis**.

This repository focuses on learning Pandas through practical problems, dataset manipulation, and analytical tasks rather than memorizing syntax. The goal is to build a strong foundation in data cleaning, transformation, analysis, and preparation for real-world Data Analyst projects.

---

## 📌 About Pandas

**Pandas** is a powerful Python library used for working with structured and tabular data.

It provides two primary data structures:

* **Series** — One-dimensional labeled data
* **DataFrame** — Two-dimensional tabular data

Pandas is widely used for:

* Data Cleaning
* Data Transformation
* Exploratory Data Analysis (EDA)
* Data Manipulation
* Statistical Analysis
* Business Analytics
* Preparing data for visualization and Machine Learning

---

# 📚 Topics Covered

## 1. Filtering Rows & Columns

**Notebook:** `Filtering_rows_And_columns_practice.ipynb`

Filtering is one of the most important operations in data analysis. It allows us to select only the rows and columns relevant to a particular analysis.

### Concepts Practiced

* Selecting specific columns
* Selecting specific rows
* Boolean conditions
* Comparison operators
* Filtering using multiple conditions
* Using `&` and `|`
* Using `isin()`
* Combining row and column filtering
* Filtering based on categorical and numerical values

### Example Use Cases

Filtering can be used to answer questions such as:

* Which orders were delivered?
* Which products generated sales above ₹10,000?
* Which customers belong to a particular city?
* Which employees have a salary above a certain threshold?

---

## 2. Sorting Data

**Notebook:** `Sorting_Data_practice_questions.ipynb`

Sorting helps organize data based on one or more columns, making it easier to identify trends, rankings, and extreme values.

### Concepts Practiced

* `sort_values()`
* Ascending sorting
* Descending sorting
* Sorting by multiple columns
* Sorting filtered data
* Finding highest and lowest values

### Example Use Cases

Sorting can help answer:

* Which products have the highest sales?
* Who are the top-performing employees?
* Which customers have spent the most?
* What are the lowest-rated products?

---

## 3. Value Counts

**Notebook:** `Value_counts_practice.ipynb`

`value_counts()` is used to calculate the frequency of unique values in a Series.

It is especially useful for analyzing categorical data.

### Concepts Practiced

* Counting unique values
* Frequency analysis
* Using `value_counts()`
* Sorting frequency results
* Analyzing categorical columns
* Combining value counts with filtering

### Example Use Cases

Value counts can help answer:

* How many orders belong to each payment mode?
* Which category appears most frequently?
* How many customers are from each city?
* What is the most common order status?

---

## 4. GroupBy & Aggregation

**Notebook:** `Groupby_And_Aggregating_Practice.ipynb`

`groupby()` is one of the most important Pandas concepts for data analysis.

It allows data to be divided into groups and analyzed using aggregation functions.

### Concepts Practiced

* `groupby()`
* Grouping by a single column
* Grouping by multiple columns
* `sum()`
* `mean()`
* `count()`
* `min()`
* `max()`
* Aggregating grouped data
* Filtering grouped results
* Sorting aggregated results
* Combining `groupby()` with other Pandas operations

### Example Use Cases

GroupBy analysis can answer business questions such as:

* What is the total sales for each city?
* What is the average rating for each category?
* Which product generates the highest revenue?
* How many orders are placed in each category?
* Which category has the highest average sales?

### Example

```python
df.groupby('City')['Sales'].sum()
```

This groups the dataset by city and calculates the total sales for each city.


---

# 🧠 What I Have Learned So Far

Through these topics, I can now perform several fundamental data-analysis tasks using Pandas:

* Select relevant data from a DataFrame
* Filter datasets using conditions
* Sort data based on analytical requirements
* Analyze categorical distributions
* Calculate frequencies
* Group data based on business dimensions
* Calculate aggregate metrics
* Identify top and bottom performers
* Combine filtering, grouping, sorting, and aggregation
* Convert business questions into Pandas operations

---



# 🎯 Learning Objective

The objective of this repository is to progress from **Pandas fundamentals to real-world data analysis**.

The learning path is:

```text
Pandas Fundamentals
        ↓
Data Selection & Filtering
        ↓
Sorting & Aggregation
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Combining Data
        ↓
Data Reshaping
        ↓
Exploratory Data Analysis
        ↓
Real-World Data Analysis Projects
```

---

# 💼 Career Relevance

Pandas is a core skill for a **Data Analyst** and is also highly useful in Data Science and AI workflows.

The concepts practiced in this repository directly support tasks such as:

* Sales analysis
* Customer analysis
* Financial analysis
* Business reporting
* KPI analysis
* Exploratory Data Analysis
* Data cleaning
* Dashboard preparation
* Preparing datasets for visualization
* Preparing data for Machine Learning

---

# 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **Jupyter Notebook**
* **Git & GitHub**

---

# 📂 Repository Structure

```text
Pandas-Practice/
│
├── Filtering_rows_And_columns_practice.ipynb
├── Sorting_Data_practice_questions.ipynb
├── Value_counts_practice.ipynb
├── Groupby_And_Aggregating_Practice.ipynb
└── README.md
```

---

# 📈 Progress Philosophy

I am following a **practice-first approach**:

> Learn the concept → Solve problems → Work with datasets → Analyze real-world questions → Build projects

The ultimate goal is not just to learn Pandas syntax, but to develop the ability to use Pandas to **solve real-world data problems and generate meaningful insights from datasets**.

---

## ⭐ Repository Goal

Build a strong foundation in **Python + Pandas + Data Analysis** and gradually transition from practice notebooks to **real-world portfolio projects**.

**Current Progress: 4 Pandas topics completed ✅**

