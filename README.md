PySpark Data Processing Tasks 


Overview

This repository contains a Jupyter Notebook (Copy_of_Task.ipynb) that demonstrates fundamental data processing operations using Apache Spark with PySpark on Resilient Distributed Datasets (RDDs) and DataFrames. The notebook includes a series of tasks that cover RDD creation, transformations, actions, and DataFrame operations, showcasing common big data processing techniques.

Purpose

The project is designed to illustrate how to perform data manipulation and analysis using PySpark, including:

Creating and manipulating RDDs with NumPy.
Performing statistical computations (sum, average, min, max, count).
Grouping and aggregating data.
Processing text data (tokenization, stopword removal, word frequency counting).
Handling DataFrames for structured data analysis and managing NULL values.

This serves as a practical guide for learning PySpark fundamentals and can be used as a reference for big data processing workflows.

Tasks


The notebook includes the following tasks:

1-RDD Creation and Statistics:

Create an RDD of numbers (1 to 49) using NumPy.
Compute sum, average, maximum, minimum, and count.
Count even vs. odd numbers.


2-People Data Analysis:

Process an RDD of people data (name, age).
Find the oldest person.
Compute the average age.
Group names by age.


3=Text Data Processing:

Load text data from russia.txt into an RDD.
Count total lines and lines containing "Russia".
Tokenize words, remove stopwords, and find the top 5 most frequent words.


4-DataFrame Operations:

Create a DataFrame with columns: id, name, age, salary.
Display schema and select specific columns.
Compute average salary, filter employees by age, and count distinct names.
Group by name and calculate average salary.


5-Handling NULL Values:

Load a CSV file (NullData.csv) into a DataFrame.
Compute average sales and replace NULL values in Name and Sales columns.



Technologies Used

Apache Spark: Distributed computing framework.
PySpark: Python API for Spark.
NumPy: For generating numerical data.
Jupyter Notebook: For interactive development and documentation.
