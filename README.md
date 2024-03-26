# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: S LALIT CHANDRAN
#RegisterNumber:212223240077

import numpy as np
a= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors =np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/lalitchandran/EIGENVALUES-AND-EIGENVECTORS/assets/137707725/cafd158e-0fdf-4b83-bb9e-54c7ce8d5782)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
