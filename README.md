## DATE:
## Ex No 7 - Norm of a matrix
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
```
Python
# Register No: 212223230012
# Developed By: AMALJOSH MAADHAV J
```
### 1-Norm of a Matrix
```

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)

```



### 2-Norm of a Matrix
```

import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)

```



### Infinity Norm of a Matrix

```

import numpy as np
mat=np.array(eval(input()))

norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))

```




## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/a580ec7a-9f38-4cd2-9831-704e6c1ac26a)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/a15b02b8-9d27-46ae-a72e-ca738c81aa92)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/b7f10e80-bf47-4fd5-9bae-053bbf64ffed)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
