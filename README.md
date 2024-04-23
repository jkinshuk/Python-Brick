# Python-Brick

kiCertainly! Here are some basic Python terminologies for beginners:

1. **Python**: A high-level, interpreted programming language known for its simplicity and readability.

2. **Interpreter**: A program that executes Python code line by line, translating it into machine-readable instructions.

3. **Script**: A Python program or file containing a sequence of Python commands and statements.

4. **Syntax**: The rules that define the structure and grammar of the Python language.

5. **Indentation**: The use of whitespace (typically four spaces) to define code blocks in Python, instead of curly braces or keywords like "end" or "begin".

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

6. **Statement**: A complete instruction that the Python interpreter can execute. For example, variable assignments, function calls, and control flow statements are all statements.

```Python

x = 10


```

7. **Expression**: A combination of values, variables, and operators that evaluates to a single value. For example, `2 + 3` is an expression that evaluates to `5`.

```Python
result = 3 + 4 * 2


```

8. **Variable**: A named location in memory used to store data. Variables are created using assignment statements.

```Python
x = 10 // x is variable 


```

9. **Data Type**: A classification of data that determines the operations that can be performed on it. Common data types in Python include integers, floats, strings, lists, tuples, dictionaries, and sets.

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

# NoneType
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



10. **Boolean**: A data type that represents truth values. It can have one of two values: `True` or `False`.

```Pyhton
var = true
val = false 

```

11. **Conditional Statement**: A control flow statement that executes different blocks of code depending on whether a specified condition evaluates to `True` or `False`. Examples include `if`, `elif`, and `else` statements.

```Python

x = 10

if x > 5:
    print("x is greater than 5")
else:
    print("x is not greater than 5")



```

12. **Loop**: A control flow statement that repeatedly executes a block of code until a specified condition is met. Examples include `for` and `while` loops.


```Python


fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)


```

1. **Mutability**:
   - Lists are mutable, meaning their elements can be changed after the list is created.
   - Tuples are immutable, meaning their elements cannot be changed after the tuple is created.

2. **Syntax**:
   - Lists are defined using square brackets `[ ]`.
   - Tuples are defined using parentheses `( )`.

3. **Example of a List**:
   ```python
   my_list = [1, 2, 3, 4, 5]
   ```

4. **Example of a Tuple**:
   ```python
   my_tuple = (1, 2, 3, 4, 5)
   ```

5. **Appending Elements**:
   - Lists allow appending new elements using the `append()` method.
   - Tuples do not allow appending because they are immutable.

6. **Example of Appending to a List**:
   ```python
   my_list.append(6)
   ```

7. **Accessing Elements**:
   - Both lists and tuples allow accessing elements using indexing.
   - Lists and tuples use zero-based indexing.

8. **Example of Accessing Elements**:
   ```python
   print(my_list[0])  # Accessing the first element of the list
   print(my_tuple[0]) # Accessing the first element of the tuple
   ```

9. **Slicing**:
   - Both lists and tuples support slicing to extract sub-sequences.
   - Slicing returns a new list or tuple.

10. **Example of Slicing**:
    ```python
    sliced_list = my_list[1:3]  # Returns a new list [2, 3]
    sliced_tuple = my_tuple[1:3] # Returns a new tuple (2, 3)
    ```

These examples illustrate some of the key differences between lists and tuples in Python.
