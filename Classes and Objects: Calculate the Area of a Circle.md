# Classes and Objects in Python: Calculate the Area of a Circle

## Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## Program
```
class cse:
    def __init__(self,radius):
        self.radius=radius
        
        
    def mech(self):
        area=3.1416*pow(self.radius,2)
        print("Area of circle: {:.2f}".format(area))
        

radius=float(input())
circle=cse(radius)

circle.mech()
    
```

## Output
![image](https://github.com/user-attachments/assets/ab5ee455-95fe-4954-bee2-33eacbb44ad6)


## Result
Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation is successfully executed.
