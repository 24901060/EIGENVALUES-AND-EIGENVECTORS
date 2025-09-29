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
#Program to find the eigen values and eigen vectors.
#Developed by: Praveen S
#RegisterNumber: 212224230206
import numpy as np
matrix = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eign_values,eign_vector = np.linalg.eig(matrix)
print(f"Eigen values are {eign_values} and Eigen Vectors are {eign_vector}")
## Output:
<img width="1334" height="964" alt="image" src="https://github.com/user-attachments/assets/8a4f4cbf-f29a-4a54-bd00-ff5ad94621e7" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
