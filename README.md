# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Form the characteristic equation of A by using:  ∣A−λI∣=0 
### Step 2: 
Solve the characteristic equation to get the Eigenvalues (λ values).
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End The Program
## Program:
### _Program to find the eigen values and eigen vectors._

### _Developed by:VAIDEESHWARAN G_

### _RegisterNumber: 25011798_
```
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
evl,evc=np.linalg.eig(A)
print(f"Eigen values are {evl} and Eigen Vectors are {evc}")
```
## Output:

<img width="1920" height="1080" alt="Screenshot 2025-11-23 183005" src="https://github.com/user-attachments/assets/13cc203f-0fe5-4a57-9f3e-b94610454b46" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
