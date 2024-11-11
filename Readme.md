### In-Class Assignment: Python Syntax Fixes and Coding Practice

**Instructions**: Complete each part as described below. For parts 1–6, you’ll be given code files with minor errors; your task is to fix the code to produce the correct output. For parts 7–10, you’ll write the code yourself according to the instructions.

---

### Part 1 - Fixing Variable Assignment

1. **File Name**: `fix_variable.py`
2. **Problem**: The file contains code that tries to assign a value to a variable but is missing an equal sign.
3. **Task**: Fix the variable assignment by adding the correct syntax so that the code prints `"The variable value is 10"`.
   
   **Pre-existing Code**:
   ```python
   x 10
   print("The variable value is", x)
   ```

---

### Part 2 - Fixing Print Statement

1. **File Name**: `fix_print.py`
2. **Problem**: The file has a print statement with unnecessary parentheses, causing a syntax error.
3. **Task**: Remove the extra parentheses so that the code prints `"Hello, Python!"`.
   
   **Pre-existing Code**:
   ```python
   print(("Hello, Python!"))
   ```

---

### Part 3 - Fixing Indentation

1. **File Name**: `fix_indentation.py`
2. **Problem**: The file has an `if` statement without correct indentation, causing an error.
3. **Task**: Correct the indentation so that the `print` statement is part of the `if` block and prints `"Python is fun!"` if `is_fun` is `True`.
   
   **Pre-existing Code**:
   ```python
   is_fun = True
   if is_fun:
   print("Python is fun!")
   ```

---

### Part 4 - Fixing String Concatenation

1. **File Name**: `fix_concatenation.py`
2. **Problem**: The file tries to concatenate a string and a number, causing an error.
3. **Task**: Use type conversion to fix the code so that it correctly prints `"The number is 5"`.
   
   **Pre-existing Code**:
   ```python
   number = 5
   print("The number is " + number)
   ```

---

### Part 5 - Fixing Comparison Operator

1. **File Name**: `fix_comparison.py`
2. **Problem**: The code is attempting to compare two numbers but uses a single equal sign instead of the comparison operator.
3. **Task**: Change the single equal sign to a double equal sign to correctly compare `x` and `y`. If they’re equal, it should print `"x and y are equal"`.
   
   **Pre-existing Code**:
   ```python
   x = 10
   y = 10
   if x = y:
       print("x and y are equal")
   ```

---

### Part 6 - Fixing Missing Colon

1. **File Name**: `fix_colon.py`
2. **Problem**: The `if` statement is missing a colon, causing a syntax error.
3. **Task**: Add the missing colon so that the code checks the condition and prints `"Condition met"` if `a` is greater than `b`.
   
   **Pre-existing Code**:
   ```python
   a = 15
   b = 10
   if a > b
       print("Condition met")
   ```

---

### Parts 7–10: Writing Code

#### Part 7 - Greeting Program

1. **File Name**: `greeting.py`
2. **Task**: Write a program that stores a name in a variable and then prints a greeting using that name.
   
   **Example Code**:
   ```python
   name = "Alice"
   print("Hello, " + name + "!")
   ```

3. **Expected Output**:
   ```
   Hello, Alice!
   ```

---

#### Part 8 - Simple Calculator

1. **File Name**: `calculator.py`
2. **Task**: Write a program that:
   - Defines two numbers in variables, `num1` and `num2`.
   - Prints the result of adding, subtracting, multiplying, and dividing the two numbers.


3. **Expected Output**:
   ```
   Addition: 8
   Subtraction: 2
   Multiplication: 15
   Division: 1.6666666666666667
   ```

---

#### Part 9 - Even or Odd Checker

1. **File Name**: `even_odd_checker.py`
2. **Task**: Write a program that:
   - Stores a number in a variable.
   - Checks if the number is even or odd and prints `"The number is even"` or `"The number is odd"` accordingly.



3. **Expected Output**:
   ```
   The number is odd
   ```

---

#### Part 10 - Temperature Converter

1. **File Name**: `temperature_converter.py`
2. **Task**: Write a program that:
   - Stores a temperature in Celsius in a variable.
   - Converts the temperature to Fahrenheit using the formula `(C * 9/5) + 32`.
   - Prints the converted temperature.


3. **Expected Output**:
   ```
   Temperature in Fahrenheit: 77.0
   ```
