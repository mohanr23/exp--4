# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from the given matrix and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: END the progrram


## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MOHAN R 
#RegisterNumber:212224230168
import numpy as np

A = np.array([
    [2, -3, 0],
    [2, -5, 0],
    [0,  0, 3]
])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```

## Output:


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
