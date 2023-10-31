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
- Hello, Rahul. Good morning!
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
