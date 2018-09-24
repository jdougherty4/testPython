---
title: 'Introduction into coding with Python'
description: ""
---

## Data Types

```yaml
type: NormalExercise
key: d3f28047d0
lang: python
xp: 100
skills: 2
```

There are many types of data. The main four are integer, boolean, float, and strings. To find out what type of data you are using you can use the `type()` function to output the type of data inside the brackets.

In order to output in Python you need to use the `print()` function. It will print whatever is in the brackets.

`@instructions`
The code to output the type of data for `1` has already been filled in for you as an example.
1. Edit the following lines of code so that they would output the types of data for `True`, `3.14`, and `"A string"`.
2. Create a line of cude to output the type of data for `3`.

`@hint`
Make sure to use the print() and/or type().

`@pre_exercise_code`
```{python}
# Load datasets and packages here.
```

`@sample_code`
```{python}
#The code to output the type of data for (1) has already been filled in for you as an example.

print(type(1))

# Please edit the following lines of code so that they would output the types of data for `True`, `3.14`, and `"A string"`.

(type(True)

print(3.14)

"A string"

#Find the Data type of 3 and print it.
 
 
```

`@solution`
```{python}
#The code to output the type of data for (1) has already been filled in for you as an example.

print(type(1))

# Please edit the following lines of code so that they would output the types of data for `True`, `3.14`, and `"A string"`.

print(type(True)

print(type(3.14))

print(type("A string")

#Find the Data type of 3 and print it.
 
print(type(3))
```

`@sct`
```{python}
# Update this to something more informative.
success_msg("Good work! You have found the main types of data used in Python!")
```

---

## Variables Pt. 1

```yaml
type: NormalExercise
key: e193dadeb9
xp: 100
```

You can assign numerical values to variables. In the code below, two new variable "first" have been assigned integer values of 10 and 5, respectively.

`first = 10`

`second = 5`

`print(first)` Output: `10`

Numerical variables can be used for mathematical operations.

`print(first + 15)` Output: `25`

`third = first * 2`

`print(third)` Output: `20`

`print(first + third)` Output: `30`

`@instructions`
Numerical variable `num1` has already been assigned an integer value of `10` for you in the code.
1. Create new variables `num2` and `num3` with the values `30` and `40`, respectively.
2. Print the output of the sum of `num1` and `num2`.
3. Create a new variable `sum123` whose value is the sum of  `num1`, `num2`, and `num3`.
3. Print the output of (`num3`/`num1`+`sum123`).

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# In the code below, the variable `num1` has been assigned an integer value of 10.

num1 = 10

# Create variables `num2` and `num3` by assigning them with values of 30 and 40.




# Print the output of the sum of `num1` and `num2`.



# Create a new variable `sum123` whose value is the sum of  `num1`, `num2`, and `num3`.



# Print the output of (`num3`/`num1`+`sum123`).



```

`@solution`
```{python}
# In the code below, the variable `num1` has been assigned an integer value of 10.

num1 = 10

# Create variables `num2` and `num3` by assigning them with values of 30 and 40.

num2 = 30
num3 = 40

# Print the output of the sum of `num1` and `num2`.

print(num1+num2)

# Create a new variable `sum123` whose value is the sum of  `num1`, `num2`, and `num3`.

sum123 = num1 + num2 + num3

# Print the output of (`num3`/`num1`+`sum123`).

print(num3/num1+sum123)

```

`@sct`
```{python}

```

---

## Variables Pt. 2

```yaml
type: NormalExercise
key: e9057c9cea
xp: 100
```

Variables can also be assigned to different types of data.

`greeting = "Hello World!"` `pi = 3.14` `truth = True`

`print(greeting)` Output: `"Hello World!"` (String variable)

`print(pi)` Output: `3.14` (Float Variable)

`print(truth)` Output: `True` (Boolean Variable)

You can also run equations on different types of data, but the data type of the results will be prioritized in the order of presence of the data types used in the equation. In other words, the sum of string variable `"September"` and integer variable `2018` will output the string "September 2018".

The order of variable types is as follows: Strings, Floats, Integers, and Booleans.

`@instructions`
The string variables "i" and"name", as well as the integer variable "number", have been defined for you. Please fill in the appropriate code lines needed to output (Hello Julien)

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
#The string variables "i" and "name" have been defined for you.
i = "Hello"
name = "Julien"

#Print output "HelloJulien" in the line below by using the addition operator.



#Print output "Hello Julien" in the line below by using the addition operator.



#You can also run mathematical operations on variables of different types. The line of code below will result in a string output.

mult = i+5

```

