# List Comprehensions 

- It's a method for creating python lists
- my_new_list = [ expression for item in list ]
- list comprehension is usually faster than other methods
- To create a list:

    1. Using loop
    2. list comprehension

### Multiplying parts of a list

    Using loop

    1. Create an empty list
    2. loop over the elements in the list using for loop
    3. expression to carry out
    4. append to the new list new_list = [] for x in range(y): if x % 2 == 0: squares.append(x*2)

    Using list comprehension

    1. assign a variable to be a list with: expression to carry out, for loop, condition all in one line inside the list new_list = [x*2 for x in range(y) if x % 2 == 0]
    
### Show the first letter of each word Using list comprehension

    letters = [ name[0] for name in authors ]

### Separating the characters in a string

    letters = [ letter for letter in "any string"]
### Lower/Upper case converter

    lower_case = [ letter.lower() for letter in ['A','B','C'] ]
    upper_case = [ letter.upper() for letter in ['a','b','c'] ]
### Print numbers only from a given string

    phone_number = [ x for x in user_data if x.isdigit()]
### Parsing a file using list comprehension

    open the file in read-only mode
    reading_file = [ line for line in file ]
    for line in reading_file:
        print(line)
