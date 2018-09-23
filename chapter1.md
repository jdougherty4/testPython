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

There are many types of data. The main four are integer, boolean, float, and strings. To find out what type of data you are using you can use the type() function.It outputs the type of data inside the brackets.

In order to output in Python you need to use the print() function. It will print whatever is in the brackets

`@instructions`
The first line has been coded to output the type of data for (1). Please complete the following lines of code by filling in the missing functions, so that they would output the types of data for (True), (3.14), and ("A string").

`@hint`
Make sure to use the print() and/or type().

`@pre_exercise_code`
```{python}
# Load datasets and packages here.
```

`@sample_code`
```{python}
print(type(1))
# print type 1

___(type(True))

print(___(3.14))

___(___("A string"))

#Find the Data type of 3
```

`@solution`
```{python}
print(type(1))
# print type 1

print(type(True))

print(type(3.14))

print(type("A string"))

#Find the Data type of 3
```

`@sct`
```{python}
# Update this to something more informative.
success_msg("Good work! You have found the main types of data used in Python!")
```

---

## Variables

```yaml
type: NormalExercise
key: e193dadeb9
xp: 100
```



`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
# you can assign values to variables. In the code below, the variable "first" has been assigned an integer value of 10 
# Make a second variable with the name "second" and a value of 5.
first = 10
____

#Numerical variables can be used for mathematical operations 

print(first + second)

#You can also create a new variable that equals operations of other variables. In the line of code below, a new variable "add" has been assigned the value which equals to the sum of "first" and "second".

add = first + second

#Please print the variable "add"

____

#Create a variable named "sub" whose value equates to "first" subtracted by "second", and print it.

____

#Create two variables named "mult" and "div" that is "first" multiplied and divided by "second", respectively, and print them seperately.

____
____
____
____
```

`@solution`
```{python}
# you can assign values to variables. In the code below, the variable "first" has been assigned a integer value of 10 
# Make a second variable with the name "second" and a value of 5.
first = 10

#Numerical variables can be used for mathematical operations 

print(first + second)

#You can also create a new variable that equals operations of other variables. In the line of code below, a new variable "add" has been assigned the value which equals to the sum of "first" and "second".

add = first + second

#Please print the variable "add"

print(add)

#Create a variable named "sub" whose value equates to "first" subtracted by "second", and print it.

sub = first - second

#Create two variables named "mult" and "div" that is "first" multiplied and divided by "second", respectively, and print them seperately.

mult = first * second
div = first / second
print(mult)
print(div)

```

`@sct`
```{python}

```

---

## Variable Pt. 2

```yaml
type: NormalExercise
key: e9057c9cea
xp: 100
```

i is a variable. It stores what you put in it. You need to print it to see its output.

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
____

#Print output "Hello Julien" in the line below by using the addition operator.
____

#You can also run mathematical operations on variables of different types. The line of code below outputs
mult = i*5

```

`@solution`
```{python}

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



`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
jake = { "name": "Jake", "age": 20, "single": True, "hotness": 2.5}
print(jake)

print(jake.name)

jake.hotness = 1.3
print(jake.hotness)
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



`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
import pandas as pd

df = pd.read_csv("somethig.csv")

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
