# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : Import numpy module to use the built-in functions for calculations

### Step 2: Use py.array() to create list from the given equations

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: Run the program to get the output

## Developed by : N.PRAVESH
## Register no : 212223230154

## Program:

```python

#Program to find the eigen values and eigen vectors.
#Developed by: N.PRAVESH
#RegisterNumber: 212223230154

import numpy as py
a = py.array([[2,2],[1,3]])
eigenvalues,eigenvectors = py.linalg.eig(a)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)

```

## Output:

![Screenshot 2024-04-10 190551](https://github.com/NPravesh2005/EIGENVALUES-AND-EIGENVECTORS/assets/164477756/3291a84d-6dbd-45c3-9c97-bf862e9d5820)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
