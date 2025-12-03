# 4a.Classes and Objects in Python: Calculate the Area of a Circle
# Name: Vembarasi.A.R
# Reg no: 212224220120
##  Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

##  Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

##  Program
```
import math

class cse:
    def mech(self, radius):
        area = math.pi * radius ** 2
        print(f"Area of circle: {area:.2f}")


r = float(input())

obj = cse()
obj.mech(r)
```

## Output
<img width="906" height="217" alt="image" src="https://github.com/user-attachments/assets/6c835aee-0159-47b5-b549-637162c1b238" />


## Result
Thus the program executed successfully.
