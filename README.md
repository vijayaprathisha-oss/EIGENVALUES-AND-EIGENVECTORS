# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 : Start the program.
Step 2: Input a square matrix.
Step 3: Compute eigenvalues and eigenvectors using a mathematical method (e.g., NumPy linalg.eig()).
Step 4: Display the eigenvalues and eigenvectors, then stop the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: VIJAYAPRATHISHA J
#RegisterNumber:212225240184
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```
## Output:
<img width="1450" height="1224" alt="image" src="https://github.com/user-attachments/assets/d07fe8a5-4bc2-4806-914e-e0d05bb56f11" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
