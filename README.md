# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:DIVYA.K
#RegisterNumber:212222230035

import numpy as np
from numpy.linalg import eig
a=np.array([[2,2],[1,3]])
w,v=eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(w,v))
```


## Output:

![Screenshot_20230327_093335](https://user-images.githubusercontent.com/119393621/228007486-1059a13b-63e0-4ba2-a691-8cad96e36bc6.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
