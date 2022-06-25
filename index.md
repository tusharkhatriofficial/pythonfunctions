---
title: "Python Functions"
permalink: /
layout: default
---

# Python Functions

A function is a block of code which only runs when it is called. You can pass data, known as parameters, into a function.

> A function can return data as a result

## Creating a Function

In Python a function is defined using the `def` keyword:

### Example

```Python
  def my_function():
    return "Hello from a python function"
```

## Calling a Function

To call a function, use the function name followed by parenthesis

### Example

```Python
  def my_function():
    print("Function called")
  my_function()
```

## Arguments

Information can be passed into  functions as arguments. Arguments are specified after the function name inside the parenthesis. You can add as many arguments as you want, just separate them with a comma.

### Example

```Python
  def sum(num1, num2):
    print(num1+num2)

  sum(5, 10)
  sum(20, 60)
  sum(100, 231)
```
