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

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

Given the example of importing data 'Titanic.csv' with the “pd.read_csv()” function.

### Head
• looking at the most recent data
• Head is the top 5 by default

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)
 
### Info
• The info() method prints information from the DataFrame. The information includes the number of columns, column headers, column data types, memory usage, range index, and number of cells in each column (non-zero values).


![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)
### Tail
• A given number of last rows is returned by tail(). In the absence of a number, tail() retrieves the previous five rows.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)
### Shape
Shape is the number of columns and columns of the DataFrame.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

### Columns
Columns returns the name of each column within the DataFrame.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

### Index
•	The record returns the record data of the DataFrame. The file data contains the names of the columns. In case the lines have NOT named records, the record property returns a RangeIndex protest with the begin, halt, and step values.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

### Sum
•	 Returns the entirety of the values within the indicated pivot. By indicating the column hub (axis='columns'), the entirety() strategy looks column-wise and returns the whole of each push.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

### Isnull
Isnull is utilized to discover Invalid values.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

### Notnull
Notnull is utilized to discover values that are NOT Invalid.

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

### Describe
Returns a description summary for each column within the DataFrame

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)
### Mean
The average value

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

### Median
The midpoint value

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

### Mode
The most common value

![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

### Unique
Returns the min of the values within the indicated hub
![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

### Slicing
![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

## Module Random
![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

## Datetime
![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)

## File txt
![alt text](https://github.com/andhitogalih/Learn_Python_2/blob/main/public/Image/Data%20Frame.png)
