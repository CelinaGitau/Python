# **PYTHON Reference Guide** ![](https://img.icons8.com/color/48/python--v1.png) 

Welcome to my repository  which is a structured and practical python study guide designed to help you learn and practice from basics to more advanced topics.

This  will be categorised examples with clear explanations for each topic, code examples and practice exercises based on user input at the end of certain sections and Mini Projects

📌 Projects will be added soon.

[Visit my Github](https://github.com/CelinaGitau)

Welcome feedback, suggestions or questions!!

## Table of Contents :
 #### What is Python
 #### Python Importing, reading csv Files 
 #### Loops `while`, `break`, `continue`
 #### `Range` Functions
 #### Conditions `if`,`elif`,`else`
 #### Practice Exercises
 #### Projects   
----

###  What is Python ❓
Python is a simple and easy to read programming language that is beginner friendly that helps users analyse data, allows users to solve complex problems quickly, create visualisations, and build useful tools applications

#### ⛏️ Tools used 
* ✅Google Colab – for running and documenting the analysis

* ✅Pandas – for data cleaning and manipulation

* ✅Matplotlib – for creating visualisations

* ✅Seaborn – for enhanced and styled data visualisation
***
     
### Importing, reading csv, Files into pandas dataframe
How to import libraries, load, read CSV files

#### Syntax
```
from google.colab import files
files = files.upload()
```

#### Syntax: Read (*your selected*) CSV files 
```
import pandas as pd
sales = pd.read_csv('sales.csv')
sales 

```

### LOOPS using `while`, `continue` and `break`
This repeats actions until a condition is met

#### Syntax 
```
x = 1
while x <10:
  print (x)
  x += 1
```
Write a loop using `contine` and `break` and print all even numbers from 0 to 30 *

#### Syntax `continue` 
```
number = 0
while number <= 30:
  number += 2
  if number==32:
    continue
  print(number)

```

#### Syntax using `break`
```
number = 0
while number <= 30:
  number+=2
  if number == 32:
    break
  print(number)

```
Write a Loop and print all odd numbers less than or equal to 30

#### Syntax using `%`

`%` checks if this is an even number 
 x += 1 #adds 1 to each time
```
x =  0
while x <= 30:
  x += 1 
  if x % 2 == 0:
    continue
  print (x)
```
----
### `Range` Function
Range generates  numbers from 3 and stopping before 10 

#### Syntax 
```
for  number in range (3, 10):
  print (number)
```

Print numbers (x) starting at 4, increasing by 3 each time, and stopping before 15
#### Syntax
```
for x in range (4, 15, 3):
 print (x)
```
#### Syntax: Odd numbers 
```
print ("odd numbers from 1 to 100")
for x in range (1, 101, 2):
  print (x, end= " ")
```

### Range with `end ` Variable

Print all even numbers from 0 to 100

#### Syntax 
````
print ("Even numbers from 0 to 100")
for n in range( 0, 101, 2):
  print (n, end= " ")
````
👉 [See full code](https://github.com/CelinaGitau/Python/blob/21e3aa3adb6b5e04aa5e1aae2c9333704dda9971/Python_Loop.ipynb)
 ----
### Conditions `if`, `elif` and `else`
**`if`**: checks a condition. If it is true the code runs 

💭 Think *if this happens, do this*

#### Syntax
````
a = 8
if a > 6:
  print ('a is greater than 6')
````

 **`elif`** short for else if : checks another condition if the first was false
 
💭 Think: *if the first thing didnt happen, check this instead*

**`else`**: Runs if none of the above conditions are true

💭 Think: *If nothing else worked, do this*

#### Syntax
````
a = 10
if a > 15: # 10 > 15 is false
 print('a is greater than 15')
elif  a == 15:
 print ('a is equal to 15')
else: 
  print ('a is less than 15')
````
**[See full code](add it here)**
----
#### **FizzBuzz Task**
| **Symbol** |   **Meaning**     |  **Simple Explanation**            |**Example**             |
|------------|-------------------|------------------------------------|------------------------|
|  ` ==`     | Equal to          | Checks if values are the same      | `number == 5`          |
|  `%`       | Modulus (remainder| Gives the remainder after dividing | `10 % 3 = 1`           |
| `""`       | String (text)     | Displays text                      |  " Fizz" or "buzz"     |
                                                                         
#### Syntax 
````
for number in range(1, 100):
  if number % 3 == 0 and number % 5 == 0:
    print("fizzbuzz")
  elif number % 3 == 0:
    print("fizz")
  elif number % 5 == 0:
    print("buzz")
  else:
    print(number)
````
👉 **[See full Code](https://github.com/CelinaGitau/Python/blob/8caff455b26962ff842ae27962371c5e70d9e2a3/Python_if_elif_elsed0.ipynb)**

[Practice Exercises]() 


