# Introduction to Python Programming

1. **What is Python?**
2. **Why Use Python?**
3. **Variables and Constants**
   - Variables
   - Constants
4. **Affection (Assigning Value to Variable or Constant)**
5. **Simple Data Types**
   - Integer (`int`)
   - Character (`char`)
   - Floating Point (`float`)
   - Boolean (`bool`)
6. **Conditional Statements**
   - `if`, `elif`, `else`
7. **Logical Operators**
   - `and`, `or`, `not`
8. **Mathematical Operators**
   - Addition (`+`)
   - Subtraction (`-`)
   - Multiplication (`*`)
   - Division (`/`)
   - Floor Division (`//`)
   - Modulus (`%`)
   - Exponentiation (`**`)
9. **While Loop**
10. **For Loop**
11. **Strings**
12. **Lists**
13. **Arrays**
14. **Functions**

# By the end of this course, you'll be able to:
- Write basic programs that solve problems.
- Use essential programming concepts to structure your code.
- Feel confident in your coding skills to tackle more complex challenges in future courses.

# Comprehensive Programming Guide

## 1- What is Coding?
Coding is the process of writing instructions for computers using programming languages. These instructions tell computers how to perform specific tasks, from simple calculations to complex applications.

## 2- Why Learn Coding?
- Problem-solving skill development
- High job demand across industries
- Creative expression through technology
- Better understanding of modern technology
- Career advancement opportunities
- Ability to build your own solutions

## 3- How to Learn Coding
1. Start with basic languages (Python/JavaScript)
2. Practice regularly
3. Use online resources (Codecademy, FreeCodeCamp)
4. Build personal projects
5. Join coding communities
6. Watch tutorials and read documentation




## Chapitre01: Core Programming Concepts

### 1-Variables and Constants


In programming, variables and constants are used to store data that can be accessed and manipulated within a program. While they may seem similar, they serve different purposes and have different rules for how they can be used.


####  1-a) What is a Variable?
A **variable** is a storage location in a program that holds data that can be changed or modified during the execution of the program. The data stored in a variable can vary (hence the name "variable") throughout the program.

#### Rules for Naming Variables:
1. **Start with a letter or an underscore**: A variable name must begin with a letter (a-z, A-Z) or an underscore (_).
2. **Use letters, numbers, and underscores**: After the first character, you can use letters, numbers (0-9), and underscores.
3. **No spaces**: Variable names cannot contain spaces.
4. **Case-sensitive**: Python is case-sensitive, so `variable`, `Variable`, and `VARIABLE` are different.
5. **Cannot use reserved words**: You cannot use reserved words (keywords) of the programming language, such as `if`, `else`, `while`, `for`, etc., as variable names.

####   1-b)What is a  Constant?

A  **constant**  is a value that, once assigned, cannot be changed during the program's execution. It is used to store values that should remain constant throughout the program, such as mathematical constants or configuration values that should not be altered.

#### Characteristics of Constants:
- **Immutable**: Once a constant is assigned a value, it cannot be modified.
- **Used for fixed values**: Constants are ideal for storing values that don’t change during program execution, like mathematical constants (e.g., pi) or application settings (e.g., maximum allowed age, API keys).
- **Helps with readability**: Using constants can make code more readable and maintainable, as they provide a clear indication that a value shouldn't change.

#### Rules for Naming Constants:
1. **Uppercase letters**: By convention, constants are written in **uppercase letters** to make them easily distinguishable from variables.
2. **Underscores between words**: If a constant name contains multiple words, separate them with underscores for better readability (e.g., `MAX_SPEED`).
3. **No spaces**: Constant names cannot contain spaces.
4. **Avoid modification**: Once a constant is assigned, it should not be modified anywhere in the program.

#### Example of a Constant:
```python
PI = 3.14159           # A constant for the value of pi
MAX_SPEED = 120        # A constant representing the maximum speed allowed
GRAVITY = 9.8          # A constant for Earth's gravity in m/s^2
```
```python
# Variables (can change)
age = 25
name = "John"

# Constants (shouldn't change)
PI = 3.14159
MAX_USERS = 100
```

### Assignment (Affectation)
```python
# Basic assignment
x = 10
message = "Hello"

# Multiple assignment
a, b = 1, 2

# Augmented assignment
counter = 0
counter += 1  # Increment
```

### Simple Data Types
```python
# Integer
age = 30

# Float
price = 19.99

# String
name = "Alice"

# Boolean
is_active = True
```

### Logical Operators
```python
x = 5
y = 10

# AND operator
print(x > 0 and y < 20)  # True

# OR operator
print(x < 0 or y > 8)    # True

# NOT operator
print(not x > y)         # True
```

### Mathematical Operators
```python
a = 10
b = 3

print(a + b)   # Addition: 13
print(a - b)   # Subtraction: 7
print(a * b)   # Multiplication: 30
print(a / b)   # Division: 3.333...
print(a % b)   # Modulo: 1
print(a ** b)  # Exponent: 1000
print(a // b)  # Floor division: 3
```

### If Statements
```python
score = 85

if score >= 90:
    print("Grade A")
elif score >= 80:
    print("Grade B")
else:
    print("Grade C")
```

### Loops

#### While Loop
```python
counter = 0
while counter < 5:
    print(counter)
    counter += 1
```

#### For Loop
```python
# Iterating over range
for i in range(5):
    print(i)

# Iterating over list
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```
## Algorithms and Data Structures
An algorithm is a step-by-step procedure for solving problems. Data structures organize and store data efficiently.

### Pseudocode
Pseudocode is plain-language programming logic. Example:
```
START
SET number = user_input
IF number > 0 THEN
    PRINT "Positive"
ELSE
    PRINT "Negative"
END
```
# Example: Calculating the Average  of a Student in a Subject

## Problem Scenario:
Imagine you're tasked with calculating the average score (called "moyenne") of a student in a subject based on several test scores. You need to:
1. Collect multiple test scores from the user.
2. Calculate the average of these scores.
3. Display the average to the user.

### Problem:
- A student has taken 5 tests in a subject.
- You will ask for the score of each test and then calculate the average score.

---

## Steps to Solve the Problem

### Step 1: Define the Problem
We need to:
1. Collect multiple test scores (5 in this case).
2. Calculate the average score (moyenne).
3. Display the result.

### Step 2: Break Down the Problem
1. **Get the test scores** from the user (for 5 tests).
2. **Calculate the average** by summing all the test scores and dividing by the number of tests.
3. **Display the average** to the user.

### Step 3: Pseudocode
```plaintext
START
  1. Initialize a variable to store the total score as 0.
  2. Initialize a variable to store the number of tests.
  3. Loop to get the score for each test (5 times):
     - For each test, prompt the user to enter the score.
     - Add the entered score to the total score.
  4. Calculate the average by dividing the total score by the number of tests.
  5. Display the average score (moyenne).
END
```