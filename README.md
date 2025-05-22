# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
3. 	## ALGORITHM
### Step 1:
Import the NumPy module to perform matrix operations.
import numpy as np

### Step 2:
Create a list of lists to represent the matrix.
Convert the list into a NumPy array using np.array().

### Step 3:
Use the np.sum() function to calculate the sum of all elements in the matrix.

### Step 4:
Display the original matrix and the computed sum.

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
