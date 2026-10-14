# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### 5(A)
1. Start the program and read the input matrix A.
2. Import the required NumPy and SciPy libraries.
3. Perform LU decomposition to obtain the L and U matrices.
4. Display the L and U matrices and stop the program.
### 5(B)
1. Start the program and read the coefficient matrix A and vector B.
2. Import the required NumPy and SciPy libraries.
3. Perform LU decomposition and solve the system of linear equations using the decomposed matrices.
4. Display the solution vector X and stop the program.

### Program:
### 5(A) To find the L and U matrix
### Program to find the L and U matrix.
### Developed by: keerthi.V
### RegisterNumber: 26010139
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### from scipy.linalg import lu
### a=np.array(eval(input()))
### P,L,U=lu(a)
### print(L)
### print(U)


#5(B) To find the LU Decomposition of a matrix 
### Program to find the L and U matrix.
### Developed by: keerthi.V
### RegisterNumber: 26010139
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### from scipy.linalg import lu_factor,lu_solve
### a=np.array(eval(input()))
### b=np.array(eval(input()))
### l,p=lu_factor(a)
### x=lu_solve((l,p),b)
### print(x)


## Output:
#5(A)
<img width="782" height="795" alt="image" src="https://github.com/user-attachments/assets/ae19bbd3-649e-4a8f-a06a-6873a1dc045c" />

#5(B)
<img width="751" height="818" alt="image" src="https://github.com/user-attachments/assets/c3699926-bee8-4fb8-98b8-09bd6c347c45" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

