# Day 2

Python learning and practice files for Day 2.
# 🧹 Removing Unnecessary Columns

## 📌 Overview

This project demonstrates how to remove unnecessary columns from a dataset using **Python and Pandas**.

Datasets may contain columns that are not required for analysis, such as temporary variables, duplicate identifiers, blank columns, notes, administrative fields, or variables unrelated to the research question.

Removing these columns makes the dataset **cleaner, simpler, and easier to analyze**.

## 🎯 Objectives

- Identify unnecessary columns in a dataset.
- Remove columns that are not useful for analysis.
- Improve dataset organization and readability.
- Prepare the dataset for further data analysis.

## 🗑️ Examples of Unnecessary Columns

Some examples include:

- Temporary variables
- Duplicate identifiers
- Blank variables
- Notes
- Administrative fields
- Variables unrelated to the research question

## 🐍 Python Code

```python
data.drop(
    columns=["Student_ID"]
)
