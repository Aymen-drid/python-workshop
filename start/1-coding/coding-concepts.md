# Basic Concepts of Coding

## 1. What is Coding?
Coding is the process of writing instructions that a computer can follow to perform specific tasks. It involves using a programming language to create software, applications, websites, and more.

## 2. Why Learn Coding?
- **Problem-solving**: Coding allows you to automate tasks, solve complex problems, and create solutions that help in real-world situations.
- **Job opportunities**: Coding skills are in high demand in many fields, including web development, software engineering, and data science.
- **Creativity**: Coding gives you the power to bring your ideas to life by creating interactive applications, games, or websites.

---

## Basic Concepts of Coding

### 3. **Variables and Constants**
- **Variables**: A variable is a container that stores data that can change during the execution of a program.
  - Example in Python: 
    ```python
    age = 20
    ```
  - Here, `age` is a variable that stores the number `20`.

- **Constants**: A constant is a value that cannot be changed once it is assigned.
  - Example:
    ```python
    PI = 3.14159
    ```
  - `PI` is a constant and its value cannot change during the program.

---

### 4. **Data Types**
Different types of data are used in programming:
- **Integer (int)**: Whole numbers (positive, negative, or zero).
  - Example: `5`, `-3`
  
- **Float**: Decimal numbers.
  - Example: `3.14`, `-7.5`

- **Character (char)**: A single character (typically enclosed in quotes).
  - Example: `'A'`, `'z'`

- **String (str)**: A sequence of characters.
  - Example: `"Hello, World!"`

- **Boolean (bool)**: A type that can be either `True` or `False`.
  - Example: `True`, `False`

---

### 5. **Operators**
Operators are used to perform operations on variables and values.
- **Arithmetic Operators**: Used to perform mathematical operations.
  - Examples: 
    - `+` (addition)
    - `-` (subtraction)
    - `*` (multiplication)
    - `/` (division)

- **Comparison Operators**: Used to compare two values.
  - Examples:
    - `==` (equal to)
    - `!=` (not equal to)
    - `>` (greater than)
    - `<` (less than)

- **Logical Operators**: Used to combine multiple conditions.
  - Examples:
    - `and` (both conditions must be true)
    - `or` (either condition must be true)
    - `not` (negates a condition)

---

### 6. **Conditional Statements**
Conditional statements allow you to perform different actions based on certain conditions.

- **If Statement**: Executes a block of code if a condition is true.
  - Example:
    ```python
    if age >= 18:
        print("You are an adult.")
    ```

- **Else Statement**: Executes a block of code if the condition is false.
  - Example:
    ```python
    else:
        print("You are not an adult.")
    ```

- **Elif Statement**: Checks another condition if the previous ones were false.
  - Example:
    ```python
    if age > 18:
        print("You are an adult.")
    elif age == 18:
        print("You are just an adult.")
    else:
        print("You are a minor.")
    ```

---

### 7. **Loops**
Loops are used to repeat a block of code multiple times.

- **While Loop**: Runs as long as a condition is true.
  - Example:
    ```python
    while age < 18:
        print("You are still a minor.")
        age += 1
    ```

- **For Loop**: Iterates over a sequence (like a list or range) a specific number of times.
  - Example:
    ```python
    for i in range(5):
        print("Iteration:", i)
    ```

---

### 8. **Functions**
Functions allow you to group reusable code into a block that can be called multiple times.

- **Defining a Function**: 
  - Example:
    ```python
    def greet(name):
        print(f"Hello, {name}!")
    ```

- **Calling a Function**:
  - Example:
    ```python
    greet("Alice")
    ```

---

### 9. **Comments**
Comments are notes in the code that are ignored by the computer. They help explain the code to other people (or to yourself in the future).

- **Single-line comment**:
  ```python
  # This is a comment
