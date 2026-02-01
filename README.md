# DAY_27_PANDAS_BASICS
# Day 27 – Pandas Basics: Reading & Exploring CSV Data

## Overview
This day focuses on learning **Pandas fundamentals** required for Machine Learning and Data Analysis.  
The goal is to understand how real-world datasets are loaded, inspected, and prepared before any cleaning or modeling.

This repository contains **practice exercises only**, not full projects.

---

## Topics Covered

### 1. Why Pandas?
- NumPy is efficient for numerical computation but lacks structure for real datasets.
- Pandas introduces **tabular data handling** using rows and columns.
- It is the backbone of data preprocessing in ML pipelines.

---

### 2. Core Data Structures
- **List** → Simple container, no structure, slow for large data
- **NumPy Array** → Fast numerical operations, no column labels
- **Pandas DataFrame** → Labeled rows & columns, ideal for datasets

---

### 3. Reading CSV Files
Learned how to load external datasets using:

```python
import pandas as pd
df = pd.read_csv("data.csv")
