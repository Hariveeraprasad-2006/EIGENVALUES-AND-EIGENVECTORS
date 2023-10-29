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
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:A.Hari Veera Prasad 
#RegisterNumber:23009466
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {0} and Eigen Vectors are {1}".format(values,vectors))
```
## Output:
![eigen values and eigen vectors](https://github.com/Hariveeraprasad-2006/EIGENVALUES-AND-EIGENVECTORS/assets/145049988/9aeb2932-1c8e-4a51-9732-32d3e8ad8364)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
