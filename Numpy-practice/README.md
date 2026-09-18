# NumPy Practice

This folder contains my hands-on practice with **NumPy**, a fundamental Python library for numerical computing and data analysis.

I have worked through the core NumPy concepts using Jupyter Notebooks, focusing on understanding how arrays work, how data can be manipulated, and how NumPy can be used for efficient numerical calculations.

---

## 📚 Topics Covered

### 1. NumPy Basics & Creating Arrays

This section covers the fundamentals of NumPy and how to create arrays.

**Concepts practiced:**

* Importing NumPy using `import numpy as np`
* Creating arrays using `np.array()`
* Creating arrays of zeros using `np.zeros()`
* Creating arrays of ones using `np.ones()`
* Generating sequences using `np.arange()`
* Creating evenly spaced values using `np.linspace()`
* Creating 1D and 2D arrays
* Understanding the difference between Python lists and NumPy arrays

**Why it matters:**
NumPy arrays are the foundation for numerical data processing in Python and are widely used in data analysis, machine learning, and scientific computing.

---

### 2. Array Properties & Operations

This section focuses on understanding the structure of NumPy arrays and performing operations on them.

**Concepts practiced:**

* `ndim` – Finding the number of dimensions
* `shape` – Understanding the size of each dimension
* `size` – Finding the total number of elements
* `dtype` – Checking the data type of elements
* Arithmetic operations on arrays
* Addition, subtraction, multiplication and division
* Comparison operations
* Performing calculations directly on arrays

**Why it matters:**
Understanding array properties helps in working with datasets correctly and avoiding dimension-related errors during data analysis.

---

### 3. Indexing & Slicing

This section focuses on accessing specific elements and portions of an array.

**Concepts practiced:**

* Accessing elements using indexes
* Positive indexing
* Negative indexing
* Indexing 2D arrays
* Selecting specific rows
* Selecting specific columns
* Selecting individual elements
* Slicing arrays
* Selecting ranges of rows and columns
* Using `:` for selecting complete rows or columns

**Examples of concepts practiced:**

```python
arr[2]
arr[-1]
arr[1, 2]
arr[:5]
arr[:, 2]
```

**Why it matters:**
Indexing and slicing are essential when selecting specific parts of a dataset for analysis or further processing.

---

### 4. Reshaping Arrays

This section covers changing the structure of an array without changing its data.

**Concepts practiced:**

* Using `reshape()`
* Converting 1D arrays into 2D arrays
* Changing the number of rows and columns
* Understanding dimensions while reshaping
* Flattening arrays
* Understanding how the total number of elements affects reshaping

**Example:**

```python
arr.reshape(2, 3)
```

**Why it matters:**
Different data operations require different array shapes. Reshaping is particularly useful when preparing numerical data for analysis and machine learning.

---

### 5. NumPy Functions

This section covers commonly used NumPy functions for numerical calculations and data analysis.

**Statistical functions practiced:**

* `np.sum()` – Calculates the total of array elements.
* `np.mean()` – Calculates the average value.
* `np.median()` – Finds the middle value of the data.
* `np.min()` – Finds the smallest value.
* `np.max()` – Finds the largest value.
* `np.std()` – Calculates standard deviation to understand data variation.
* `np.var()` – Calculates the variance of the data.

**Searching and sorting functions practiced:**

* `np.argmax()` – Finds the index of the maximum value.
* `np.argmin()` – Finds the index of the minimum value.
* `np.argsort()` – Returns the indexes that would sort an array.
* `np.where()` – Finds elements that satisfy a given condition.

**Why it matters:**
These functions provide the basic numerical operations required for exploring and analyzing datasets efficiently.

---

### 6. Data Manipulation

This section focuses on using NumPy to filter, modify, and work with numerical data.

**Concepts practiced:**

* Sorting arrays
* Filtering values
* Boolean indexing
* Applying conditions to arrays
* Selecting values based on conditions
* Replacing values
* Performing calculations on selected data
* Working with rows and columns
* Combining indexing with conditions

**Example:**

```python
arr[arr > 50]
```

This selects all values greater than `50`.

**Why it matters:**
Data manipulation is an important part of data analysis. NumPy makes it possible to efficiently filter and transform numerical data.

---

### 7. Broadcasting

Broadcasting allows NumPy to perform operations between arrays with different shapes without manually resizing them.

**Concepts practiced:**

* Understanding broadcasting rules
* Performing operations between arrays of different shapes
* Scalar operations on arrays
* Broadcasting across rows and columns
* Understanding compatible array shapes

**Example:**

```python
arr + 10
```

Here, `10` is automatically applied to every element of the array.

**Why it matters:**
Broadcasting makes numerical operations faster, cleaner, and more memory-efficient.

---

### 8. Random Module

This section covers NumPy's random number generation capabilities.

**Concepts practiced:**

* Generating random numbers
* Creating random arrays
* Generating random integers
* Working with random values
* Using NumPy's random module for creating sample data

**Examples:**

```python
np.random.randint()
np.random.rand()
```

**Why it matters:**
Random data generation is useful for testing programs, creating sample datasets, simulations, experiments, and practicing data analysis.

---

## 📂 Project Structure

```text
Numpy-practice/
│
├── numpy_basics_&_creating_arrays.ipynb
├── Array_properties_&_operations.ipynb
├── Indexing_&_Slicing.ipynb
├── reshaping_arrays.ipynb
├── numpy_functions.ipynb
├── Data_Manipulation.ipynb
├── Broadcasting_&_random_module.ipynb
└── README.md
```

---

## 🛠️ Technologies Used

* **Python** – Programming language used for implementation
* **NumPy** – Numerical computing and array manipulation
* **Jupyter Notebook** – Environment used for learning, coding, and experimentation

---

## 🎯 Learning Outcomes

By completing this practice, I developed a working understanding of:

* Creating and working with NumPy arrays
* Understanding array dimensions and properties
* Accessing and slicing data
* Reshaping arrays
* Performing numerical calculations
* Filtering and manipulating data
* Using Boolean conditions
* Applying statistical functions
* Sorting and searching arrays
* Working with `axis=0` and `axis=1`
* Using broadcasting
* Generating random data

---

## 🚀 Practical Application

After practicing these concepts individually, I applied my NumPy knowledge to a **Student Performance Analysis** mini-project.

The project uses NumPy to analyze student scores, calculate averages, identify top and bottom performers, classify performance levels, and extract meaningful insights from the dataset.

---

## 📌 Purpose of This Practice

The purpose of this folder is not just to collect code examples, but to document my progress in learning NumPy through **hands-on practice and problem-solving**.

This practice forms part of my broader journey toward building stronger **Python and Data Analysis skills**.

---

## 👩‍💻 Author

**Pallavi Sagar**

Learning Python and Data Analysis through consistent practice, hands-on projects, and continuous improvement.

