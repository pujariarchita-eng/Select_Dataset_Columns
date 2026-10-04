# Select Dataset Columns Using Pandas loc and iloc

## 📌 Project Overview

This project demonstrates how to select specific rows and columns from a Pandas DataFrame using the `loc` and `iloc` methods.

The task uses a small Iris dataset and focuses on understanding label-based and position-based indexing in Pandas.

---

## 🎯 Objective

The main objective of this task is to:

- Understand Pandas DataFrames.
- Select specific rows and columns using `loc`.
- Select specific rows and columns using `iloc`.
- Understand the difference between `loc` and `iloc`.
- Practice selecting individual values, rows, columns, and combinations of rows and columns.

---

## 🛠️ Tools and Technologies

- Python
- Pandas
- Jupyter Notebook

---

## 📊 Dataset

The project uses sample records from the **Iris Dataset**.

The dataset contains the following columns:

| Column | Description |
|---|---|
| `sepal_length` | Length of the sepal |
| `sepal_width` | Width of the sepal |
| `petal_length` | Length of the petal |
| `petal_width` | Width of the petal |
| `species` | Species of the flower |

### Sample Dataset

| sepal_length | sepal_width | petal_length | petal_width | species |
|---:|---:|---:|---:|---|
| 5.1 | 3.5 | 1.4 | 0.2 | setosa |
| 4.9 | 3.0 | 1.4 | 0.2 | setosa |
| 4.7 | 3.2 | 1.3 | 0.2 | setosa |
| 4.6 | 3.1 | 1.5 | 0.2 | setosa |
| 5.0 | 3.6 | 1.4 | 0.2 | setosa |

---

## 🔍 What is `loc`?

`loc` is used for **label-based indexing** in Pandas.

### Example: Select a row

```python
df.loc[0]
