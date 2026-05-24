# NumPy and Pandas Practice Notebook

## Overview

This project contains hands-on exercises using **NumPy** and **Pandas** for data manipulation, analysis, and validation tasks. The notebook demonstrates operations on arrays, Sudoku validation, student performance analysis, and basic dataset preprocessing.

---

## Technologies Used

- Python 3
- NumPy
- Pandas
- Google Colab

---

## Features

### 1. Sudoku Validation using NumPy

Implemented various checks on a Sudoku grid:

- Create a 9×9 Sudoku matrix
- Calculate total sum of the Sudoku board
- Verify row sums
- Check Sudoku validity based on expected row totals
- Extract individual 3×3 sub-grids
- Traverse all 3×3 Sudoku blocks using nested loops

#### Concepts Used

- NumPy Arrays
- Slicing
- Axis-based operations
- Nested loops
- Conditional validation

---

### 2. Student Data Analysis

A dataset containing:

| Column | Description |
|----------|------------|
| Age | Student age |
| Math Marks | Mathematics score |
| Science Marks | Science score |

Performed operations such as:

- Finding dataset dimensions
- Calculating average age
- Extracting subject-wise marks
- Finding maximum science marks
- Boolean filtering
- Selecting students with marks above thresholds
- Updating marks
- Counting students based on age criteria
- Computing subject averages
- Applying multiple filtering conditions
- Replacing low scores with zero

#### Concepts Used

- Indexing
- Boolean Masking
- Conditional Selection
- Aggregation Functions
- Data Modification

---

### 3. Pandas Data Processing

Loaded an Anime dataset and performed:

- Reading CSV files
- Displaying records using `head()`
- Accessing rows with `loc`
- Creating custom extraction functions
- Extracting episode information from text
- Applying functions to DataFrame columns
- Creating new columns dynamically

#### Concepts Used

- DataFrames
- CSV Handling
- String Processing
- `apply()` Function
- Custom Functions
- Feature Engineering

---


