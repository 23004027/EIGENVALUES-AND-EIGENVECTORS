# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Algorithm:
### Step1 :
Import the numpy module to use the built-in function for calculation.

### Step 2:
prepare the listfrom each linear equation and assign in np.array()

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program.
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by:vignesh.v 
#RegisterNumber:23004027

import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![EXM4](https://github.com/23004027/EIGENVALUES-AND-EIGENVECTORS/assets/138956447/9583cdcd-73a4-4db0-8448-7867eb7fda80)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
