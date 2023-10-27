# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Identify the coordinates of the two points
### Step 2: 
The coordinate two points are (x1,y1) and (x2,y2)
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Calculate the difference between (x2-x1) and (y2-y1)
### Step 5: 
Square each of these difference and add the squared difference
### step 6:
Take the square root of the sum


### PROGRAM:
``````
# Program to find the distance between two points.
# Developed by: ARCHANA.T
# RegisterNumber:23014066
import math
def calculate_distance(x1,y1,x2,y2):
    distance = math.sqrt((x2-x1)**2+(y2-y1)**2)
    return distance
x1,y1 = 4,2
x2,y2 = 10,6
distance = calculate_distance(x1,y1,x2,y2)
print("{:.2f}".format(distance))

``````

### OUTPUT:

![Alt text](<Screenshot 2023-10-27 08175.png>)



### RESULT:
Thus the distance between two points are succesfully executed
