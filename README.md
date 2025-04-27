# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step :  python program to find the inverse of the given matrix
### Step 1 : Input the square matrix \( A \).  
### Step 2 : Augment \( A \) with the identity matrix to form \([A | I]\).
### Step 3 : Perform row reduction to transform \( A \) into the identity matrix.  
### Step 4 : Extract the inverse \( A^{-1} \) from the transformed matrix.  

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Tharun.V
#RegisterNumber:212224230290

import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
b=np.linalg.inv(a)
print(b)
```
## Output:
![Screenshot 2025-04-22 231512](https://github.com/user-attachments/assets/5552dbca-9538-4910-b35c-8d60e49f89c3)

## Result:
Thus the inverse of given matrix is successfully solved using python program.

