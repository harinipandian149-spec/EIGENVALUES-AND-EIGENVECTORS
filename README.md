# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: import numpy as np 
### Step 2: create "a" variable and store the given matrix as np.aarray  
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: run the program

## Program:
### Program to find the eigen values and eigen vectors.
### Developed by: Harini P 
### RegisterNumber: 26008597
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
### values,Vectors=np.linalg.eig(a)
### print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

## Output:
<img width="1403" height="520" alt="Screenshot 2026-10-13 153054" src="https://github.com/user-attachments/assets/ea7d595e-46f5-43ce-a595-7cbf0d4d44db" />



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
