# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the NumPy module to use built-in functions for matrix operations.

### Step 2:
Create a list of lists to represent the matrix and convert it into a NumPy array using np.array().

### Step 3:
Use the np.transpose() function or .T attribute to find the transpose of the given matrix.

### Step 4:
Display the transposed matrix.

### Step 5:
End the program.



## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: THARRUN D
#RegisterNumber:212224240170

import numpy as np


matrix = np.array([[2, 2],
                   [1, 3]])


eigenvalues, eigenvectors = np.linalg.eig(matrix)

print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")

```

## Output:

![Screenshot 2025-05-16 221342](https://github.com/user-attachments/assets/c5505068-3051-4fcb-9827-2e85cabdae55)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
