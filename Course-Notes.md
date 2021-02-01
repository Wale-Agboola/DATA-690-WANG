# Class Session 1 Notes:

## Important Termonolgy:

- ipynb = iteractive python notebook
- pwd = present working directory

## CHAPTER 1-2 READING NOTES

### CHAPTER 1:
- When we obtain data it is unstructured most of the time and its our job as data scientist to structure that data and draw useful information from it.
- Python is a scrypting language that can be used to quickly write small programs or scripts that automate different tasks.
- In the last 10 years python has become one of the most important languages for data science, machine learning, and general software development.
*Drawbacks to Python*
- As Python is an interpreted programming language, in general most Python code will run substantially slower than code written in a compiled language like Java or C++.
- Python can be a challenging language for building highly concurrent, multithreaded applications, particularly applications with many CPU-bound threads.
*Essential Python Libraries*
- **Numpy(Numerical Python)** provides the data structures, algorithms, and library glue needed for most scientific applications involving numerical data in Python.
- For numerical data, NumPy arrays are more efficient for storing and manipulating data than the other built in Python data structures.
- Libraries written in a lower level language, such as C or Fortran, can operate on the data stored in a NumPy array without copying data into some other memory representation.
- **Pandas** provides high level data structures and functions designed to make working with structured or tabular data fast, easy, and expressive.
- Its primary objects include DataFrame, a tabular, column oriented data structure with both row and column labels, and the Series, a one dimensional labeled array object.
- **matplotlib** is the most popular Python library for producing plots and other two dimensional data visualizations.
- **scipy** is a collection of packages addressing a number of different standard problem domains in scientific computing.
- **scikit-learn** is the general purpose machine learning toolkit for Python Programmers. It includes submodules like...
  - Classification
  - Clustering 
  - Dimensionality reduction
  - Model Selection
  - Preprocessing 
- **statsmodel** is a statistical analysis package that implements a number of regres‐ sion analysis models popular in the R programming language. 
- It contains algorithms for classical statistics and econometrics. It also includes submodules like...
  - Analysis of Variance 
  - Regression Models
  - Time Series Analysis
  - Nonparametric Methods
  - Visualizations of statistical model results
- **Import Conventions** 
  - import numpy as np
  - import matplotlib.pyplot as plt
  - import pandas as pd
  - import seaborn as sns
  - import statsmodels as sm
  
### Chapter 2:

- Python is an interpreted language. The python interpreter runs a program by executing one statement at a time.
- IPython executes the code in the specified file in the same process, enabling you to explore the results interactively when its done.
- **Tab Completion**: While entering expressions in the shell, pressing the Tab key will search the namespace for any variables (objects, functions, etc.) matching the characters you have typed so far.
- Also allows you to see the modues in a imported library
- **Introspection**: Using a question mark (?) before or after a variable will display some general infor‐ mation about the object.
- This is referred to as object introspection. If the object is a function or instance method, the docstring, if defined, will also be shown
- Then using ? shows us the docstring
- Using ?? will also show the function’s source code if possible
- A number of characters combined with the wildcard (*) will show all names matching the wildcard expression
- **Terminal Keyboard Shortcuts** See page 27 of text 
- **Magic Commands** are designed to facilitate common tasks and enable you to easily control the behavior of the IPython system
- For list of magic commands see page 29 in text 
- Python uses whitespace (tabs or spaces) to structure code instead of using braces as in many other languages like R, C++, Java, and Perl
- **Scalar Types**: standard library that has a built in types used for handling diferent types of data-
- Numeric types *See page 39*
- Strings *See page 39 - 42*
- Booleans: the ttwo boolean values in python are written as true and false. 
- **Control Flow**
- if
- elif
- else 
- for loops 
- while loops 
- pass
- range
