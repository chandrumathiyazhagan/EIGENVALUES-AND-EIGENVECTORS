# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Get the input matrix from the user
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: M.CHANDRU
#RegisterNumber:212222230026
import numpy as np
A=np.array([[4,2],[2,4]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector)) 
```
## Output:
![ma4](https://user-images.githubusercontent.com/119393023/226389844-eea98faf-0933-4868-875e-29460600ea27.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
