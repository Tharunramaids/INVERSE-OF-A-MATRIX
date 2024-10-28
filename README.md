# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the build-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.inv(),we can find the solution
### Step 4: 
End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:Tharun R
#RegisterNumber:24005919
import numpy as np
matrix = [[1, 0, 3],
          [-1, 2, -2],
          [2, 3, -1]]
matrix_np = np.array(matrix)
inverse = np.linalg.inv(matrix_np)
print(inverse)

```
## Output:
![alt text](<exp 03 output.png>)

## Result:
Thus the inverse of given matrix is successfully solved using python program

