# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of matrix.

## ALGORITHM:
### Step 1:
Use import numpy as np.

### Step 2:
Enter the input.

### Step 3:
Use for loop and range.

### Step 4:
Use np.linalg.inv() to find inverse of matrix.

### Step 5:
print()


## PROGRAM:
```python
import numpy as np
l1,l2=[],[]
n1,n2=int(input()),int(input())
for i in range (n1):
    for j in range (n2):
       values=int(input())
       l1.append(values)
    l2.append(l1)
    l1=[]
print(l2)
matrix=np.array(l2)
inverse=np.linalg.inv(matrix)
print(inverse)
```

## OUTPUT:
![output](https://github.com/Hemapriya-2004/Inverse-of-matrix/blob/main/h2.PNG?raw=true)

## RESULT:
Thus the program is written to find the matrix.
