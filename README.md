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
Python
# Register No:25012185
# Developed By:Rohith s
# 1-Norm of a Matrix
~~~
import numpy as np
a=np.array(eval(input()))
x=np.linalg.norm(a,1)
print(x)
~~~
# 2-Norm of a Matrix
~~~
import numpy as np
a=np.array(eval(input()))
x=np.linalg.norm(a,2)
print("{:.2f}".format(x))
~~~
# Infinity Norm of a Matrix
~~~
import numpy as np
a=np.array(eval(input()))
x=np.linalg.norm(a,np.inf)
print(x)
~~~

## Output:
### 1-Norm of a Matrix

<img width="1244" height="230" alt="Screenshot 2025-12-23 185118" src="https://github.com/user-attachments/assets/6594e677-ddfe-4cd7-b12d-fe61cdf621bd" />

### 2-Norm of a Matrix

<img width="1231" height="308" alt="Screenshot 2025-12-23 185059" src="https://github.com/user-attachments/assets/8e5c95d5-ca16-4537-9be0-d624cdadf458" />

### Infinity Norm of a Matrix

<img width="1228" height="233" alt="Screenshot 2025-12-23 185040" src="https://github.com/user-attachments/assets/b622a371-27a9-49be-b025-0b9b5c117dce" />

## Result
  Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
