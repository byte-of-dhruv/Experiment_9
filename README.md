# Aim of Experiment: Tools for EDA- Study of Numpy library
Dhruv Verulkar
25070123162
# Theory:
NumPy (Numerical Python) is a fundamental library for scientific computing in Python.   
It provides powerful data structures, primarily the ndarray (n-dimensional array) object, and a rich collection of routines for 
performing operations on these arrays.  

1. Array Creation: - Demonstrates how to create NumPy arrays from Python lists (np.array()).  
                   - Creates a Numpy array from a Python list or tuple using np.array().  
                   eg.import numpy as np  
                   a = np.array([1, 2, 3, 4])
   
2. Indexing and Slicing: Access or extract specific elements or parts of an array.  
Indexing Syntax : - array[index] & array[row_index, column_index]  
Slicing Syntax :  - array[start : end : step]  
eg.a[0]  # first element  
a[1:3]  # slicing  
a[-1]  # last element

3. Mathematical Operations: Performs element-wise arithmetic operations on arrays.  
Functions:  
np.add() – Adds corresponding elements of two arrays.  
np.subtract() – Subtracts elements of one array from another element-wise.  
np.multiply() – Multiplies corresponding elements of two arrays.  
np.divide() – Divides elements of one array by another element-wise.

4. Dimension of array-Returns number of dimensions (axes) using ndim.   
ndim: The number of dimensions (axes) of the array (e.g., 1 for a vector, 2 for a matrix).  
eg.import numpy as np   
a = np.array([[1,2,3],[4,5,6]])    
print(a.ndim)

5. size: The total number of elements in the array.  
eg.a = np.array([[1,2,3],[4,5,6]])  
print(a.size)  

6. shape: A tuple indicating the size of the array in each dimension using array.shape command.  
eg.import numpy as np
a = np.array([[1,2,3],[4,5,6]])  
print(a.shape)  

7. dtype: The data type of the elements in the array (e.g., int64, float64) using commnad array.dtype.  
eg.import numpy as np  
a = np.array([1,2,3,4])  
print(a.dtype)   
 
## In-built Array Creation Functions: NumPy provides convenient functions to create special arrays.  
np.zeros((rows, cols)): Creates an array filled with zeros.  
np.ones((rows, cols)): Creates an array filled with ones.  
np.eye(size): Creates an identity matrix (a square matrix with ones on the main diagonal and zeros elsewhere).  
np.arange(start, stop, step): Generates an array with evenly spaced values within a given interval (similar to Python's range()).  
np.linspace(start, stop, num): Generates an array with a specified number of evenly spaced values over a given interval.   

## Descriptive Statistics: NumPy offers various functions to quickly compute statistical properties of arrays, which are crucial for summarizing data in EDA.   
np.mean(): Calculates the arithmetic mean of array elements.  
np.median(): Calculates the median of array elements.  
np.sum(): Calculates the sum of array elements.  
np.max(): Finds the maximum value in the array.  
np.min(): Finds the minimum value in the array.  

## Applications of Numpy Library In EDA:
a)Statistical Analysis of Data:
NumPy provides functions like np.mean(), np.median(), np.std(), and np.sum() to calculate statistical measures of datasets.
These functions help understand the central tendency and variability of the data during exploratory data analysis.

b)Handling and Cleaning Data:
NumPy functions such as np.isnan() and np.where() help identify missing values and filter or replace incorrect data.

## Conclusion:
This experiment provides a foundational understanding of how to use NumPy for basic array manipulation and statistical computations, which are essential first steps in any data analysis workflow.