`@solution`
```{python}
#The string variables "i" and "name" have been defined for you.
i = "Hello"
name = "Julien"

#Print output "HelloJulien" in the line below by using the addition operator.

print(i+name)

#Print output "Hello Julien" in the line below by using the addition operator.

(print(i+" "+name))

#You can also run mathematical operations on variables of different types. The line of code below will result in a string output.

mult = i+5

```

`@sct`
```{python}

```

---

## If statment

```yaml
type: NormalExercise
key: d021cc29c8
xp: 100
```

If statements take a condition. If that condition is true then it will continue and run any indented lines of code below it. If it is false it will not run the indented lines of code below it.

Python is particular about format. The if statements must be indented***.

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
#Boolean can only have one of two values. Either they are "True" or "False". Variables "yes" and "no" have been assigned boolean variables of "True" and "False", respectively.
yes = True

#Boolean variables are generally used for conditional statements such as an if statement.The below lines of code uses boolean variables to determine whether or not the following print() functions will run.
if yes:
  print("Yessssss")

if yes == False:
	print("noooooo")
  
# You can also use boolean conditions for the if statements. They are less than, <, grater than, >, and equals ==. Note the double equals sign. Also less than or equal <= and greater than or equal >=

# The below code is asking if 3 is greater than 2 and if so print "Three is greater than Two"
if 3>2:
	print("Three is greater than Two")

# The below code is asking if 3 is less than 2 and if so print "Three is less than Two"
if 3<2:
	print("Three is less than Two")
print("Three is actually greater than Two")

#

var1 = 10

#Using var1, create an if statement whose condition is that var1 is equal to 10. If correct output "var1 is equal to 10"

if (var1 == 10):
	print("var1 is equal to 10")

#if else statments take a condition and if it is false it runs the else code

if 4 < 3:
	print("4 is less than 3")
else: 
	print("4 is not less than 3")


```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Lists

```yaml
type: NormalExercise
key: 21ec40b6c7
xp: 100
```

A list is a collection of data. It can hold any data type, and can hold as much data as memory allows. A list can contain any combination of data types. One can do all sorts of things with lists such as sorting the list, removing values and adding values. Math operations etc. Lists are an incredibly powerful way of manipulating data in python.

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
#Lists are a collection of data. The lists start at 0. 
integers = [1,2,3,4,5,6]
print(integers[0])
print(integers[5])

print(integers[0:6])
print(integers[:3])
print(integers[3:])


names = ["Name", "hello", "jake", "no", "wat"]
print(names)

print(integers[0] + integers[5])

intnam = ["Name", 1, "hello", 2, "jake", 3, "no", 4, "wat", 5]
print(intnam)

# finds length of a list
print(len(intnam))

# add value to end of a list
intnam.append('hello')        
# add vaue to the start of a list
intnam.insert(0, 'noway')

# create your own list. 

# print the last element of the list

# add the last element of the your list with the last element of the integers list.

# how long is your list?



```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Dictionaries

```yaml
type: NormalExercise
key: 6cb3d2209a
xp: 100
```

A dictionary is a collection which is unordered, changeable and indexed. In Python dictionaries are written with curly brackets, and they have keys and values.

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
person = { "name": "someone", "age": 20, "single": True, "siblings": 2.5}
print(person)

x = person["name"]
print(x)


print(person.name)

person.siblings = 1.3
print(person.siblings)
```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Packages and Pandas

```yaml
type: NormalExercise
key: 382d8315c3
xp: 100
```

A Package is a piece of software that has a specific functionality. Pandas for example allows you to do data analysis in a "easy" way. You could do everything pandas does in plain python but it would be a billion times harder.

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
import pandas as pd

# explain pandas
```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Functions

```yaml
type: NormalExercise
key: b8c2de00fd
xp: 100
```

A function is a block of organized, reusable code that is used to perform a single, related action.

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
list = [1,2,3,4,5,6]
print(list.max())
```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Data frames

```yaml
type: NormalExercise
key: 7530df4f84
xp: 100
```

Basically it's like an excel table but in python.

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
import pandas as pd

df = pd.read_csv("c:\temp\somethig.csv")

df.head()

```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Some functions

```yaml
type: NormalExercise
key: 28b101f19f
xp: 100
```

These are just some basic functions in pandas.

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
df["column"].values_counts()

df["numbers"].sum()
df["numbers"].max()
df["numbers"].min()

# find the mean for the numbers column

# find the median for the numbers column


```

`@solution`
```{python}

```

`@sct`
```{python}

```

---

## Extra practice exercises

```yaml
type: NormalExercise
key: 085b05772b
xp: 100
```



`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}

```

`@sct`
```{python}

```
