# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program
### Step 2: 
Initialize the matrix in the form of nested list.
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SETHUKKARASI C
#RegisterNumber:23012881
import numpy as n
a=[[2,-3,0],[2,-5,0],[0,0,3]]
val,vec=n.linalg.eig(a)
print("Eigen values are",val,"and Eigen Vectors are",vec)
```
## Output:
![output](/EIGENVALUES-AND-EIGENVECTORS/eigen_output.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
