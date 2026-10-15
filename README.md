# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Importing Numpy Module.
### Step 2: Creating the Given Array using np.array function.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Printing the Rank of the matrix.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Sre Vishnu Priyar L N
#RegisterNumber: 26009605

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[1,2,3],[3,6,9]])
sol=np.linalg.matrix_rank(A)
print(sol)
```
## Output:
<img width="1530" height="942" alt="image" src="https://github.com/user-attachments/assets/9c8c7f10-6a80-4706-9401-277824ac918c" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

