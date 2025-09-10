# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE

---

### AIM  
To write a Python program to take the radius from the user and find the area of a circle using the class name `umbrella` and function name `rain`.

---

### ALGORITHM

1. Begin the program.  
2. Create a class named `umbrella`.  
3. Define a method `rain(self, r)` inside the class `umbrella` that accepts a radius `r` as an argument.  
4. Inside the `rain` method:  
   - Calculate the area of a circle using the formula:  
     \[ \text{Area} = \pi \times r^2 \]  
   - Use the `math.pi` constant to get the value of π and perform the calculation.  
   - Print the result, formatted to two decimal places.  
5. Prompt the user for an integer input to represent the radius of the circle.  
6. Create an instance of the `umbrella` class and store it in the variable `u`.  
7. Call the `rain` method of the `umbrella` class, passing the user-provided radius `r` as an argument.  
8. Terminate the program.

---

### PROGRAM

```
# Reg.No-212223060072
# Name-Gowri.M

import math

class Pen:
    def stationary(self, radius):
        area = math.pi * radius * radius
        print(f"Area of circle: {area:.2f}")

radius = float(input())
p = Pen()
p.stationary(radius)


```

### OUTPUT
<img width="740" height="198" alt="{91019AB2-7885-4823-B003-DAE6EE6DEDC1}" src="https://github.com/user-attachments/assets/3972b4aa-2e8e-4989-947b-6d363a83fb97" />

### RESULT
Thus the program to take the radius from the user and find the area of a circle has been implemented and executed successfully.


