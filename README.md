# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance between two 2 points
## ALGORITHM:
### Step 1: 
Import the math module for mathematical functions.
### Step 2: 
Define the coordinates of two points: 'x1, y1 = 10, 6' and 'x2, y2 = 4, 2'. 
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Format the distance as a floating-point number: 'e = "{:.2f}".format(d)'.
### Step 5: 
Print the formatted distance
## PROGRAM:
```
#Program to find the distance between two points.
#Developed by: Gnanendran N
#RegisterNumber: 23006661
import math
x1,y1=10,6
x2,y2=4,2
d=math.sqrt((x2-x1)**2+(y2-y1)**2)
e="{:.2f}".format(d)
print(e)
```
## OUTPUT:
![output](/distance.png)
## RESULT:
Thus finding the distance between two points is successfully executed
