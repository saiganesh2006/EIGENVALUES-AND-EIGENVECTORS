# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the  numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Depuru Bhargava Venkata Sai Ganesh
#RegisterNumber:23009248
import numpy as np
a=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![Screenshot 2023-11-10 095903](https://github.com/saiganesh2006/EIGENVALUES-AND-EIGENVECTORS/assets/145742342/efd375da-f0fd-4497-85b5-f3b8783797fb)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
