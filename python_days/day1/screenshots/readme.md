📊 Student Data Analysis with Python

A beginner-friendly Data Analysis project using Python and Pandas.
This project demonstrates how to load an Excel dataset, inspect the
data, and read the first five rows for an initial understanding of the
dataset.

📌 Project Overview

The goal of this project is to practice the basic steps of data analysis
using Pandas:

Importing the Pandas library

Loading an Excel dataset

Understanding the structure of a dataset

Reading the first five rows

Identifying columns and missing values

Preparing the data for further analysis

The dataset contains student academic information such as attendance,
assignment scores, midterm scores, final scores, and academic status.

🛠️ Technologies Used

Technology        Purpose

🐍 Python         Data analysis programming
🐼 Pandas         Data loading and analysis
📗 Excel          Dataset storage
☁️ Google Colab   Running the Python notebook

📂 Dataset Information

The Excel dataset contains student-related academic records.

Main Columns

Student_ID --- Unique ID for each student

Program --- Student's academic program

Attendance_Percent --- Student attendance percentage

Assignment_Score --- Assignment score

Midterm_Score --- Midterm examination score

Final_Score --- Final examination score

Academic_Status --- Student's academic standing

Example Academic Status Values

At Risk

Good Standing

Some records contain missing values (NaN), which will be handled
during the data-cleaning stage.

🚀 Project Steps

1. Import the Library

import pandas as pd

Pandas is imported with the common alias pd.

2. Load the Dataset

The Excel file is loaded using read_excel():

date = pd.read_excel("/content/drive/MyDrive/Colab Notebooks/python/Book1211.xlsx")

This reads the Excel dataset into a Pandas DataFrame.

Note: The variable name date works in Python, but data is
clearer and recommended.

A cleaner version is:

data = pd.read_excel("/content/drive/MyDrive/Colab Notebooks/python/Book1211.xlsx")

3. Read the First Five Rows

To view the first five records:

data.head()

By default, head() returns the first 5 rows.

This is useful for quickly checking:

Column names

Data values

Data types at a glance

Missing values

Whether the dataset loaded correctly

🔎 Sample Output

The first five records include examples such as:

Student_ID   Program            Attendance   Assignment     Midterm       Final Academic
Status

STD0229      Public Health            58.7         69.8        49.5         NaN At Risk

STD0112      Business                 55.6         93.7        52.4        86.7 At Risk
Administration

STD0272      Public Health            95.4         53.1         NaN        76.2 Good
Standing

STD0055      Engineering              86.7         72.4        71.0        85.8 Good
Standing

📸 Project Screenshots

Loading the Dataset

The notebook imports Pandas and loads the Excel file from Google Drive.



Reading the First Five Rows

The head() function is used to display the first five rows of the
dataset.



📈 What I Learned

Through this project, I practiced:

Importing Python data-analysis libraries

Reading Excel files with Pandas

Working with DataFrames

Using head() to inspect data

Recognizing missing values such as NaN

Understanding the structure of student academic data

Preparing a dataset for deeper analysis

🔮 Future Analysis

The project can be extended with:

Missing-value analysis

Duplicate detection

Data cleaning

Descriptive statistics

Average scores by program

Attendance analysis

Academic-status analysis

Data visualization

Correlation analysis

Student performance insights

Example:

data.info()

data.describe()

data.isnull().sum()

📁 Suggested Project Structure

student-data-analysis/
│
├── README.md
├── Book1211.xlsx
├── student_data_analysis.ipynb
└── screenshots/
    ├── loading-data.png
    └── first-five-rows.png


⭐ Conclusion

This project provides a simple introduction to Python-based data
analysis using Pandas.
Starting with dataset loading and head() inspection creates a strong
foundation for the next stages of data cleaning, analysis,
visualization, and reporting.

⭐ If you find this project useful, feel free to star the
repository!
