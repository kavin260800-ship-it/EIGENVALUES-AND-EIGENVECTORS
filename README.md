# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

### Step 2: import numpy as np
a=np.array([[2,2],[1,3]])
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Program:<img width="944" height="581" alt="{97A74FA8-4D8D-458D-8FB0-FFC112BB86FD}" src="https://github.com/user-attachments/assets/f4cf6249-9f37-4fad-89cc-1279eb36bcf7" />


## Output:<img width="1394" height="450" alt="{037BB5EE-188C-48D9-ABCE-9B8B29A2D2DC}" src="https://github.com/user-attachments/assets/6989f0fe-089c-42ab-9ec0-53463b360331" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
