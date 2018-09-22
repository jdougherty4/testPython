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
Fill in the missing functions.

`@hint`
Try print() or type()

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

i is a variable. It stores what you put in it. You need to print it to see its output.

`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
i = "hello"
print(i)

name = "Julien"
print(name)

#variables can hold any sort of data type

number = 55
print(number)

# you can add and subtract variables

first = 5
second = 9
added = first + second
print(added)

sub = first - second
print(sub)

mult = first * second
print(mult)

div = first / second
print(div)


# this doesn't work. Why?
print(Jake)

# create your own variable and print it. 

```

`@solution`
```{python}
i = "hello"
print(i)

name = "Julien"
print(name)

#variables can hold any sort of data type

number = 55
print(number)

# you can add and subtract variables

first = 5
second = 9
added = first + second
print(added)

sub = first - second
print(sub)

mult = first * second
print(mult)

div = first / second
print(div)


# this doesn't work. Why?
print(Jake)

# create your own variable and print it. 
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



`@instructions`


`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
if 3 > 2: 
  print("True")
  
if 0 > 5: 
  print( 3 > 2)
  
  print("Hello")
 
print("no")
# in python indentation is very important

bigger_number = 6
smaller_number = 2

if bigger_number > smaller_number:
	print(bigger_number + smaller_number)

## if else statments
if 4 < 3:
  print(False)
else: 
  print(True)
  
 # if else if



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
list = [1,2,3,4,5,6]
print(list[0])
print(list[5])

print(range(0,5))

names = ["Name", "hello", "jake", "no", "wat"]
print(names)

print(list[0] + list[5])

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

## Packages

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

## Pandas

```yaml
type: NormalExercise
key: fb17ea9bfa
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

## explain pandas
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
