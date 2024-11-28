# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy library.
### Step 2: Convert the 1-D matrix into 2-D array.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalue and eigenvector.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Yuvaram S
#RegisterNumber:24900232

import numpy as np
A=np.array([[2,2],[1,3]])
value,vector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(value,vector))
```
## Output:
![Screenshot 2024-11-28 210936](https://github.com/user-attachments/assets/af1e38e6-6e65-4e29-abcd-bccf699e7d2f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
