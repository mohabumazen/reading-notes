# The Global Scope
- Python turns the program’s main script into a module called main to hold the main program’s execution. The namespace of this module is the main global scope of your program.
- Any name defined at the top level of any Python module, then that name is considered global to the module.
- main' is also the name of its main module name 'main'
- The interpreter executes the code in the module or script that serves as an entry point to your program
- We can access or reference the value of any global name from any place in your code. This includes functions and classes.

Whenever a value is assigned to a name in Python, one of two things can happen:
1. We create a new name
2. We update an existing name


### The nonlocal Statement
- Nonlocal names can be accessed from inner functions, but not assigned or updated

- With a nonlocal statement, we can define a list of names that are going to be treated as nonlocal.

- The nonlocal statement consists of the nonlocal keyword followed by one or more names separated by commas

- We can’t use nonlocal outside of a nested or enclosed function, we can’t use a nonlocal statement in either the global scope or in a local scope.

- Names must already exist in the enclosing Python scope if we want to use them as nonlocal names. This means that we can’t create nonlocal names by declaring them in a nonlocal statement in a nested function.

# Big O

- Is a way for comparing algorithms with other algorithms, and how the algorithm will perform
- Is a way of measuring how an algorithm will respond to an increasing amount of data that it has to process
- It gives us that the algorithm Worst Casen
- Two Components:

1. Time Complexity: How long an algorithm takes to do something
2.Space Complexity: How mush memory it takes while its doing something
- Types of Complexities:

1. O(1) -> Constant running time
2. O(logn) -> Logarithmic running time
3. O(n) -> Linear running time
4. O(n logn) -> Log-Linear running time
5. O(n^k) -> Polynomial running time
6. O(c^n) -> Exponential running time