# Classes & Objects

- Class: it's a template to create objects
- object: it's a section where you can put variables and functions in.
- To access a variable in an object : object_name.variable_name, and the same applies for the functions
- The __init__() function, is a special function that is called when the class is being initiated. It's used for asigning values in a class.

# Thinking Recusively

- Break problems into small parts A recursive function is a function defined in terms of itself via self-referential expressions.
- Recursive Function : A function that calls itself
- Behind the scenes, each recursive call adds a stack frame (containing its execution context) to the call stack until we reach the base case. Then, the stack begins to unwind as each call returns its results

# Maintainng State

- Thread the state through each recursive call so that the current state is part of the current call’s execution context
- keep the state in global scope

# Coverage

- Coverage.py is a tool for measuring code coverage of Python programs. It monitors your program, noting which parts of the code have been executed, then analyzes the source to identify code that could have been executed but was not.
- Coverage measurement is typically used to gauge the effectiveness of tests. It can show which parts of your code are being exercised by tests, and which are not. Checking that your tests have run all of the code.
