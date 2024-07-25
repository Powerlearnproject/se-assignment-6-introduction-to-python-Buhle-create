[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15464389&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
Python is a high level programming language which is very simple and readable. It supports various programming paradigms which are procerdural, object oriented and functional programming.Python's main features are: a.It is an interpretable language whose code is executed line by line which makes it easier to debug.
     b. Python variables do not require strong declaration of their types.
     c. Python has a huge standard library that has modules and functions for various tasks.
     d. Python has a large and active community that contributes to a surplus of resources and third party libraries.
     -Python is effective in Web development by using frameworks like Django.
     - Libraries like Pandas and NumPy are good for data science and machine learning.
     
2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
     WINDOWS
   - a. Download the installer from python.org
   - b. Run the installer and check the 'Add Python to PATH' option.
   - c. Follow the intsallation prompts.
   - d. Verify the installation by typing 'python--version'
   - e. Set up the virtual environment by installing virtualenv and create a virtual environment and activate the virtual environment.
   - Windows:myenv\Scripts\activate.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   - print ("Hello,World!")
   - print: A built in function to output text to the console.
   - "Hello, World!" :  a string 

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   - str: strings (text)
   - int: Integer numbers
   - float: Floating point numbers.
   - bool: Boolean values
   - dict: Key value pairs
   - list: Ordered collection of items
   -  Integer
a = 22

 Float
b = 10.5

 String
c = "Hello"

 Boolean
d = True

print(a, b, c, d)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   - Conditional statements: These are important programming constructs that permit you to control the flow of your program based on conditions that you specify.

    - x = 8

if x > 4:
    print("x is greater than 4")
else:
    print("x is 4 or less")
    - Loops: It is a control flow statement which repeatedly executes a block of code until the condition is satsified.
for i in range(4):
    print(i)
    
6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
- Functions are reusable blocks of code that do a certain task. These functions are used to "bundle a set of instructions that you want to use repeatedly or that , because of their complexity, are better self contained in a sub program and callec when needed" (datacamp)

- def add(a, b):
    return a + b

 Calling the function
result = add(5, 4)
print(result) # Output: 9

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   - A list is an ordered collection of objects whereas a dictionary is an unoredered data collection in a key.
   - List:
     numbers = [2, 4, 6, 8, 10]
print(numbers[0]) # Accessing the first element

   - Dictionary:
     person = {"name": "Buhle", "age": 36}
print(person["name"]) # Accessing the value associated with the key "name

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   - Exceptional Handling a technique whereby errors are resolved in a program.
     try:
    result = 22 / 0
except ZeroDivisionError:
    print("Cannot divide

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
- A module is a single file that contains Python definitions and  statements. Python codes are organized logically in modules by having a .py extension.
- Packages is a process of structuring Python's module namespace by using dotted module names. It contains a unique -init-.py file that contains numerous modules and sub packages.
  import math

 Using the math module to calculate the square root and cosine:
num = 9
sqrt_result = math.sqrt(num)
cos_result = math.cos(math.pi / 3)

print(f"The square root of {num} is {sqrt_result}")
print(f"The cosine of 45 degrees is {cos_result}")

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    - One can read from a file by using the open function in read mode ('r')
  Reading the content of a file and printing it to the console
with open('example.txt', 'r') as file:
    content = file.read()
    print(content)

Writing a list of strings to a file
lines = ["First line", "Second line", "Third line"]

with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + '\n')

        #REFERENCES:
        
hhtps://in.indeed.com
https://www.geeksforgeeks.org
https://docs.python.org
https://www.educative.io
https://www.datacamp.com

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


