# Intro_to_python
notes and activities

# Day1 Notes

Python is a high-level, interpreted programming language known for its simplicity and readability. 

## PYTHON IN THE JOB MARKET

Versatility: Python is known for its versatility and can be used in various domains, including web development, data science, machine learning, artificial intelligence, automation, scientific computing, and more. This versatility makes Python professionals in demand in a wide range of industries.

Data Science and Machine Learning: Python is the preferred language for many data scientists and machine learning engineers. Libraries and frameworks like NumPy, Pandas, Matplotlib, and TensorFlow/PyTorch have made it a go-to language for data analysis and machine learning, resulting in a strong demand for Python experts in these fields.

Web Development: Python's frameworks, such as Django and Flask, are popular for web development. Many companies use Python to build web applications and websites, leading to a demand for Python web developers.

Automation and Scripting: Python is frequently used for scripting and automation tasks due to its simplicity and readability. This makes it valuable in IT operations and DevOps roles.

Data Engineering: Python is commonly used in data engineering tasks, where professionals work on data processing, ETL (Extract, Transform, Load) processes, and building data pipelines.

Job Titles: Job titles associated with Python skills include Python Developer, Data Scientist, Machine Learning Engineer, Web Developer, Data Engineer, DevOps Engineer, and more.

Growing Demand: The demand for Python developers and professionals with Python-related skills is growing rapidly. Python's popularity in emerging technologies like artificial intelligence and data science is a significant driver of this demand.

Competitive Salaries: Python professionals often command competitive salaries due to their specialized skills and the demand for their expertise. The exact salary can vary based on the role, experience, and location.

Remote Work: Python developers and professionals often have the flexibility to work remotely, making it a desirable language for those looking for remote or freelance opportunities.

Learning Resources: Python's ease of learning and the abundance of online resources, tutorials, and courses make it accessible to newcomers, contributing to its popularity in the job market.

## HISTORY OF PYTHON

Python was conceived in the late 1980s and Guido van Rossum started implementing it at CWI in the Netherlands in December 1989. 

Python strikes a good balance between fast compilations and readability, and it is easier to write applications.

Python is implemented in C and relies on the extensive, well understood, portable C libraries.

## COMMENTS IN PYTHON
In programming comments are texts that are ignored by the compilers and they explain certain parts of the code. We add comments for the code to be easily understood and readable.

A comment may appear at the start of a line or following whitespace or code, but not within a string literal. A hash character within a string literal is just a hash character.

