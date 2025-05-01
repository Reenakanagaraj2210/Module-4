# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```
import math

class CSE:
    def mech(self, radius):
        area = math.pi * radius * radius
        return area

r = float(input())
obj = CSE()
area = obj.mech(r)
print("Area of circle:", round(area, 2))
```

## Output
![Screenshot 2025-05-02 010501](https://github.com/user-attachments/assets/c2d9f029-10d1-43c7-9101-d405c8b00b92)

## Result
Thus,the given program is executed successfully.
