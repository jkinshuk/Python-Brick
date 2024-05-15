# ARRAYS AND TUPPLES IN PYTHON




```Python
# Initial values
a = 5
b = 10

print("Before swapping:")
print("a =", a)
print("b =", b)

# Swapping using XOR
a = a ^ b
b = a ^ b
a = a ^ b

print("\nAfter swapping:")
print("a =", a)
print("b =", b)




```


```Python 

a = 5
b = 10

a = a + b
b = a - b
a = a - b

print("a =", a)
print("b =", b)




```


Linear search in python 

```Python
arr = [5, 8, 10, 15, 20]
target = 15

found = False
for i in range(len(arr)):
    if arr[i] == target:
        print(f"Element {target} found at index {i}.")
        found = True
        break

if not found:
    print("Element not found.")



```


# Program 1

```Python 

# Define the number of terms
n = 10

# Initialize the first two terms
a, b = 0, 1

# Print the first two terms
print(a, end=" ")
print(b, end=" ")

# Generate the rest of the series
for _ in range(2, n):
    c = a + b
    print(c, end=" ")
    a, b = b, c



```

# Python-Brick 
certainly! Here are some basic Python terminologies for beginners:

1. **Python**: A high-level, interpreted programming language known for its simplicity and readability.
2. **Interpreter**: A program that executes Python code line by line, translating it into machine-readable instructions.
3. **Script**: A Python program or file containing a sequence of Python commands and statements.
4. **Syntax**: The rules that define the structure and grammar of the Python language.
5. **Indentation**: The use of whitespace (typically four spaces) to define code blocks in Python, instead of curly braces or keywords like "end" or "begin".


# EXAMPLE -1 
```Python
# This is a comment
x = 5  # Assigning a value to a variable
y = 10

if x < y:
    print("x is less than y")  # Indentation defines code blocks

# Function definition
def greet(name):
    print("Hello, " + name + "!")

# Function call
greet("Alice")

# Looping through a range of numbers
for i in range(3):
    print("Number:", i)

# Importing a module
import math
print("Square root of 16 is", math.sqrt(16))
```
1. **Statement**: A complete instruction that the Python interpreter can execute. For example, variable assignments, function calls, and control flow statements are all statements.
```Python
x = 10
```
1. **Expression**: A combination of values, variables, and operators that evaluates to a single value. For example, `2 + 3`  is an expression that evaluates to `5` .
```Python
result = 3 + 4 * 2
```
1. **Variable**: A named location in memory used to store data. Variables are created using assignment statements.
```Python
x = 10 // x is variable
```
1. **Data Type**: A classification of data that determines the operations that can be performed on it. Common data types in Python include integers, floats, strings, lists, tuples, dictionaries, and sets.


# EXAMPLE - 2
```Python
# Integer
x = 10

# Float
y = 3.14

# String
name = "John Doe"

# List
numbers = [1, 2, 3, 4, 5]

# Tuple
coordinates = (3.5, -2.7)

# Dictionary
person = {"name": "Alice", "age": 30, "city": "New York"}

# Set
unique_numbers = {1, 2, 3, 4, 5}

# Boolean
is_active = True

# None Type
empty_value = None

# Printing initialized variables
print("Integer:", x)
print("Float:", y)
print("String:", name)
print("List:", numbers)
print("Tuple:", coordinates)
print("Dictionary:", person)
print("Set:", unique_numbers)
print("Boolean:", is_active)
print("None⬤
```
1. **Boolean**: A data type that represents truth values. It can have one of two values: `True`  or `False` .
```Pyhton
var = true
val = false
```
1. Certainly! Let's go through different types of conversions and operators in Python with explanations and examples: Type Conversions:
**Integer to String (**`**int**` ** to **`**str**` **):**

```
num_int = 123
num_str = str(num_int)
print("Converted String:", num_str)
```
This converts an integer `**123**` to a string `**"123"**`.

**String to Integer (**`**str**` ** to **`**int**` **):**



```
num_str = "456"
num_int = int(num_str)
print("Converted Integer:", num_int)
```
This converts a string `**"456"**` to an integer `**456**`.

1. **Float to Integer (**`**float**` ** to **`**int**` **):**
```
num_float = 3.14
num_int = int(num_float)
print("Converted Integer:", num_int)
```
This converts a float `**3.14**` to an integer `**3**`.

1. **Integer to Float (**`**int**` ** to **`**float**` **):**
```
num_int = 100
num_float = float(num_int)
print("Converted Float:", num_float)
```
1. **String to Float (**`**str**` ** to **`**float**` **):**
```python
pythonCopy codenum_str = "3.14"
num_float = float(num_str)
print("Converted Float:", num_float)
```
This converts a string `**"3.14"**` to a float `**3.14**`.

# operators in python : 
1. **Arithmetic Operators:**
```python
a = 10
b = 5
print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)
print("Modulus:", a % b)
print("Exponentiation:", a ** b)
print("Floor Division:", a // b)
```
These operators perform basic arithmetic operations like addition, subtraction, multiplication, division, modulus, exponentiation, and floor division.

1. **Comparison Operators:**
```python
x = 10
y = 5
print("Equal to:", x == y)
print("Not equal to:", x != y)
print("Greater than:", x > y)
print("Less than:", x < y)
print("Greater than or equal to:", x >= y)
print("Less than or equal to:", x <= y)
```
These operators compare two values and return a boolean result indicating the comparison.

1. **Logical Operators:**
```python
p = True
q = False
print("Logical AND:", p and q)
print("Logical OR:", p or q)
print("Logical NOT:", not p)
```
These operators perform logical operations such as AND, OR, and NOT on boolean values.

1. **Assignment Operators:**
```python
x = 10
x += 5  # Equivalent to x = x + 5
print("x after addition:", x)
x -= 3  # Equivalent to x = x - 3
print("x after subtraction:", x)
x *= 2  # Equivalent to x = x * 2
print("x after multiplication:", x)
x /= 4  # Equivalent to x = x / 4
print("x after division:", x)
```
These operators are used to assign values to variables along with performing an operation.

1. **Identity Operators:**
```python
a = 5
b = 5
print("Is a same as b:", a is b)
print("Is a different from b:", a is not b)
```
These operators compare the memory locations of two objects.

1. **Membership Operators:**
```python
list = [1, 2, 3, 4, 5]
print("Is 3 in list?", 3 in list)
print("Is 6 not in list?", 6 not in list)
```
These operators check for membership in a sequence (such as lists, tuples, or strings).



1. **Conditional Statement**: A control flow statement that executes different blocks of code depending on whether a specified condition evaluates to `True`  or `False` . Examples include `if` , `elif` , and `else`  statements.
# EXAMPLE - 3
```Python
x = 10

if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")
```
1. **Loop**: A control flow statement that repeatedly executes a block of code until a specified condition is met. Examples include `for`  and `while`  loops.


# EXAMPLE - 4
```Python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```
# EXAMPLE -5 FOR LOOP 
```
num = 5
for i in range(1, 11):
    print(num, "x", i, "=", num*i)
```
# EXAMPLE -6 FOR LOOP
```
fruits = ["apple", "banana", "cherry", "date"]
for index, fruit in enumerate(fruits):
    print("Index:", index, "Fruit:", fruit)
```


