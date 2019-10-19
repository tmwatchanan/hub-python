class: center, middle

# Python

### 19/10/2019

---

# Agenda

1. Review
1. Intro to Function
   <!-- 1. Flowchart -->
1. Debugging

---

# Review (17/10/2019)

1. Primitive types
1. List
1. range()
1. len()

---

<!-- # Abstraction

- A technique for managing complexity of computer systems
- Some examples of **definitions** are:
  1. the process of **removing** physical, spatial, or temporal **details** or attributes **in the study of** objects or **systems** in order to **focus attention** on details of higher importance, it is also very similar in nature to the process of generalization;
  1. the creation of **abstract concept-objects** which are created by mirroring common features or attributes from various non-abstract objects or systems of study — the result of the process of abstraction.

--- -->

<!-- # Flowchart

> "a type of diagram that represents a workflow or process"

![](2019_10_19/lamp_flowchart.png)

--- -->

# Primitive Types

- Integer
- Float
- String
- Boolean

---

# Intro to Function

- Math function

![](2019_10_19/math_function.png)

---

# Intro to Function (cont.)

- A function

![](2019_10_19/function.png)

---

# Intro to Function (cont.)

- **print()** is a function that prints the specified message to the screen, or other standard output device
- take multiple arguments

---

# Intro to Function (cont.)

- **len(x)** is a function that returns the number of items in an object.
  - x can be some data types such as **list**, set, etc.
- **range()** is a function that is used to generate a sequence of numbers over time

  ```python
  range([start,] stop [, step]) --> range object
  ```

  - **start** (optional) = _starting point_ of the sequence [default = 0]
  - **stop** (required) = _endpoint_ of the sequence = the endpoint is not included in the sequence
  - **step** (optional) = _step size_ of the sequence [default = 1]

- These are built-in functions:
  https://docs.python.org/3/library/functions.html

---

# Learn a New Function for Taking Input

- **input()** is a function that takes the input from the user
  - There is one parameter for **input** function = `

```python
input(prompt)
```

```python
x = input("Enter number :")
print(x)
print ("type of x", type(x))
```

- **type(x)** is also a function that returns the type of object x

---

# Range Object

```python

>>> range(5)
range(0, 5)

>>> list(range(5))
[0, 1, 2, 3, 4]
```

---

# Debugging

- The process of **detecting** and **removing** of existing and potential **errors** (also called as '_bugs_') in a software code that can cause it to behave unexpectedly or crash.

---

# Loop Problems

Write these programs:

1. print out the first 10 natural numbers
1. print out the natural numbers within a range of [5, 10]
1. print out the natural numbers without a range of [0, 19)
1. print out the natural numbers within a range of (2, 7)
1. print out the natural numbers within a range of [12, 21)
1. print out the word "Luffy" for 5 times, separated with the symbol ' '

1. Take an input number from the user to be the endpoint of loop. The loop is intended to print out the current range number

## ยากส์

1. Create a 5-iteration loop, and each iteration takes an input number. The wanted result is the sum of all input numbers
