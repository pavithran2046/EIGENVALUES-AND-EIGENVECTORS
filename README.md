# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy module to use the built-in function for calculation
### Step 2: 
prepare list from each linear equation and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program

## Program:
``` python
#Program to find the eigen values and eigen vectors.
#Developed by: pavithran
#RegisterNumber: 23001643
import numpy as np
a=[[4,2],[2,4]]
b=np.array(a)
values,vectors=np.linalg.eig(b)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![output](/Screenshot%202023-07-26%20181453.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
