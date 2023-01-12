# COT-4500-Intro
Intro to Python and GitHub Assignment 

import numpy as np  // NumPy is a library in Python that is used for scientific computing and supports  functions to deal with N-dimensional array objects
 
arr = np.array([[1, 0, 0,],
                [0, 1, 0,],
                [0, 0, 1,]]) // i = row and j = column, specific 3x3 matrix where a cell is 1 if i == j, else 0 
                
arr2 = np.array([[1, 3, 3],
                 [3, 1, 3],
                 [3, 3, 1]]) // the same 3x3 matrix from arr, however everyone cell that is not i = j equals 3
                 
arr3 = np.array([[1, 3],
                 [3, 1],
                 [3, 3]]) // delete the last column from the previous matrix 
print(arr)  
print(arr2)
print(arr3) // print all three matrixes at the same time 
 
