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
class Circle:
    def __init__(self, radius):
        self.radius = radius
    def area(self):
        return 3.1416 * self.radius * self.radius
r = float(input())
c = Circle(r)
print("Area of circle:", round(c.area(), 2))
```

## Output

<img width="793" height="178" alt="image" src="https://github.com/user-attachments/assets/066111d0-e9af-45e5-9d3d-c75cd7901137" />


## Result
Thus the program executed successfully.
