[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15313828&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a high leveled, general purpose programming language known for its readability, simplicity and versatility.

Key features of python:
   Python code is executed line by line, making it easier to debug and create interactive programs.
   Python supports object-oriented programming, allowing developers to organize code into objects and classes.
   Python allows variables to change types at runtime, providing flexibility and reducing the need for type annotations.
   Python uses whitespace (indentation) to define blocks of code, making it more readable and visually appealing.
   Python has a vast ecosystem of libraries for various tasks, such as data science, web development, and machine learning.
   Python can be run on multiple operating systems (Windows, macOS, Linux) and architectures.
   Python can be used for a wide range of applications, including web development, data analysis, scripting, and machine learning.

Web Development: 
   Python frameworks like Django and Flask are popular for building web applications and APIs.
Data Science: 
   Python libraries like NumPy, Pandas, and Matplotlib make it widely used for data analysis, visualization, and machine learning.
Data Automation:
    Python's scripting capabilities enable the automation of repetitive tasks, such as data extraction, cleaning, and transformation.
Machine Learning: 
   TensorFlow, Keras, and scikit-learn are popular Python libraries for developing and deploying machine learning models.
System Administration: 
   Python can be used to create scripts and automate system administration tasks, such as managing files, processes, and user accounts.
Artificial Intelligence: 
   Python's simplicity and libraries for natural language processing, computer vision, and deep learning make it a great choice for AI development.
Education: 
   Python's ease of learning and extensive resources make it popular for introductory programming courses and teaching programming concepts.


2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

Intalling Python on windows:
   Visit thw official website https://www.python.org/downloads/ to download. thenvisit the on screen instructions. Open the command prompt and type "python --version" to counter check the installed python version. To set up a vertual environment write the following code, ' python -m virtualenv venv_name' replace 'venv_name' with the actual virtual environment name. 
Installing pythin on Linux:
   Open a terminal and  update the package manager; 
      Ubuntu/Debian: "sudo apt update"
      Red Hat/CentOS: "sudo yum update"
   Install Python:
      Ubuntu/Debian: "sudo apt install python3"
      Red Hat/CentOS: "sudo yum install python3"
   Verify the installation by opening a terminal and typing "python3 --version" to see the installed python version.
   Write "python3 -m venv venv_name" to set up the vitual environment, replace "venv_name" with the actual virtual environment name.
Installing python on macOS:
   Install Homebrew, a package manager for macOS: https://brew.sh/ , then run the following command "brew install python". Write "python --version" to see the python version. Write "python3 -m venv venv_name" to set up the virtal environment and replace "venv_name" with the actual virtual environment name. 


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

Code:
   print("Hello, World")

Explanation:  
   print: This is a built-in function in Python used to output data to the console.
   (): Parentheses are used to group arguments passed to the function. In this case, we're passing a single argument, the string "Hello, World!".
   "": Double quotes define a string literal, which is a sequence of characters enclosed within quotes. In this program, the string "Hello, World!" is the message we want to print.
   Semicolon (;) (Optional): In Python, statements typically don't require a semicolon at the end. However, you can optionally use semicolons to include multiple statements on a single line, although this is not commonly practiced for readability.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

Basic date types:
   Integer (int): Represents whole numbers without decimal points, such as 1, -5, 1000.
   Float (float): Represents numbers with decimal points, such as 3.14, -0.5, 2.0.
   String (str): Represents text, enclosed in single (') or double (") quotes, such as "hello", 'Python', "123".
   Boolean (bool): Represents True or False values, used in logical expressions and comparisons.
   List (list): Represents an ordered collection of items, enclosed in square brackets [], such as [1, 2, 3], ['apple', 'banana', 'cherry'].
   Tuple (tuple): Similar to a list but immutable (cannot be changed), enclosed in parentheses (), such as (1, 2, 3), ('a', 'b', 'c').
   Dictionary (dict): Represents a collection of key-value pairs, enclosed in curly braces {}, such as {'name': 'Alice', 'age': 30}.
   Set (set): Represents an unordered collection of unique items, enclosed in curly braces {}, such as {1, 2, 3}, {'apple', 'banana', 'cherry'}.

Short script that demonstrates how to create and use variables of different data types:
   # Create variables of different data types

   int = 10
   float = 3.14
   bool = True
   str = "Hello World"
   list = [1, 2, 3, 4, 5]
   tuple = (1, 2, 3, 4, 5)
   dict = {"name": "John Doe", "age": 30}

# Print the variables

   print("Integer:", int)
   print("Float:", float)
   print("Boolean:", bool)
   print("String:", str)
   print("List:", list)
   print("Tuple:", tuple)
   print("Dictionary:", dict)



5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

If-else statemant is used to make decisions based on certain conditions. Example:
   age = int(input("Enter your age: "))

   if age >= 21:
      print("You are eligible to drink cocktails")
   else:
      print("You are not eligible to drink cocktails")


Explanation:
   So when you run this program you will be required to enter your age. When you enter your age the program will check if your age is greater than or equal to 21. If it is greater than 21 then the output will be "You are eligible to drink cocktails", and vice versa if the inputed age is less than 21 then the output will be "You are not eligible to drink cocktails"

For loop is used to iterate over a sequence and perform actions on each item in the sequence. Example:
   colours = ["Blue", "Black", "purple"]
   for colour in colours:
      print("I like ", colour)


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

Function in python is a block of reusable code that performs a specific task.

Benefits of Functions:
   Allow one to reuse code without re-writing it.
   Breaks down complex task into smaller, managerble functions.
   Make code easier to read and understand.
   Make it easier to update and debug code.

Example:
   def add_two_numbers(a, b):
      return a + b
   
   result = add_two_numbers(5, 5)
   print("The sum of 5 and 5 is :, result)

Explanation:
   def is used to define a function and in this case it is defining the "add_two_numbers" function. Then the "Return" just shows the output in this case the output is "a + b". the now call your defined function then print the output to get the desired output.


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

Difference between list of numbers and dictionaries:
   A list is an ordered collection of items which can be of different types while a dictionary is an unordered collection of key-value pairs
   Lists are defined using square brackets while dictionaries are defined using curly brackets.
   Lists are accessed by their index, starting from 0 while dictionaries are accessed by their keys.
   Lists are used when you need an urdered collection of items that can be indexed while dictionaries are used when you need to store data that can be quickly accessed via unique keys.

Example:
   numbers = [10, 20, 30, 40, 50]
   person = {
      'name' = 'Alice',
      'age' = 30,
      'city' = 'New York'
   }
   print("Original list:", numbers)
   
   numbers.append(60)
   print("List after appending 60:", numbers)

   numbers.remove(30)
   print("List after removing 30:", numbers)

   second_element = numbers[2]
   print("Second element in the list:", second_element)

   print("Original dictionary:", person)

   person['job'] = 'Engineer'
   print("Dictionary after adding job:", person)

   del person['age']
   print("Dictionary after removing age:", person)

   city = person['city']
   print("City from the dictionary:", city)

Explanation:
   List operations:
      numbers: creates our list to work with
      numbers.append(60): adds the number 60 to the end of the list 
      numbers.remove(30): removes the first occurence of the number 30 from the list.
      numbers[2]: access the third element in the list.

   Dictionary operations:
      person: creating the dictionary to work with.
      person['job'] = 'Engineer': adds new key(job) with the value (engineer).
      del person['age']: removes the key 'age' and ts associate value.
      person['city']: accesses the value associated with the key 'city'.


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

Exception handling is a mechanism to handle runtime errors, allowing the program to continue executing or terminate gracefully.
   'try' block: Contains code that may throw an exception. if an exception occurs within the try block then the control jumps to the except block.
   'except' block: Handles the exception that occured in thetry block. multiple except blocks can be specified to handle different types of exceptions.
   'finally' block: This block is executed whether or not an exception occerred in the try block. Used to perform cleanup operations such as clossing file handles or connections.

Example:
   def divide(numerator, denominator):
      try:
         result = numerator / denominator
      except ZeroDivisionError:
         print("Error: Cannot divide by zero.")
      finally:
         print("Division operation completed.")
   
   result = divide(10, 2)
   print("Result:", result) # Output: Result: 5

   result = divide(10, 0)
   Print("Result:", result) # output: Error: cannot divide by zero.
                                      Division operation completed.

Explanation:
   We first define the function you want to use and in this case it is the 'divide' function. then start with the try block. Basically this function is trying to check whether the numerator is divisible by the denominator. If it is then the answer will be displayed and also the message on the finally block which is "Division operation completed". Suppose the number is being divided by zero then it will display the error message in the except block and also the message in the finally block.

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

A module in python is a file containing Python code which can be imported and used in other Python programs.

A package in python is a way of organising related modules into a directory hierachy

Example using the 'math' module;
   import math

   number = 16
   square_root_number = math.sqrt(number)
   print(f"The square root of {num} is {square_root_number}")

Explanation:
   This program simply calculates the square root of the number 16. You import the 'math' module and use the functions under the math module. in this case the function being used is the '.sqrt' function to calculate the square root of the number provided.



10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

To read from a text file, you first use the 'open' function to open the file with the file name and mode. use methods like 'read()', 'readline()' or 'readlines()'. Finally ensure you close the file using 'close()' function to release resources.

Example of a file that reads:
   with open("my_file.txt", "r") as file:
      content = file.read()
   print("file content: ")
   print(content)

Explanation:
   open the file either in read or write mode. In this case its opened in read mode because of the "r". Then read the entire content and store it in the 'content' variable. Finally print the content to the console.
 
Example of a file that writes:
   with open("fruits.txt", "w") as file:
      fruits = ["apple", "banana", "cherry"]

      for fruits in fruits:
         file.write(fruit + "\n")

   print("Fruits written to fruits.txt")

Explanation:
   Open the file in write mode "w". Use the '.write()' function to write each fruit along with a new line character to the new file. Finally  a message is printed indicating successful writing.
   

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].



