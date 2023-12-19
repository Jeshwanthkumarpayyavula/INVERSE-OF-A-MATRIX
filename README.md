# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
# Name:Jeshwanth Kumar
# Reg.No:212223240114
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 4:
End the program

## Program:
```
#To write a python program to find the inverse of a matrix
#Developed By:Jeshwanth Kumar
#Reg.no:212223240114

import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse=np.linalg.inv(a)
print(inverse)
```
## Output:
![image](https://github.com/Jeshwanthkumarpayyavula/INVERSE-OF-A-MATRIX/assets/145742402/32550d84-ce9d-4fa2-97b0-1524be37b2b4)

## Result:
Thus the inverse of given matrix is successfully solved using python program