In python they are led by the '#' for single line comments  and  ''' for multiple comments.

## ACTIVITY 3
1. print("""This is how the backslash character is displayed

in Python

“\\”""")

2. print("****  *   * ********* *   *  ****  *     *\n*  *   * *      *     *   * *    * * *   * \n****    *       *     ***** *    * *  *  *\n*       *       *     *   * *    * *   * * \n*       *       *     *   *  ****  *     *" )

## Day2
Variables in Python are used to store and manage data. They act as containers that hold values, making it easier to work with data in your programs. Here are some important points to understand about variables in Python:

## Variable Names:

Variable names are case-sensitive, which means "myVar" and "myvar" are treated as different variables.
Variable names must start with a letter (a-z, A-Z) or an underscore (_).
They can contain letters, numbers, and underscores, but not spaces or special characters.
It's a good practice to use descriptive names for variables to make your code more readable.
## Variable Assignment:

You assign a value to a variable using the = operator. For example: x = 10.
The variable name (left-hand side) stores the value (right-hand side).
## Data Types:

Python is dynamically typed, meaning you don't need to declare the data type of a variable explicitly. Python will figure out the type on its own.
Common data types in Python include integers, floats, strings, booleans, lists, and dictionaries.
## Variable Types:

#### Variables can hold various types of data. For example:
name = "Alice"  # String
age = 30       # Integer
height = 5.8   # Float
is_student = True  # Boolean

## Reassignment:

### You can change the value of a variable by reassigning it:
x = 10
x = x + 5  # x now holds the value 16

## Multiple Assignments:
You can assign multiple variables in a single line:

a, b, c = 1, 2, 3

## Naming Conventions:

It's common to use lowercase letters and underscores for variable names (e.g., my_variable).
For constants, it's a convention to use uppercase with underscores (e.g., MAX_VALUE).
## Reserved Keywords:

Python has reserved keywords (e.g., if, else, while, for) that cannot be used as variable names.
## Printing Variables:

You can print the value of a variable using the print() function:

x = 42
print(x)  # This will print 42

## Scope:

Variables have a scope, which determines where they can be accessed. A variable defined inside a function is only accessible within that function (local scope). Variables defined outside functions have a global scope and can be accessed from anywhere in the code.
## Type Conversion:

You can convert variables from one data type to another using functions like int(), float(), str(), etc.
## Delete Variables:

You can delete a variable using the del statement. For example: del x.
## Comments:

You can add comments to your code using the # symbol to explain the purpose of variables.
Here's an example of using variables in Python:
# Variable assignment
name = "Alice"
age = 30

# Printing variables
print("Name:", name)
print("Age:", age)

# Reassigning variables
age = age + 5
print("Age after 5 years:", age)

# day3
Data types in Python are essential for representing and manipulating different kinds of data. Understanding data types is fundamental for writing effective and bug-free code. Python provides several built-in data types, and you can also create custom data types using classes. Here are some of the most commonly used data types in Python:

1. **Numeric Types:**
   - **int**: Represents integers, e.g., 1, -5, 100.
   - **float**: Represents floating-point numbers, e.g., 3.14, -0.5, 2.0.

2. **Boolean Type:**
   - **bool**: Represents Boolean values, `True` or `False`, which are used for logical operations.

3. **String Type:**
   - **str**: Represents sequences of characters, e.g., "Hello, World!".

4. **List:**
   - **list**: An ordered collection of values that can be of any data type. Lists are mutable, and you can add, remove, or change elements.

5. **Tuple:**
   - **tuple**: Similar to a list but immutable, meaning you cannot change its elements once defined.

6. **Dictionary:**
   - **dict**: Represents a collection of key-value pairs, where each key is unique and associated with a value.

7. **Set:**
   - **set**: An unordered collection of unique elements. Sets are commonly used for tasks that involve testing membership and eliminating duplicates.

8. **None Type:**
   - **NoneType**: Represents the absence of a value. It is often used to indicate that a variable or function returns nothing.

9. **Custom Classes:**
   - You can define your own data types by creating classes. This allows you to encapsulate data and methods into a single unit, facilitating more complex data structures.

10. **Type Casting:**
    - You can convert one data type to another using type casting functions like `int()`, `float()`, `str()`, etc.

11. **Special Data Types:**
    - Python also provides some special data types like `complex` for complex numbers and `bytes` for representing sequences of bytes.

12. **Collection Data Types (Containers):**
    - Lists, tuples, dictionaries, and sets are often referred to as collection data types or containers because they hold multiple values. You can iterate through them and perform various operations.

It's important to understand the characteristics and behaviors of these data types, as they dictate how you can use and manipulate data in your Python programs. For example, some data types are mutable (can be changed), while others are immutable (cannot be changed), and this can have significant implications for how your code behaves. Additionally, different data types are suited for different types of tasks, so choosing the right data type is crucial for writing efficient and maintainable code.

### examples
Certainly, let's explore these data types with examples:

1. **Numeric Types:**

   - `int` and `float`:

     ```python
     num_int = 42
     num_float = 3.14
     ```

2. **Boolean Type:**

   - `bool`:

     ```python
     is_true = True
     is_false = False
     ```

3. **String Type:**

   - `str`:

     ```python
     greeting = "Hello, World!"
     ```

4. **List:**

   - `list`:

     ```python
     fruits = ['apple', 'banana', 'cherry']
     ```

   - Lists are mutable, so you can add or change elements:

     ```python
     fruits.append('orange')
     fruits[1] = 'kiwi'
     ```

5. **Tuple:**

   - `tuple`:

     ```python
     coordinates = (3, 4)
     ```

   - Tuples are immutable; you can't change their elements.

6. **Dictionary:**

   - `dict`:

     ```python
     person = {
         'name': 'John',
         'age': 30,
         'city': 'New York'
     }
     ```

   - Access values using keys:

     ```python
     name = person['name']
     ```

7. **Set:**

   - `set`:

     ```python
     unique_numbers = {1, 2, 3, 2, 4, 5}
     ```

   - Sets automatically remove duplicates.

8. **None Type:**

   - `NoneType`:

     ```python
     result = None
     ```

   - Often used when a function doesn't return anything explicitly.

9. **Custom Classes:**

   - You can create your own data types using classes. For example:

     ```python
     class Person:
         def __init__(self, name, age):
             self.name = name
             self.age = age

     john = Person("John", 30)
     ```

10. **Type Casting:**

    - Converting between data types using casting functions:

    ```python
    num_str = "42"
    num_int = int(num_str)  # Convert string to int
    ```

11. **Special Data Types:**

    - `complex` and `bytes`:

    ```python
    complex_num = 2 + 3j
    byte_data = b'Hello'
    ```

12. **Collection Data Types (Containers):**

    - Lists, tuples, dictionaries, and sets are examples of collection data types. Here's an example using a dictionary:

    ```python
    student = {
        'name': 'Alice',
        'grades': [85, 90, 78]
    }
    ```

 Operators in Python are special symbols or keywords that are used to perform operations on variables and values. Python provides a wide range of operators for various tasks, including arithmetic, comparison, logical, assignment, and more. Here's an introduction to some of the most commonly used operators in Python:

1. **Arithmetic Operators:**

   Arithmetic operators are used to perform mathematical operations.

   - `+` (Addition): Adds two operands.
   - `-` (Subtraction): Subtracts the right operand from the left operand.
   - `*` (Multiplication): Multiplies two operands.
   - `/` (Division): Divides the left operand by the right operand.
   - `%` (Modulus): Returns the remainder of the division.
   - `**` (Exponentiation): Raises the left operand to the power of the right operand.
   - `//` (Floor Division): Returns the integer part of the division result.

   Example:

   ```python
   a = 10
   b = 3
   addition = a + b
   division = a / b
   modulus = a % b
   ```

2. **Comparison Operators:**

   Comparison operators are used to compare two values and return a Boolean result.

   - `==` (Equal to): Checks if two values are equal.
   - `!=` (Not equal to): Checks if two values are not equal.
   - `<` (Less than): Checks if the left operand is less than the right operand.
   - `>` (Greater than): Checks if the left operand is greater than the right operand.
   - `<=` (Less than or equal to): Checks if the left operand is less than or equal to the right operand.
   - `>=` (Greater than or equal to): Checks if the left operand is greater than or equal to the right operand.

   Example:

   ```python
   x = 5
   y = 10
   is_equal = x == y
   is_greater = x > y
   ```

3. **Logical Operators:**

   Logical operators are used to combine and manipulate Boolean values.

   - `and`: Returns `True` if both operands are `True`.
   - `or`: Returns `True` if at least one operand is `True`.
   - `not`: Returns the opposite of the operand's Boolean value.

   Example:

   ```python
   is_sunny = True
   is_warm = False
   is_good_weather = is_sunny and is_warm
   ```

4. **Assignment Operators:**

   Assignment operators are used to assign values to variables.

   - `=` (Assignment): Assigns the value on the right to the variable on the left.
   - `+=`, `-=`, `*=`, `/=`, `%=`, `**=`, `//=`: Perform the respective operation and assign the result to the variable on the left.

   Example:

   ```python
   x = 10
   x += 5  # Equivalent to x = x + 5
   ```

5. **Membership Operators:**

   Membership operators are used to test if a value is present in a sequence (e.g., a list, tuple, or string).

   - `in`: Returns `True` if the value is found in the sequence.
   - `not in`: Returns `True` if the value is not found in the sequence.

   Example:

   ```python
   fruits = ['apple', 'banana', 'cherry']
   is_apple_in_fruits = 'apple' in fruits
   ```

6. **Identity Operators:**

   Identity operators are used to compare the memory location of two objects.

   - `is`: Returns `True` if both operands refer to the same object.
   - `is not`: Returns `True` if both operands do not refer to the same object.

   Example:

   ```python
   a = [1, 2, 3]
   b = a
   are_same_object = a is b
   ```
# day4 operators in python
 Operators in Python are special symbols or keywords that are used to perform operations on variables and values. Python provides a wide range of operators for various tasks, including arithmetic, comparison, logical, assignment, and more. Here's an introduction to some of the most commonly used operators in Python:

1. **Arithmetic Operators:**

   Arithmetic operators are used to perform mathematical operations.

   - `+` (Addition): Adds two operands.
   - `-` (Subtraction): Subtracts the right operand from the left operand.
   - `*` (Multiplication): Multiplies two operands.
   - `/` (Division): Divides the left operand by the right operand.
   - `%` (Modulus): Returns the remainder of the division.
   - `**` (Exponentiation): Raises the left operand to the power of the right operand.
   - `//` (Floor Division): Returns the integer part of the division result.

   Example:

   ```python
   a = 10
   b = 3
   addition = a + b
   division = a / b
   modulus = a % b
   ```

2. **Comparison Operators:**

   Comparison operators are used to compare two values and return a Boolean result.

   - `==` (Equal to): Checks if two values are equal.
   - `!=` (Not equal to): Checks if two values are not equal.
   - `<` (Less than): Checks if the left operand is less than the right operand.
   - `>` (Greater than): Checks if the left operand is greater than the right operand.
   - `<=` (Less than or equal to): Checks if the left operand is less than or equal to the right operand.
   - `>=` (Greater than or equal to): Checks if the left operand is greater than or equal to the right operand.

   Example:

   ```python
   x = 5
   y = 10
   is_equal = x == y
   is_greater = x > y
   ```

3. **Logical Operators:**

   Logical operators are used to combine and manipulate Boolean values.

   - `and`: Returns `True` if both operands are `True`.
   - `or`: Returns `True` if at least one operand is `True`.
   - `not`: Returns the opposite of the operand's Boolean value.

   Example:

   ```python
   is_sunny = True
   is_warm = False
   is_good_weather = is_sunny and is_warm
   ```

4. **Assignment Operators:**

   Assignment operators are used to assign values to variables.

   - `=` (Assignment): Assigns the value on the right to the variable on the left.
   - `+=`, `-=`, `*=`, `/=`, `%=`, `**=`, `//=`: Perform the respective operation and assign the result to the variable on the left.

   Example:

   ```python
   x = 10
   x += 5  # Equivalent to x = x + 5
   ```

5. **Membership Operators:**

   Membership operators are used to test if a value is present in a sequence (e.g., a list, tuple, or string).

   - `in`: Returns `True` if the value is found in the sequence.
   - `not in`: Returns `True` if the value is not found in the sequence.

   Example:

   ```python
   fruits = ['apple', 'banana', 'cherry']
   is_apple_in_fruits = 'apple' in fruits
   ```

6. **Identity Operators:**

   Identity operators are used to compare the memory location of two objects.

   - `is`: Returns `True` if both operands refer to the same object.
   - `is not`: Returns `True` if both operands do not refer to the same object.

   Example:

   ```python
   a = [1, 2, 3]
   b = a
   are_same_object = a is b
   ```

 Operators in Python are special symbols or keywords used to perform operations on variables and values. Python provides a wide range of operators for various purposes, such as arithmetic calculations, logical comparisons, assignment, and more. Operators can be classified into several categories:

1. **Arithmetic Operators:**
   - These operators are used for basic mathematical calculations.

   ```python
   +   # Addition
   -   # Subtraction
   *   # Multiplication
   /   # Division
   %   # Modulus (remainder)
   **  # Exponentiation
   //  # Floor Division (returns the integer part of the division)
   ```

   Example:

   ```python
   a = 10
   b = 3
   addition = a + b  # 13
   division = a / b  # 3.3333...
   modulus = a % b   # 1
   ```

2. **Comparison Operators:**
   - These operators are used to compare values and return Boolean results.

   ```python
   ==  # Equal to
   !=  # Not equal to
   <   # Less than
   >   # Greater than
   <=  # Less than or equal to
   >=  # Greater than or equal to
   ```

   Example:

   ```python
   x = 5
   y = 7
   is_equal = x == y     # False
   is_not_equal = x != y # True
   ```

3. **Logical Operators:**
   - Logical operators are used to combine or negate Boolean values.

   ```python
   and  # Logical AND
   or   # Logical OR
   not  # Logical NOT
   ```

   Example:

   ```python
   is_true = True
   is_false = False
   result = is_true and is_false  # False
   ```

4. **Assignment Operators:**
   - These operators are used to assign values to variables.

   ```python
   =    # Assign
   +=   # Add and assign
   -=   # Subtract and assign
   *=   # Multiply and assign
   /=   # Divide and assign
   %=   # Modulus and assign
   **=  # Exponentiate and assign
   //=  # Floor divide and assign
   ```

   Example:

   ```python
   x = 10
   x += 5  # x is now 15
   ```

5. **Bitwise Operators:**
   - These operators are used for manipulating individual bits in integers.

   ```python
   &   # Bitwise AND
   |   # Bitwise OR
   ^   # Bitwise XOR
   ~   # Bitwise NOT
   <<  # Left shift
   >>  # Right shift
   ```

   Example:

   ```python
   a = 5   # 101 (in binary)
   b = 3   # 011 (in binary)
   result = a & b  # Bitwise AND: 001 (in binary), which is 1 in decimal
   ```

6. **Membership Operators:**
   - These operators are used to test if a value is a member of a sequence (e.g., a string, list, or tuple).

   ```python
   in    # True if a value is found in the sequence
   not in  # True if a value is not found in the sequence
   ```

   Example:

   ```python
   fruits = ['apple', 'banana', 'cherry']
   is_apple_in_fruits = 'apple' in fruits  # True
   ```

# week2
## day1
Control flow in Python is a fundamental concept that allows you to control the order in which statements and code blocks are executed. Python provides several control flow constructs 
 

 
## Control Flow in Python

## 1. Introduction
- Control flow refers to the order in which a program's instructions are executed.
- Python provides various control flow structures to determine how code is executed.

**2. Sequential Execution**
- By default, Python executes code sequentially, from top to bottom.
- Each statement is executed in the order it appears in the script.

## 3. Conditional Statements
- Conditional statements are used for decision-making in Python.
- Key elements:
  - `if`: Executes code block if a condition is true.
  - `elif`: Additional condition(s) to check.
  - `else`: Executes code block if no conditions are met.

## 4. Example of Conditional Statements
- Consider a temperature converter program:
```python
temperature = 25
if temperature > 30:
    print("It's hot outside.")
elif temperature >= 20:
    print("It's a pleasant day.")
else:
    print("It's cold outside.")
```

## 5. Loops - `for` and `while`
- Loops allow repetitive execution of code.
- `for` loop: Iterates over sequences (e.g., lists, strings).
- `while` loop: Repeats as long as a condition is true.

## 6. Example of Loops
- `for` loop to print elements of a list:
```python
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```
- `while` loop to count from 1 to 5:
```python
count = 1
while count <= 5:
    print(count)
    count += 1
```

## 7. Loop Control Statements
- `break`: Exits the loop prematurely when a condition is met.
- `continue`: Skips the current iteration and proceeds to the next.

## 8. Example of Loop Control Statements
- Using `break` to exit a loop early:
```python
numbers = [1, 2, 3, 4, 5]
for num in numbers:
    if num == 3:
        break
    print(num)
```
- Using `continue` to skip specific values:
```python
numbers = [1, 2, 3, 4, 5]
for num in numbers:
    if num == 3:
        continue
    print(num)
```

## 9. Exception Handling
- Exception handling allows graceful error management.
- `try`: Encloses code that might raise an exception.
- `except`: Defines what to do if an exception occurs.
- `else`: Optional block for code to execute if no exceptions are raised.
- `finally`: Optional block for cleanup, always executed.


 
# Day 2

##  Functions
In Python, function is a group of related statements that perform a specific task.
Functions help break our program into smaller and modular chunks. As our program grows larger and larger, functions make it more organized and manageable.
Furthermore, it avoids repetition and makes code reusable.

## Sintax of a function
 def function_name(parameters):
"""docstring"""
statement(s)

### Above shown is a function definition which consists of following components.
Keyword def which marks the start of function header.
A function name to uniquely identify it. Function name can be any unique identifier.
Parameters (arguments) through which we pass values to a function. They areoptional.
A colon (:) to mark the end of function header.
Optional documentation string (docstring) to describe what the function does.
One or more valid python statements that make up the function body. Statements must have same indentation level.
An optional return statement to return a value from the function.

## Example of a function

def greet(name):
"""This function greets the person passed in as
parameter"""
print("Hello, " + name + ". Good morning!")
Here, a function of name greet() is defined. It has one
argument : name
O/P :
If we execute this code with the name as 5stars, the
output is :
Hello 5Stars. Good Morning!

## How to call a function

Once we have defined a function, we can call it from
◦ another function,
◦ program or
◦ Python prompt.
 To call a function we simply type the function name
with appropriate parameters. eg: To call the function
greet with the name 5stars, we write the following at
the Python prompt
 >>> greet(„5stars') 
## DocString
The first string after the function header is called the docstring
and is short for documentation string.
- It is used to explain in brief, what a function does.
- Although optional, documentation is a good programming practice.
- In the example of the function given in previous slide, we have a docstring immediately below the function header.
- We generally use triple quotes so that docstring can extend up to multiple lines.
- This string is available to us as __doc__ attribute of the function.
- For example:
- Try running the following into the Python shell to see the output.
 >>> print(greet.__doc__)
- This function greets to the person passed into the name parameter

## The return statement
The return statement is used to exit a function and go back to the
place from where it was called.
- Syntax of return
- return [expression_list]
- This statement can contain expression which gets evaluated and
the value is returned.
- If there is no expression in the statement or the return statement
itself is not present inside a function, then the function will return
the None object.
- For example:
 >>> print(greet(“5stars")) or
 >>> greet(“5stars”)
- Hello, 5stars. Good morning!
- None : Here, None is the returned value.
- 
## Eample of a function using return statement
def absolute_value(num):
"""This function returns the absolute value of the
entered number"""
if num >= 0:
return num
else:
return –num
print(absolute_value(2))
# Output: 2
print(absolute_value(-4))
# Output: 4

## scope and lifetime of variables

Scope of a variable is the portion of a program where
the variable is recognized. Parameters and variables
defined inside a function is not visible from outside.
Hence, they have a local scope.
- Lifetime of a variable is the period throughout which
the variable exits in the memory. The lifetime of
variables inside a function is as long as the function
executes.
- They are destroyed once we return from the function.
Hence, a function does not remember the value of a
variable from its previous calls.

## example of a function to illustrate the use of scope and lifetime of a variable
- def my_func():         # function is defined
x = 100
print("Value inside function:",x)
x = 200
my_func()                 # function is called
print("Value outside function:",x)
O/P
Value inside function: 100
Value outside function: 200

## Types of functions
#### Build- In functions :
Functions that are built in Python are called Build- In functions .eg : split(), sort(),
append(), input(), print()

#### User-Defined Functions:
Functions defined by the users themselves are called User-Defined functions.
The functions greet() and my_func() explained in the
previous slides are examples of user defined functions

## Default arguments
Python allows function argumets to have default values.
 If the function is called without the argument, the argument gets its
default value.
 Further, arguments can be specified in any order by using named
arguments.
- Eg :
def CalArea(height =2, width = 5)
area = width*height
print “ Width = “, width, “ \tHeight = “, height, “ \tarea = “, area
CalArea()
CalArea(width = 5.6)
CalArea(height = 9)
CalArea(width = 7, height = 5)
CalArea(4.5, 3.5)
CalArea(5)

- The O/P of the previous program will be:
Width = 5 Height =2 area = 10
Width = 5.6 Height =2 area = 11.2
Width = 5 Height =9 area = 45
Width = 7 Height =5 area = 35
Width = 3.5 Height =4.5 area = 15.75
Width = 5 Height =5 area = 25
## Recursion
Recursion is the process of defining something in terms of
itself.
We know that in Python, a function can call other functions.
- It is even possible for the function to call itself.
- These type of construct are termed as recursive functions.
- Every recursive function should have a terminating or base
condition.
- Following is an example of recursive function to find the
factorial of an integer.
- Factorial of a number is the product of all the integers from
1 to that number. For example, the factorial of 6 (denoted as 6!) is 1*2*3*4*5*6 = 720.

## examples of recursive
# find the factorial of a number
def calc_factorial(x):
"""This is a recursive function to find the
factorial of an integer"""
if x == 1:
return 1
else:
return (x * calc_factorial(x-1))
num = 4
print("The factorial of", num, "is", calc_factorial(num))

## Advantages of Recursion
- Recursive functions make the code look clean and
elegant.
- A complex task can be broken down into simpler subproblems using recursion.
- Sequence generation is easier with recursion than using
some nested iteration.
# Global and local variables

## Global Variables
- In Python, a variable declared outside of the function or in global
scope is known as global variable. This means, global variable
can be accessed inside or outside of the function.
- Example 1: Create a Global Variable
x = "global“
def foo():
print("x inside :", x)
foo()
print("x outside:", x)
O/P
x inside : global
x outside: global \

## Local Variables
A variable declared inside the function's body or in the local scope is known as local
variable.
Accessing local variable outside the scope
def foo():
y = “local”
foo()
print(y)
O/P :
NameError: name 'y' is not defined
The output shows an error, because we are trying to access a local
variable y in a global scope whereas the local variable only works
inside foo() or local scope.

## Creating local variables
def foo():
y = "local"
print(y)
foo()
O/P :
loca

## using global and local variables in the same code
x = "global“
def foo():
global x
y = "local"
x = x * 2
print(x)
print(y)
foo()
O/P :
global global
local

##  global and local with the same name

x=5
def foo():
x = 10
print("local x:", x
)
foo()
print("global x:", x
)
O/P
local x: 10
global x: 5


## Global keyword

In Python, global keyword allows you to modify the variable outside of the current scope. It is used to
create a global variable and make changes to the variable in a local context.

## Rules of global Keyword

#### The basic rules for global keyword are:
• When we create a variable inside a function, it’s local by default.
• When we define a variable outside of a function, it’s global by default. You don’t have to use global keyword.
• We use global keyword to read and write a global variable inside a function.
• Use of global keyword outside a function has no effect

Use of global Keyword (With Example)
c = 1 # global variable
def add():
print(c)
add()
When we run above program, the output will be:

- Modifying Global Variable From Inside the Function
c = 1 # global variable
def add():
c = c + 2 # increment c by 2
print(c)
add()
When we run above program, the output shows an error:
UnboundLocalError: local variable 'c' referenced before assignment

Changing Global Variable From Inside a Function
using global
c = 0 # global variable
def add():
global c
c = c + 2 # increment by 2
print("Inside add():", c)
add()
print("In main:", c)
When we run above program, the output will be:
Inside add(): 2 In main: 2

# day 3
## modules 
· A file containing python code, typically functions, classes and variables that can be imported and used in other python script.

· Modules in Python are a fundamental concept that allows you to organize and reuse code.

· Modules help break down a program into smaller, manageable parts, promoting code reusability and organization.

· Definition: A module in Python is a file containing Python code, typically functions, classes, and variables, that can be imported and used in other Python scripts. Modules help break down a program into smaller, manageable parts, promoting code reusability and organization.

· Usage: You can use modules to structure your code logically and make it more maintainable. Python's standard library is a collection of modules that provide a wide range of functionality, from file manipulation to web development, mathematics, and more.

· Creating Modules: To create your own module, you can write a Python script and save it with a .py file extension. This file can contain functions, classes, and variables that you want to reuse in other parts of your program.

· Importing Modules: To use a module in your Python script, you import it using the import statement.

For example:

import mymodule # Import a module named "mymodule"

· Accessing Module Members: Once a module is imported, you can access its functions, classes, and variables using dot notation.

For example,

if mymodule has a function named my_function, you can call it like this:

mymodule.my_function()

· Aliasing: You can alias a module or its members to give them shorter or more convenient names when using them in your code.

For example:

import mymodule as mm # Alias the module from mymodule import my_function as mf # Alias a specific function

· Standard Library: Python comes with a vast standard library that includes modules for tasks like file I/O, math, networking, regular expressions, and more. These modules are readily available for use in your programs without the need for additional installation.

· Third-Party Modules: Python's ecosystem benefits from a rich collection of third-party modules and packages that extend its capabilities. You can install and use these modules using package managers like pip.

· Module Search Path: Python searches for modules in directories defined by the sys.path variable. By default, it includes the current directory and the standard library paths. You can add custom paths to this list to find your own modules.

· __name__ and Module Execution: Python modules have a built-in __name__ attribute. When a module is executed, its __name__ is set to '__main__'. This allows you to include code that should only run when the module is the main program.

· Packages: Packages are a way to organize related modules into directories and subdirectories. They include a special __init__.py file that marks a directory as a package. Packages help manage large codebases by providing a hierarchical structure.

· Modules are a fundamental part of Python's modular and extensible design, making it easier to develop and maintain Python applications and libraries. They promote code reuse, encapsulation, and separation of concerns, making your code more organized and maintainable.

Mechanism of Python Modules

· There's a thing called program directory where the python modules are located its called PYTHONPATH.

Listing of Modules

· The list of available modules in Python can be found out by executing the following command in the command prompt (interpreter shell).

When you want to see the lsit of available modules on python you execute

Help(“module”) on the console.

The mechanism of Python modules involves several steps that Python follows to locate, import, and use modules in your code. Here's a summary of the key aspects of how Python's module system works:

1. Module Structure: A module in Python is a file containing Python code, typically with the `.py` extension. Modules can include functions, classes, variables, and even executable code.

2. Module Search Path: Python uses a list of directories to search for modules. This list is defined in the `sys.path` variable and includes the following directories in this order:

- The directory containing the script that was executed (if applicable).

- Directories in the `PYTHONPATH` environment variable (if set).

- Standard library directories.

- Site-specific directories.

- User-specific directories.

3. Importing Modules: To use a module in your Python script, you import it using the `import` statement. For example:

```python

import mymodule # Import a module named "mymodule"

```

4. Dot Notation: Once imported, you can access the functions, classes, and variables from the module using dot notation. For instance:

```python

mymodule.my_function()

```

5. Module Caching: Python caches imported modules to improve performance. When a module is imported, it's executed only once, and subsequent imports reuse the cached module.

6. Module Initialization: When you import a module, Python executes the code in the module from top to bottom. However, it only does this once per module, even if the module is imported multiple times.

7. `__name__` Attribute: Modules have a built-in attribute called `__name__`. When a module is executed as the main program, its `__name__` is set to `'__main__'`. You can use this to include code that should only run when the module is executed directly.

8. Packages: Packages are a way to organize related modules into directories. A package directory includes a special `__init__.py` file, which marks it as a package. Packages help manage large codebases by providing a hierarchical structure.

9. Relative Imports: Modules can be organized into packages, and you can use relative imports to refer to modules within the same package. Relative imports use dot notation to specify the module's location within the package.

```python

from . import submodule # Relative import within a package

```

10. Standard Library and Third-Party Modules: Python's standard library provides a vast collection of modules for various tasks. In addition to the standard library, you can also install and use third-party modules and packages to extend Python's functionality.

Python's module mechanism is a fundamental feature of the language that promotes code organization, reusability, and maintainability. It allows you to create modular and well-structured code by separating functionality into distinct units that can be easily imported and used in your programs.

Importing modules

The syntax of importing modules for python standard path is below,

Import module_name

· To fetch and use modules from other and new sources, we need to install Python PIP.

· Python pip is a software that installs python modules from an index or using a manager like Anaconda.

· Run the following command to install modules from new sources using python pip:

· python -m pip3 install module_name

· Run the following command to install modules from new sources using Ananconda:

· conda install module_name

· Example: Steps to install NumPy

· python -m pip3 install numpy conda install numpy sudo apt install python3-numpy

To import modules from an external source in Python, you typically use a package manager like `pip`, which allows you to download and install packages (collections of modules) from external sources such as the Python Package Index (PyPI). Here are the steps to import modules from an external source:

1. **Install the Package Manager**:

If you don't have `pip` installed, you can install it by following the instructions provided on the official Python website or the package manager's documentation.

2. **Search for the Desired Package**:

Use the package manager to search for the module or package you want to import. For example, to search for a package named "requests," you can run:

```bash

pip search requests

```

3. **Install the Package**:

Once you've identified the package you want to use, you can install it using `pip`. For example, to install the "requests" package:

```bash

pip install requests

```

This command will download and install the "requests" package and its associated modules.

4. **Import the Module in Your Python Code**:

After installation, you can import the module(s) in your Python code as usual. For example:

```python

import requests

```

5. **Use the Imported Module**:

You can then use the imported module and its functions, classes, and variables in your Python code. For example:

```python

response = requests.get('https://www.example.com')

```

By following these steps, you can import modules from external sources in Python. The process is the same for most external packages, but you may need to consult the specific package's documentation or PyPI page for any additional installation or usage instructions. Keep in mind that using a virtual environment for your project is recommended to manage package dependencies and avoid conflicts between different projects.
Day4

Regular expressions, often referred to as “regexes,” are a concise way of specifying patterns in text. They are a powerful tool in Python, thanks to the `re` module, and serve several key purposes:

1.	Parsing: Regular expressions are used to identify and extract specific pieces of text that match certain criteria within a larger text or data.

2.	Searching: They help locate substrings that may have multiple forms, such as finding various image file extensions like ‘pet.png,’ ‘pet.gif,’ and ‘pet.mpg’ while excluding ‘carpet.gif.’


3.	Searching and Replacing: You can find substrings and replace specific words within the matched string or strings, such as replacing a local phone number format like ‘071 234 5678’ with an international format like ‘+2771 234 5678.’

4.	Splitting Strings: Regular expressions are handy for splitting a string at specific delimiters. For example, you can split a comma-separated list into individual items by using a regex that matches ‘,’.


5.	Validation: They are used to check whether a string adheres to certain criteria, like validating whether an email address is in the standard format.
However, regular expressions do have limitations:
- They are suitable for handling recursive (repeating) structured text only if the maximum number of repetitions is known in advance.
- Large and complex regex patterns can become challenging to maintain and understand.

As a best practice, when dealing with highly structured data formats like XML, it’s often better to use specialized parsers tailored to that format. In simpler terms, a basic regular expression consists of a character followed by a quantifier, while more complex expressions can involve combinations of quantified expressions to match intricate patterns in text data.
 Regular expression syntax
This section provides an overview of regular expressions (regex) and their syntax. It covers key functions from the Python re module and presents a table of commonly used functions and their descriptions.

1. **Introduction to Regular Expressions: ** 
   - Regular expressions are a powerful tool for text pattern matching.
   - The section is divided into four subsections:
     - Matching individual characters or character groups.
     - Quantifying matches (e.g., matching zero or more occurrences).
     - Creating and grouping sub-expressions.
     - Using language assertions and flags.

2. **Table of re Module Functions (commonly used):**
   - `compile`: Compiles a regex pattern.
   - `findall`: Returns a list of all non-overlapping matches in a string.
   - `finditer`: Returns an iterator over all matches.
   - `match`: Tries to apply the pattern at the start of the string.
   - `search`: Scans through a string looking for a match.
   - `split`: Splits a string by pattern occurrences.
   - `sub`: Replaces occurrences of the pattern in the string.
   - `subn`: Returns a 2-tuple with the new string and the number of replacements.
   - `template`: Compiles a template pattern.

3. **Regular Expression Syntax:**
   - This part explains various regex syntax elements:
     - `.` (Dot): Matches any character (except newline).
     - `^`: Matches the start of the string.
     - `$`: Matches the end of the string.
     - `*`: Matches zero or more occurrences.
     - `+`: Matches one or more occurrences.
     - `?`: Matches zero or one occurrence.
     - `{m}`: Matches exactly m occurrences.
     - `{m,n}`: Matches from m to n occurrences.
     - `{m,n}?`: Matches as few occurrences as possible.
     - `\`: Escapes special characters or signals a special sequence.
     - `[]`: Indicates a set of characters.
     - `|`: Represents alternation (matches X or Y).

4. **Raw Strings in Python:**
   - Explains the importance of using raw strings in regex.
   - In raw strings, backslashes are treated as literal characters, making regex patterns cleaner.

5. **Example - Validating Input Format:**
   - Demonstrates the use of regex to validate input.
   - Shows two equivalent regex patterns: one using a raw string and one without.
   - Validates input in the format of three numbers enclosed in brackets.

The provided code example shows how to validate input in a specific format (three numbers enclosed in brackets) using regular expressions and demonstrates the use of raw strings for cleaner pattern definition.

Overall, this section provides a comprehensive introduction to regular expressions and their syntax, with a focus on Python's re module and the importance of using raw strings to simplify regex pattern creation.

Character and character classes:
In this section on regular expressions and escape characters, the following key points are discussed:

1. Basic Regex Expressions:
   - A single character, like '5' or 'b', matches one occurrence by default.
   - Special characters in regex, like '+', '*', and '?', need a backslash (\) as a prefix if they are to be treated as literals.

2. Escape Characters in Python and Regex:
   - Escape characters in Python include '\', '\n', '\t', and more. They are used to represent special characters or control characters.
   - To use special regex characters as literals, they must be preceded by a backslash (\).

3. Example - Matching Special Characters:
   - A Python example is given where regular expressions are used to match the presence of a '+' character and a newline character ('\n') in a sentence.
   - The '^' symbol matches the start of the text, '.*' matches zero or more characters (including newlines), '[\+]+' matches one or more '+' characters, and '$' matches the end of the line.

4. Character Classes and Ranges:
   - Character classes, like [ea], match either 'e' or 'a'.
   - Ranges, like [0-9], match any digit from 0 to 9.
   - Negating a character class, like [^0-9], matches any character except digits.

5. Handling Special Characters within Character Classes:
   - Dashes (-) and some other characters are metacharacters by default. However, if they are the first character within a character class (e.g., [-abc]), they are treated as literals and do not require a backslash.
   - Other metacharacters, like '.', '^', '?', '+', '*', are always treated as literals within character classes.

6. Shortcuts in Character Classes:
   - Python offers shortcuts for character classes, such as '\d' (matches any digit) and '\s' (matches whitespace).
   - The ASCII flag can modify the behavior of these shortcuts.

7. Example - Using Shortcuts in Character Classes:
   - A Python example illustrates how to count the number of words in a sentence using shortcuts like '\w' and '\W'.
   - The regular expression '^[\W]*[\w]*[\W]*' is used to identify words in a sentence.

In summary, this section covers the basics of regular expressions, escape characters, character classes, and shortcuts within character classes. It provides practical examples to demonstrate the use of these concepts in Python.

Quantifies and flags:
Quantifies:
This section explains quantifiers in regular expressions and provides shorthand notations for simplifying the use of quantifiers. The key points covered are as follows:

1. Quantifiers in Regex:
   - A quantifier in regex has the form {m, n}, specifying the minimum and maximum number of times an expression must match.
   - For example, e{1,1}e{1,1} and e{2,2} both match "feelings" but not "belt."

2. Shorthand Notations for Quantifiers:
   - Regex provides shorthand notations to simplify quantifiers.
   - If only one number is supplied, it's assumed that the minimum and maximum are the same. For example, e{4} is equivalent to e{4, 4}.
   - Different minimum and maximum values can be convenient. For instance, to match both "travelled" and "traveled," you can use "travel{1,2}ed" or "travell{0,1}ed."
   - The '?' symbol is used to represent {0,1}, meaning the preceding character is optional.

3. Examples of Using Quantifiers:
   - An example in Python demonstrates the use of quantifiers to match words like "travelled" and "traveled" with the pattern 'travell?ed' (where '?' is a shorthand for {0,1}).
   - This allows for flexibility in matching words with different numbers of 'l' characters.

In summary, this section clarifies the concept of quantifiers in regular expressions and shows how shorthand notations like '?' can be used to make regex patterns more concise and flexible. It provides a practical example in Python to illustrate the application of these quantifiers.

Flags:
Flags are used to tell the regex how to behave when looking for expressions.
This section introduces various regex flags and their functions in Python. The key points covered include:

1. Regex Flags:
   - Python offers several flags to modify the behavior of regex patterns.
   - Flags, like re.IGNORECASE or re.VERBOSE, can be used to make regex matching more flexible and readable.

2. Examples of Flags:
   - An example demonstrates the use of the IGNORECASE flag (re.IGNORECASE or re.I) for case-insensitive matching. It removes all vowels (both uppercase and lowercase) from a string.
   - Another example uses the VERBOSE flag (re.VERBOSE or re.X) to make a complex regex pattern more readable. It checks whether a string is a valid octal or hexadecimal number.
   
3. IGNORECASE Flag:
   - The IGNORECASE flag is used to make regex matching case-insensitive, reducing the need to specify both uppercase and lowercase characters explicitly.

4. VERBOSE Flag:
   - The VERBOSE flag allows comments and white spaces to be included in a regex pattern, making complex expressions more readable.
   - It can be especially useful for explaining longer and more intricate regular expressions.

In summary, this section covers the use of regex flags, specifically the IGNORECASE (case-insensitive) and VERBOSE (readable) flags, and provides practical examples to illustrate their application in Python.

# week Day 3

1 / 26
Week 3 Python
Data structure Day 1
· .Function Definition:
o `fib(n)` is defined to print the Fibonacci series up to the given boundary `n`.
o `fib2(n)` is defined to return a list containing the Fibonacci series up to `n`.

· Fibonacci Calculation:
o The Fibonacci series is generated using two variables, `a` and `b`, initialized to 0 and 1.
o The series is calculated in a loop using the formula `a, b = b, a + b`.

· Printing vs. Returning:
o `fib(n)` prints the series while `fib2(n)` returns it as a list.
· Function Calls:
o `fib(2000)` and `fib(0)` are examples of function calls.
o `fib2(100)` returns the Fibonacci series up to 100 and stores it in the variable `f100`.

· Return Statement:
o The `return` statement is used to return a value from a function. It returns `None` if omitted.

· List Manipulation:
o `result.append(a)` adds the value of `a` to the `result` list.

· Method Calls:
o `result.append(a)` demonstrates calling a method (`append()`) on a list object (`result`).
· Function Renaming:
o Functions can be assigned to other names, like `f = fib`, allowing you to call them using the new name.

· None:
o Functions without a `return` statement return `None`. It's Python's way of representing no value.

· Efficiency:
o The `result.append(a)` method is more efficient than `result = result + [a]` for building lists.

More on lists:
2 / 26
· `list.append(x)`: Add an item to the end of the list.
· `list.extend(iterable)`: Extend the list by appending items from an iterable.
· `list.insert(i, x)`: Insert an item at a given position.
· `list.remove(x)`: Remove the first occurrence of an item with a specific value.
· `list.pop([i])`: Remove and return an item at a given position or the last item if no index is specified.
· `list.clear()`: Remove all items from the list.
· `list.index(x)`: Find the index of the first item with a specific value.
· `list.count(x)`: Count the number of times a specific value appears in the list.
· `list.sort()`: Sort the list in place.
· `list.reverse()`: Reverse the list in place.
· `list.copy()`: Create a shallow copy of the list.

These methods allow you to manipulate and work with lists efficiently.
Using List as stack and queues:
You can use a list as a stack for "last-in, first-out" operations by using `append()` to add items to the top and `pop()` to retrieve items from the top.

For a queue with "first-in, first-out" operations, it's better to use `collections.deque` for efficiency. It provides fast appends and pops from both ends.

Stack using list:



Queue using collections.deque:



Lists are not efficient for queues because inserting or popping from the beginning of a list is slow due to shifting elements. Use `collections.deque` for faster queue operations.
3 / 26
List comprehensions:

List comprehension provides a concise way to create lists in Python. They consist of an expression followed by a for clause and optional if.


4 / 26

Nested List Comprehensions:
You can use list comprehensions for complex tasks, like transposing a matrix, but prefer built-in functions when possible. For transposing, use zip():




The del statement / Tuples and Sequences:
In Python, you can use the del statement to remove items from a list by specifying their index or clear the entire list. For example:
5 / 26


· Tuples are similar to lists but are immutable, meaning you can't change their elements after creation. They are often used for different purposes.  
· Tuples are defined with parentheses, and they can be nested. You can use sequence unpacking to assign values from a tuple to variables:


· Tuples with one item require a trailing comma to distinguish them from parentheses, like this:


· Tuples are useful for situations where you want to ensure data remains unchanged, and sequence unpacking simplifies variable assignment from tuples.
Sets:
§ Python has a set data type that stores an unordered collection of unique elements.
§ You can create a set using curly braces or the set () function.
§ Sets are handy for membership testing and mathematical operations like union, intersection, difference, and symmetric difference.

6 / 26

Dictionaries:
· Dictionaries are another data type in Python, used for key-value pairs.  
· Dictionaries are created with curly braces or the dict() constructor.  
· Keys must be unique, and you can store, extract, or delete values based on keys. Here's a quick overview.

7 / 26

Looping Techniques:
You can loop through dictionaries using the items () method to get both the key and value simultaneously:

You can loop through sequences and get the index and value using enumerate():


To loop over multiple sequences in parallel, use zip():


For looping in reverse, use reversed():


To loop over a sequence in sorted order, use sorted():
8 / 26


Avoid modifying a list while looping over it, and consider creating a new list instead. For example, you can filter out NaN values from a list:



Comparing Sequences and Other Types:
· Sequence objects can be compared to other objects of the same type using lexicographical ordering. This means they are compared element by element, with the first differing element determining the outcome.
· If all elements are equal, the sequences are considered equal.

Examples of comparisons:
o (1, 2, 3) < (1, 2, 4)
o [1, 2, 3] < [1, 2, 4]
o 'ABC' < 'C' < 'Pascal' < 'Python'
o (1, 2, 3, 4) < (1, 2, 4)
o (1, 2) < (1, 2, -1)
o (1, 2, 3) == (1.0, 2.0, 3.0)
o (1, 2, ('aa', 'ab')) < (1, 2, ('abc', 'a'), 4)

You can compare objects of different types if they have appropriate comparison methods. Otherwise, it raises a TypeError exception.

Day 2:
How to create list.
A Python list is like a container that can hold multiple items (numbers, words, etc.). To create a list, you put your items inside square brackets [ ], separated by commas.
9 / 26


We can also have nested list, which we can have list as items:



Access list elements:
· In Python, you can access elements in a list using the index operator [].
· Lists start with an index of 0, so the first item is at index 0, the second at 1, and so on. For example
· We can use the index operator [] to access an item in a list. In Python, indices start at 0. So, a list having 5 elements will have an index from 0 to 4.
· Trying to access indexes other than these will raise an IndexError. The index must be an integer. We can't use float or other types, this will result in TypeError.
· Nested lists are accessed using nested indexing.

10 / 26


Output:



Negative indexing:
In Python, you can use negative indexing to access items in a list or sequence.

· Index -1 refers to the last item.
· Index -2 refers to the second-to-last item.
· And so on, with each negative index counting backward from the end of the list.


Output:
11 / 26


How to slice lists in Python?




Output:














12 / 26
Add/Change List Elements:
· Lists are mutable, meaning their elements can be changed unlike stings or tuple.
· We can use the assignment operator = to change an item or range of items.



Output.




· We can add an item on the list using append ().
· Add several items using extend().
13 / 26

   

· Use the + operator to combine two lists.
· This is called concatenation.
· The * operator repeats a list for the given number of times.
14 / 26




Delete/Remove List Elements
· In Python, you can delete or remove elements from a list using various methods.  
· The two primary methods for removing elements from a list are using the `del` statement and the `remove()` method.  
Here's a summary of each method along with an example:

· Using the `del` Statement:
- The `del` statement allows you to remove an element from a list by specifying its index.
- It can also be used to delete entire slices of a list.
- This method directly modifies the original list.

Example:
· ```python
· # Create a list
· my_list = [1, 2, 3, 4, 5]

· # Remove the element at index 2 (which is '3')
· del my_list[2]
15 / 26

· print(my_list)  # Output: [1, 2, 4, 5]
```

· Using the `remove()` Method:
- The `remove()` method is used to delete the first occurrence of a specific value from the list.
- It does not require specifying an index but rather the actual value to be removed.
- If the value appears multiple times in the list, only the first occurrence is removed.

Example:
· ```python
· # Create a list
· my_list = [1, 2, 3, 2, 4, 5]

· # Remove the first occurrence of the value '2'
· my_list.remove(2)

· print(my_list)  # Output: [1, 3, 2, 4, 5]
· ```

· It's important to note that if you want to remove an element from a list without knowing its index or value, you can use methods like `pop()` to remove the last element, or you can use list slicing to create a new list with the elements you want to keep. Additionally, you can use list comprehensions to filter out specific elements from a list and create a new list without them.

Python List Method
Python provides a variety of built-in list methods that allow you to manipulate and perform operations on lists efficiently. Here's a summary of some commonly used Python list methods along with examples:

1. **append(element):**
  - The `append()` method is used to add an element to the end of a list.

  **Example:**
  ```python
  my_list = [1, 2, 3]
  my_list.append(4)
  print(my_list)  # Output: [1, 2, 3, 4]
  ```
16 / 26

2. **extend(iterable):**
  - The `extend()` method is used to add elements from an iterable (e.g., another list) to the end of the list.

  **Example:**
  ```python
  my_list = [1, 2, 3]
  my_list.extend([4, 5])
  print(my_list)  # Output: [1, 2, 3, 4, 5]
  ```

3. **insert(index, element):**
  - The `insert()` method allows you to insert an element at a specified index in the list.

  **Example:**
  ```python
  my_list = [1, 2, 3]
  my_list.insert(1, 4)
  print(my_list)  # Output: [1, 4, 2, 3]
  ```

4. **remove(element):**
  - The `remove()` method deletes the first occurrence of a specific element in the list.

  **Example:**
  ```python
  my_list = [1, 2, 3, 2, 4, 5]
  my_list.remove(2)
  print(my_list)  # Output: [1, 3, 2, 4, 5]
  ```
