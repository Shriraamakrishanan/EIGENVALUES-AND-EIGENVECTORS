# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from the matrix and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.

## Program:
```python
import numpy as np
a=np.array([[2,2],[1,3]])
val,vec=np.linalg.eig(a)
print(f"Eigen values are {val} and Eigen Vectors are {vec}")
```

## Output:
![Screenshot 2025-04-27 153915](https://github.com/user-attachments/assets/f2d8494a-1a0f-430a-8ca7-a6ccf71518ad)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
