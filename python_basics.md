
# Introduction

This is a tutorial on Python, which is a part of the tutorial on data analysis.

# Installation

You can install Python with necessary packages from Anaconda "https://www.anaconda.com/download/#macos".

I recommend that you install the latest Python 3.

After installation. You can open the "cmd"0 in Windows or "terminal" in MacOS, and type:

```
jupyter notebook
```
Then you can use Python in an interactive way by creating a new Python notebook.

# HelloWorld!

Now click a block in the notebook. You can type your first Python program and press "Shift + Enter" to execute it. Then you will see the magic as follows:


```python
print("HelloWorld!")
```

    HelloWorld!


Here, the line print("HelloWorld!") tells Python to display "HelloWorld!" on the screen. Note that print() is a function that you let Python to print the thing in the parenthesis on the screen.

# Assign values

Values and words are stored in Python with a unique name. When you are doing assignment, you tell Python the name of a certain value. Next time you refer to this name, Python will know that you will use the specific value.

Assignment is done by "=" sign. Not that it is not a judgment whether values are equal. Instead, it means that we assign a value from the right-handed side to a variable name on the left-handed side.


```python
a = 1
name = "Yuhao"
```

Above is an example of assignment. The first line assign an integer 1 to the variable with the name "a". The second line assign a word "Yuhao" to the variable with the name "name".

It is always recommended that you use nice names for your variables. "gender" is much better than "sdf1324dsf1" when you want to use it to stand for the gender type.

After successful assignment. You can print the value by calling the variable:


```python
print(a)
```

    1


Python will check the value of the variable "a" and print it on the screen.

# Change value of a variable

After assignment, you can always change the value of the variable.

Python is a dynamic language. It means that you can change the value to other types. For example:


```python
b = 1
print(type(b))
b = "people"
print(type(b))
b = [1, 2, 3]
print(type(b))
```

    <class 'int'>
    <class 'str'>
    <class 'list'>


Although the variable "b" is firstly used as an number. You can easily assign an text or list to the variable. The type of this variable changes accordingly. This feature is only permitted in languages like Python but will definitely not allowed in static languages like C.

# Basic calculations

Calculations are done in Python simply like basic algebra. For example:


```python
a = 3
b = 5
print(a + b)
print(a - 1)
print(2 * 4)
print(a / b)
print(a ** b)
```

    8
    2
    8
    0.6
    243


The signs "+", "-", "*", "/", "**" stands for "add", "minus", "times", "divide", and "power", respectively.

You can also use parentheses to make certain calculations prior to others. Parentheses can be used in parentheses. But do never use bracket and braces! They have other roles to play in Python. For example:


```python
value = ((2 + 3) * (12 - 0.4) ** (3 / 5)) / (1 + (1 / 3) ** (1 / 3))
print(value)
```

    12.849764674622323

