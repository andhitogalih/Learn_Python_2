# Learn_Python_2
Welcome to this Python learning repository!

This repository is designed to make learning Python for students easy and enjoyable. Here, you'll find various learning materials, including:
* [Function]
* [Numpy]
* [Pandas (Series)]
* [Pandas (Data Frame)]
* [Module Random] 
* [Datetime]
* [File txt]

## Function
In Python, a function is a block of reusable code that performs a specific task. Functions allow you to break down your program into smaller, manageable pieces, making your code more modular, readable, and easier to maintain.

* An input to output mapping procedure is known as a function in mathematics. Functions are used in Python to arrange code for reusability and to accomplish a comparable function.
* A defined purpose and reusability should be the ideal characteristics of Python functions.Although Python comes with many built-in functions, programmers have the ability to construct their own unique functions.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Function.png)

### Return
In Python, the return statement is used within a function to exit the function and return a value or an expression to the caller. When a return statement is encountered in a function, the function's execution is terminated immediately, and control is passed back to the point where the function was called from. 

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Return.png)

### Modify
To modify a list within a function in Python, you can pass the list as an argument to the function and make changes to it directly within the function. Since lists are mutable objects in Python, any modifications made to the list inside the function will affect the original list.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Modify.png)

### Create a function (parameters are changed and parameters are assigned)
This code snippet first initializes a list value_list with a single element 75, then calls the modify_values function with value_list as an argument. After the function call, it prints the modified value_list to see the changes made within the function.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Parameter.png)

## Numpy
NumPy (Numerical Python) is a Python library that focuses on scientific computing. NumPy has the ability to create N-dimensional array objects, which are similar to lists in Python. The advantage of NumPy arrays compared to lists in Python is that they consume less memory and run time faster. NumPy also makes it easier for us in Linear Algebra, especially operations on Vectors (1-d arrays) and Matrix (2-d arrays).

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Numpy.png) 

### Dimension
Dimensions of an array in NumPy are also called the Rank of an Array. Here, we will see how to check how many dimensions an array has used with the numpy.ndarray.ndim. With that, we will also see some examples of creating 0D, 1D, 2D, and 3D arrays:

* Create a 0-Dimensional NumPy array and check the dimensions
* Create a 1-Dimensional NumPy array and check the dimensions
* Create a 2-Dimensional NumPy array and check the dimensions
* Create a 3-Dimensional NumPy array and check the dimensions
  
![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Dimention.png) 

## Pandas
Pandas (Python for Data Analysis) is a Python library that focuses on data analysis processes such as data manipulation, data preparation, and data cleaning. Pandas provides high-level data structures and functions to make working with structured/tabular data faster, easier, and expressive.


Pandas has two objects, namely series and data frame


Import libraries that are needed
### Object Series
A Pandas Series is like a column in a table. It is a one-dimensional array holding data of any type. It is similar to a table column and can be considered a fixed-size dictionary, where the index labels map to the corresponding values.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/Pandasseries.png) 

#### Data Slicing
Slicing is the extraction of a part of a string, list, or tuple. It enables users to access the specific range of elements by mentioning their indices.

Explicit and Implicit Data Slicing
Using an explicitly defined index, such as an index range or a specific index, explicit data slicing gets a subset of data. When the last index is excluded from the resultant subset of data, 


implicit data slicing retrieves a subset of data with reference to an implicitly specified index, such as a particular rule or condition.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/Slicing.png) 

#### Loc &Iloc
Loc is short for location. As the name implies, it is used to select data at a specific location only.
![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Loc.png)

The iloc property gets, or sets, the value(s) of the specified indexes. Specify both row and column with an index.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Iloc.png)
 
## DataFrame
The pandas DataFrame is a structure that contains two-dimensional data and its corresponding labels.For example, DataFrame is built by 2 series.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

## Load Data CSV in Pandas
The Pandas module in Python offers a quick and easy method for handling structured data, and it can be used to import a CSV file. Verify that the uploaded CSV data is in the same folder.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Load%20data%20csv.png)

Given the example of importing data 'Titanic.csv' with the “pd.read_csv()” function.

### Head
• looking at the most recent data
• Head is the top 5 by default

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/head.png)
 
### Info
The info() method prints information from the DataFrame. The information includes the number of columns, column headers, column data types, memory usage, range index, and number of cells in each column (non-zero values).

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/info.png)

### Tail
A given number of last rows is returned by tail(). In the absence of a number, tail() retrieves the previous five rows.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/tail.png)

### Shape
Shape is the number of columns and columns of the DataFrame.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Shape.png)

### Columns
Columns returns the name of each column within the DataFrame.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/coulmn.png)

### Index
The record returns the record data of the DataFrame. The file data contains the names of the columns. In case the lines have NOT named records, the record property returns a RangeIndex protest with the begin, halt, and step values.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/index.png)

### Sum
Returns the entirety of the values within the indicated pivot. By indicating the column hub (axis='columns'), the entirety() strategy looks column-wise and returns the whole of each push.

### Isnull
Isnull is utilized to discover Invalid values.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/isnull.png)

### Notnull
Notnull is utilized to discover values that are NOT Invalid.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/notnull.png)

### Describe
Returns a description summary for each column within the DataFrame

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/describe.png

### Mean
The average value

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/mean.png)

### Median
The midpoint value

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/median.png)

### Mode
The most common value

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/modus.png)

### Unique
Returns the min of the values within the indicated hub
![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

### Slicing
![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/slicingdataframe.png)

## Module Random
### Random()
This function does not require arguments. When called, by default the function will generate a random float number between 0.0 and 1.0. Each time the function is called, it will return a different number.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Random.png)

### Randint(a, b)
The randint(a,b) function accepts two arguments (a and b), which are the lower and upper bounds for the number to be returned. This function will return a random integer that falls within that range, including both limits.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Randint.png)

## Datetime
In Python, date and time are not data types of their own, but a module named DateTime in Python can be imported to work with the date as well as time.

* date – An idealized naive date, assuming the current Gregorian calendar always was, and always will be, in effect. Its attributes are year, month, and day.
* time – An idealized time, independent of any particular day, assuming that every day has exactly 24*60*60 seconds.
* date-time – It is a combination of date and time along with the attributes year, month, day, hour, minute, second, microsecond.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Datetime.png)

## File txt
For reading text files, we can use the open() function to open the file in read mode and then read its contents using methods like read(), readline(), or readlines().Then to write data to a text file, we can open the file in write mode using open(), and then use the write() method to write data into the file.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/File%20txt.png)
