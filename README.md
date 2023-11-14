# Algorithm for QR Decomposition
## Aim:
To implement QR decomposition algorithm using the Gram-Schmidt method.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Intialize the matrix Q and u
2.	The vector u and e is given by

    ![eqn1](./ex4.jpg)

    ![eqn2](./ex6.jpg)

    ![eqn3](./ex3.jpg)

3.	Obtain the Q matrix   
    ![eqn4](./ex1.jpg)
4.	Construct the upper triangular matrix R
    ![eqn5](./ex2.jpg)



## Program:
### Gram-Schmidt Method
```
# Register No: 212222243003
# Developed By: praveen ck
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output
## 1-Norm of a Matrix
![Screenshot 2023-11-14 194728](https://github.com/praveenck23009864/QRdecomposition/assets/141472050/defdd305-7cd8-4d8d-9879-214c0a6e29ce)
## 2-Norm of a Matrix
![Screenshot 2023-11-14 194747](https://github.com/praveenck23009864/QRdecomposition/assets/141472050/449b2558-a350-452d-b5bd-ecce204a1743)
## 3-Infinity Norm of a Matrix
![Screenshot 2023-11-14 194817](https://github.com/praveenck23009864/QRdecomposition/assets/141472050/7e158881-43a8-40a7-8e92-d0e8de00d93e)





## Result
Thus the QR decomposition algorithm using the Gram-Schmidt process is written and verified the result.
