# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import numpy,which provides efficient method to work with matrix and compute their ranks
### Step 2: Create a matrix to find the rank.You can define as list or lists or numpy array
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
``````
#Program to find the rank of a matrix.
#Developed by: KAAVIYAN.K
#RegisterNumber: 24006507
import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
rank=np.linalg.matrix_rank(a)
print(rank)
``````
## Output:
![Screenshot 2025-04-26 104135](https://github.com/user-attachments/assets/b0891e0a-d057-4947-814b-11a140f53a4f)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.




