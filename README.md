# **PYTHON Reference Guide** ![](https://img.icons8.com/color/48/python--v1.png) 

Welcome to my repository  which is a structured and practical python study guide designed to help you learn and practice from basics to more advanced topics.

This  will be categorised examples with clear explanations for each topic, code examples and practice exercises based on user input at the end of certain sections and Mini Projects

📌 Projects will be added soon.

[Visit my Github](https://github.com/CelinaGitau)

Welcome feedback, suggestions or questions!!

## Table of Contents :
1. #### What is Python
2. #### Python File Handling
   * Importing, reading csv Files 
3. #### Learning Python control flows
    + Loops `while`, `break`, `continue`
    + Conditions `if`,`elif`,`else`
4. #### Defining Fuctions
   * Range 
5. #### Practice Exercises
6. ####  Mini Projects
  
----

###  What is Python ❓
Python is a simple and easy to read programming language that is beginner friendly that helps users analyse data, allows users to solve complex problems quickly, create visualisations, and build useful tools applications

#### ⛏️ Tools used 
* ✅Google Colab – for running and documenting the analysis

* ✅Pandas – for data cleaning and manipulation

* ✅Matplotlib – for creating visualisations

* ✅Seaborn – for enhanced and styled data visualisation

***
     
### Importing, reading csv, Files 
How to import libraries, read CSV files , and work with data in python using google colab


#### Syntax
```
from google.colab import files
files = files.upload()
```
Inspect data, load and read your  slected csv file and named file as sales

```
import pandas as pd
sales = pd.read_csv('sales.csv')
sales
```
### LOOPS : `while`, `continue` and break control flows
This repeats actions until a condition is met

 **x** variable, starting with value of 1
 
The loop runs as long as **x is less than 10**

Each time the loop runs, **x increases by 1** `x += 1`

This allows the program to automatically count up  from 1 until the  condition is no longer true (up to 10)

#### Example Syntax:
```x = 1
while x <10:
  print (x)
  x += ```
To print all even numbers using loops from 0 to 30
#### Example Syntax: using a `while`loop
```number = 0
while number <= 30:
  print (number)
  number += 2
```
### LOOP using `continue`: skips current iteration
#### Example Syntax: using `continue`
````
number = 0
while number <= 30:
  number += 2
  if number==32:
    continue
  print(number)
```
 #### LOOP using `break`: stops excecuting the loop completely





  




