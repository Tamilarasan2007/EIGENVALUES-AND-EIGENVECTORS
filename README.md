# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library to perform matrix operations.
### Step 2: Define the given matrix using a NumPy array.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigenvalues and eigenvectors in the required format.

## Program:
```
import numpy as np

A = np.array([[4, 2],[2, 4]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```

## Output:![alt text](<Screenshot 2026-02-19 084653.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
