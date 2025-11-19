# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Take the matrix A.
### Step 2: 
Find eigenvalues of A and Find eigenvectors for each eigenvalue.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
Display eigenvalues and eigenvectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Sivasakthi S
#RegisterNumber:25017123
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="1920" height="1200" alt="Exp-4" src="https://github.com/user-attachments/assets/2298598a-2566-4746-b8ab-dce69ab92168" />
<img width="1920" height="1200" alt="Exp4" src="https://github.com/user-attachments/assets/b65674d7-07c2-4ebe-9bea-87656cad236e" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
