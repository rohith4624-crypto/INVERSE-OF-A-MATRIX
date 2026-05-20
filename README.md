# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Write a python program for the given matrix.

### Step 2: Using numpy library.
### Step 3:  Using linalg.inv(),we can get the inverse of the matrix.
### Step 4: Run the program and get the output.

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a = np.array([[6,2,3],[3,1,1],[10,3,4]])
b = np.linalg.inv(a)
print(b)
```
## Output:
<img width="472" height="721" alt="Screenshot 2026-05-20 135907" src="https://github.com/user-attachments/assets/fccba4e2-0d31-4430-96a5-109dd1b40a8e" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

