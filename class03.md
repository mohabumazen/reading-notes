# Reading and Writing files in Python

### What is a file?
- It is a combination of bytes used to store data
- Files components: Header, Data, EOF (End of file)
- When we want to read from or write to a file we have to open it first.
- Files are named locations on disk.

### File paths

- A file path is required when you access a file on an operating system.
- We have folder path, file name, extension


### How to open and close a file in Python:

- open() bulit-in function is used to open a file
- try-finally block is used to close a file, even when encountering an error. The second way is to use with statment.
- 'r' => open for reading
- 'w' => open for writing 
- 'rb' or 'wb' open for binary mode
- File objects: Text files, buffered binary files and raw binary files.

# Pyhton Exceptions 

- Syntax errors occur when there is an incorrect statment
- Exception errors occur when a correct python code gives an error.
- AssertionError: It can be used to avoid the program to crash during the execution of the code, it can give two results: 1. if a condition is met then gives True, otherwise if it's false it should give an assertionError.
- The try and except block is used for handling exceptions errors. So, In the try clause all statments are executed untill an exception occurs.

