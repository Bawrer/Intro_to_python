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
