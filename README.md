# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a matrix.

## ALGORITHM:
### Step 1:
Use import as np.
### Step 2:
Enter the input.
### Step 3:
Use for loop and range.
### Step 4:
Use np.linalg.inv() to find inver of a matrix.
### Step 5:
Print()


## PROGRAM:
```python
##Developed by: yuvabharathi.b
##RegisterNumber: 22002787

import numpy as np
l1, l2 = [],[]
r,c= int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)   
value1= np.array(l2)
inverse = np.linalg.inv(value1)
print(inverse)
```

## OUTPUT:
![Screenshot from 2022-10-06 11-55-08](https://user-images.githubusercontent.com/113497333/194229658-2f70b0ea-bd89-418c-90c1-1544d65bd118.png)


## RESULT:
Thus the program is written to find the matrix.
