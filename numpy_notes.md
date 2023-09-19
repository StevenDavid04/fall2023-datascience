# Intro to NumPy
NumPy is a popular Python library for numerical and scientific computing. It provides support for working with arrays and matrices of data, as well as a variety of mathematical functions to operate on these arrays. The following is just a basic introduction to NumPy.

## NumPy Functions
Before you can use it, you need to import NumPy into your python script.

```python
import numpy as np
```
## Creating NumPy Arrays
NumPy arrays are similar to Python lists but can have multiple dimensions 

#### 1D NumPy Array
```python
arr = np.array([1, 2, 3, 4, 5])
print(arr)
```


#### 2D NumPy Array
```python
matrix = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
print(matrix)
```

## Array Atrributes
These arrays have various attributes that provide information about said array

```python
print(arr.shape)      # Prints the shape of the array
print(arr.size)       # Prints the number of elements in the array
print(arr.dtype)      # Prints the data type of the elements in the array
```

## Basic Array Operations
```python
a = np.array([1, 2, 3])
b = np.array([4, 5, 6])

# Addition
result = a + b

# Subtraction
result = a - b

# Multiplication
result = a * b

# Division
result = a / b
```

## Array Indexing and Slicing
Access elements and slices of NumPy arrays just like you would with Python lists
```python
arr = np.array([1, 2, 3, 4, 5])

print(arr[0])          # Access the first element
print(arr[1:4])        # Slice from index 1 to 3 (exclusive)
```

## NumPy Functions
Examples on how NumPy provides a wide range of mathematical and statistical functions to operate on arrays
```python
arr = np.array([1, 2, 3, 4, 5])

# Mean of the array
mean = np.mean(arr)

# Sum of the array
sum = np.sum(arr)

# Maximum and minimum values
max_value = np.max(arr)
min_value = np.min(arr)
```
