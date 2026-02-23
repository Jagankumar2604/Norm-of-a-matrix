# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()
2.  Find the 1-norm of the matrix using np.linalg.norm()
3. Find the 2-norm of the matrix using np.linalg.norm()
4.  Find the infinity norm of the matrix using np.linalg.norm()
5. Print the norm of the matrix in two decimal places.
## Program:
# Register No:212225100018
# Developed By:Jagan Kumar V

# 1-Norm of a Matrix
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```




# 2-Norm of a Matrix
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# Infinity Norm of a Matrix
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
<img width="1181" height="801" alt="image" src="https://github.com/user-attachments/assets/d20f0da2-9b1c-4e1c-828d-156b0247f2b1" />
### 2-Norm of a Matrix
<img width="1232" height="780" alt="image" src="https://github.com/user-attachments/assets/8bc519ee-52c3-4a40-89b5-a688a9d1ffd8" />
### Infinity Norm of a Matrix
<img width="1190" height="797" alt="image" src="https://github.com/user-attachments/assets/6d1a4dcd-115a-4cfa-9f90-919589b97410" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
