# Python Data Analysis Assignment 1: NumPy and Pandas

This repository contains the first assignment for Python Data Analysis, focusing on core numerical computations and structured data manipulation using **NumPy** and **Pandas**. 

## 📋 Overview
The primary objective of this assignment is to practice fundamental data engineering and analysis concepts including array operations, data alignment, indexing, filtering, and group aggregation techniques using real-world scenarios.

## 🛠️ Tasks & Structure

### 1. NumPy Array Operations
*   **Scenario:** Analyzing daily average temperatures recorded over a two-week period.
*   **Key Operations:**
    *   Creating and inspecting 1D arrays (`shape`, `dtype`, `size`).
    *   Vectorized math operations (converting Celsius to Fahrenheit).
    *   Descriptive statistics (`np.min()`, `np.max()`, `np.average()`).
    *   Array slicing (extracting specific intervals like weekends or mid-week).
    *   Handling multi-dimensional data (creating and slicing a 2D array representing multiple weeks).

### 2. Pandas Series
*   **Scenario:** Student marks management using ranked custom indices.
*   **Key Operations:**
    *   Instantiating explicit index series labels (`Rank1` to `Rank5`).
    *   Positional vs. label-based indexing using `.loc` and `.iloc`.
    *   Applying boolean masks to filter values above specific thresholds.
    *   Mutating series data, using `.drop()` to remove indices, and performing scalar mathematics (calculating GPA metrics).

### 3. Pandas DataFrame
*   **Scenario:** Transaction logging system featuring category, region, and financial distribution.
*   **Key Operations:**
    *   Constructing DataFrames from dictionary data structures.
    *   Exploratory Data Analysis (EDA) using `.info()`, `.head()`, `.tail()`, `.columns`, and `.dtypes`.
    *   Multi-conditional logical filtering (e.g., finding specific regional transactions over a certain price threshold).
    *   Categorical breakdowns using `.value_counts()` and `.nunique()`.
    *   Split-apply-combine transformations using `.groupby()` to calculate regional mean metrics.
    *   Data manipulation including value adjustments, calculating derivative features (discounts), and standard row/column deletions.

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the required libraries:
```bash
pip install numpy pandas
```

### Execution
Open the provided Jupyter Notebook (`.ipynb` file) in Google Colab or your local Jupyter environment to view the code blocks and run the execution flows.

```python
import numpy as np
import pandas as pd
```

## 📝 License
This project is open-source and intended for educational purposes.

