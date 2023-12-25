# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import nmpy as np
### Step 2:
define the matrix A
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
print the result in output using print() function

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: pavithra p
#RegisterNumber:23007232

import numpy as np
A=[[2,2],[1,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![image](https://github.com/23007232/EIGENVALUES-AND-EIGENVECTORS/assets/139115574/cac0bacd-46d9-4268-b935-2bbc03cfbed1)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
