# Jupyter Lab
JupyterLab is a next-generation web-based user interface for Project Jupyter

JupyterLab enables us to work with documents and activities such as:
- Jupyter notebooks
- text editors
- terminals
- custom components 

in a flexible, integrated, and extensible manner.

**Text, code consoles, and terminals:**
Includes syntax highlighting and configurable indentation.

To create code console for the text -> right click -> New console for editor -> Python

**Common Format**

All image formates are supported as separated files

**Shortcuts:**
Zoom in and out (- =)
Rotate left/ right []
Reset 0

**Jupyter Note Books:**

New way to work easily with data and code
Jupyer has 2 modes:
1. When a notebook is open --> Command Mode --> Easily navigating and changing the framework of my notebook
2. Edit mode: press enter to edit the current active cell

Composed of cells, which keeps my data and code in small containers


# NumPy Tutorial: Data Analysis with Python

NumPy is a commonly used Python data analysis package. By using NumPy, you can speed up your workflow, and interface with other packages in the Python ecosystem,

The data is in ssv (semicolon separated values) format —> each record is separated by a semicolon (;), and rows are separated by a new line

**Lists Of Lists for CSV Data**

Working with the data using Python and the csv package

We can read in the file using the csv.reader object, which will allow us to read in and split up all the content from the ssv file.

    Import the csv library
    Open the example.csv file.
        With the file open, create a new csv.reader object.
            Pass in the keyword argument delimiter=";" to make sure that the records are split up on the semicolon character instead of the default comma character.
        Call the list type to get all the rows from the file.
        Assign the result to varaible.

Once we’ve read in the data, we can print out any number of rows

The data has been read into a list of lists. Each inner list is a row from the ssv file. Each item in the entire list of lists is represented as a string, which will make it harder to do computations --> format the data into table

**Numpy 2-Dimensional Arrays(Matrix)**

With NumPy, we work with multidimensional arrays

In a NumPy array, the number of dimensions is called the rank, and each dimension is called an axis. So the rows are the first axis, and the columns are the second axis.

**Slicing NumPy Arrays**

If we want to select the first three items from the fourth column, we can do it using a colon (:)
A colon indicates that we want to select all the elements from the starting index up to but not including the ending index

**Assigning Values To NumPy Arrays**

We can also use indexing to assign values to certain elements in arrays. We can do this by assigning directly to the indexed value
