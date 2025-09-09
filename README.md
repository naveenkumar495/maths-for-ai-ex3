# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Find the determinant of the matrix. If it is 0, the matrix has no inverse.
### Step 2: Find minors and cofactors for every element of the matrix. 
### Step 3: Make the adjoint by taking the transpose of the cofactor matrix.
### Step 4: Divide the adjoint by the determinant to get the inverse.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Naveenkumar M
#RegisterNumber:212224230183
import numpy as np
matirxA = np.array([[6,2,3],[3,1,1],[10,3,4]])
inverse = np.linalg.inv(matirxA)
print(inverse)
```
## Output:
<img width="1218" height="904" alt="Screenshot 2025-09-09 132317" src="https://github.com/user-attachments/assets/fb0e272b-d678-46b0-a4b6-9a3fd42b5962" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

