# RANK-OF-A-MATRIX
# Name: DEEPADHARSHINI T
# Reg no: 212224230052
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Read the matrix.
### Step 2:Convert the matrix into row echelon form using row operations.
### Step 3:Count the number of non-zero rows.
### Step 4:That count is the rank of the matrix. 
## Program:
```
import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A) 
print(rank)
```
## Output:

<img width="1277" height="195" alt="image" src="https://github.com/user-attachments/assets/b68eceb5-33e5-48e1-871c-a40e43f4474c" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
