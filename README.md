# Task9-NumPy-Array-Creation-and-Data-Types
Overview
This task explores how to create NumPy arrays and understand their shape, dimensions, size, data types, and basic numerical operations.
Objectives
Create one-dimensional and two-dimensional NumPy arrays.
Explore array attributes: shape, ndim, size, and dtype.
Perform basic numerical operations.
Compare NumPy arrays with Python lists.
Tools Used
Python
NumPy
Jupyter Notebook
Example
import numpy as np

arr1 = np.array([10, 20, 30, 40])
arr2 = np.array([[1, 2, 3], [4, 5, 6]])

print("1D Array:", arr1)
print("2D Array:\n", arr2)
print("Shape:", arr2.shape)
print("Dimensions:", arr2.ndim)
print("Size:", arr2.size)
print("Data type:", arr2.dtype)

print("Addition:", arr1 + 5)
print("Multiplication:", arr1 * 2)
Learning Outcome
Learned the basics of NumPy array creation, array attributes, and numerical operations used in data science.
