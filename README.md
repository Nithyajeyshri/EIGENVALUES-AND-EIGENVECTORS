# EIGENVALUES-AND-EIGENVECTORS

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1: Import NumPy library for matrix operations.

### Step2: Define the matrix using np.array().

### STep3: Use np.linalg.eig() to compute both eigenvalues and eigenvectors of the matrix.

### Step4: Print the results to display eigenvalues and eigenvectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: NITHYA JEY SHRI S S
#RegisterNumber: 212225040288

import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eigen_value,eigen_vector=np.linalg.eig(matrixA)
print("Eigen values are",eigen_value ,"and Eigen Vectors are",eigen_vector)
```
## Output:
<img width="1476" height="816" alt="Screenshot 2026-05-01 134323" src="https://github.com/user-attachments/assets/314a7f74-2bfa-4848-b8aa-12485d788c3a" />
<img width="1483" height="467" alt="image" src="https://github.com/user-attachments/assets/afabf7e6-71a4-42b4-a499-b6778088f959" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
