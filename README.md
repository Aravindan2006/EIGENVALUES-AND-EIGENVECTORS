# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the module numpy and assign numpy as np

Step 2:
Create an variable named 'a' and use np.array() for the matrix values by first list as first row and so on

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
Print the Eigenvalue and Eigenvector
## Program:
```py
#Program to find the eigen values and eigen vectors.
#Developed by: ARAVINDAN D
#RegisterNumber:212223240012
import numpy as np
a = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Screenshot 2024-04-15 130952](https://github.com/Aravindan2006/EIGENVALUES-AND-EIGENVECTORS/assets/151760062/85d7fb9e-11e1-4fbd-9e12-17bafab38cb7)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
