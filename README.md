# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:25018250
# Developed By:MAHA VISHNU S
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by:MAHA VISHNU S
RegisterNumber:25018250 
'''
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(norm1)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:MAHA VISHNU S
RegisterNumber: 25018250
'''
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")




# Infinity Norm of a Matrix
'''
Program to find infinity-norm of a matrix.
Developed by:MAHA VISHNU S
RegisterNumber: 25018250
'''
import numpy as np
A=np.array(eval(input()))
norminf=np.linalg.norm(A,np.inf)
print(f"{norminf:.2f}")





```
## Output:
### 1-Norm of a Matrix
<img width="1207" height="738" alt="ma exp 7 1" src="https://github.com/user-attachments/assets/46293ed0-ef70-448f-a31a-3172845fe35a" />
<img width="1242" height="347" alt="ma exp 7 1 ans" src="https://github.com/user-attachments/assets/a2525989-7cd6-40db-8138-770ad7839a6a" />



### 2-Norm of a Matrix
<img width="1207" height="743" alt="ma exp 7 2" src="https://github.com/user-attachments/assets/fa1ba712-d802-4b5e-b8de-db3a8f809d9e" />
<img width="1222" height="385" alt="ma exp 7 2 ans" src="https://github.com/user-attachments/assets/94cfeab0-f803-4abe-8f69-9b98d8f44a51" />



### Infinity Norm of a Matrix
<img width="1231" height="673" alt="ma exp 7 3" src="https://github.com/user-attachments/assets/b6c91be7-2843-4db9-8a76-f393723363eb" />
<img width="1232" height="357" alt="ma exp 7 3 ans" src="https://github.com/user-attachments/assets/7dacff19-f179-4917-9c1e-12a2caa49c32" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
