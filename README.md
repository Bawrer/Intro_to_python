# Intro_to_python
notes and activities

# Day1 Notes

Python is a high-level, interpreted programming language known for its simplicity and readability. 

## pYTHON IN THE JOB MARKET

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

This should give you a good introduction to common data types in Python and how to use them. Keep in mind that Python's dynamic typing allows you to assign different data types to variables as needed, which makes it a versatile and powerful language.
