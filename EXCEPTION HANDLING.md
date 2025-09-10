# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create a Python program that prompts the user for a list of grades separated by commas, splits the string into individual grades, and uses exception handling to inform the user if the values they entered cannot be converted to integers.

---

### ALGORITHM

1. Begin the program.  
2. Read a string `input_str` from the user using `input()`.  
3. Split the input string using commas (`,`) to create a list of grades.  
4. Use a `try` block to attempt converting each item in the grades list to an integer and store the result in `l1`.  
5. If the conversion is successful, print the list `l1` containing the integer values.  
6. If an error occurs during conversion (for example, if the input is not a valid number), catch the exception and print an error message: `"The grades you entered were in an invalid format."` along with the original grades list.  
7. Terminate the program.

---

### PROGRAM

```
Reg.No-212223060072
Name-Gowri.M

grades_input = input()
grades_list = grades_input.split(',')
try:
    grades = [int(grade.strip()) for grade in grades_list]
    print(grades)
except ValueError:
    print("Please enter only valid integers separated by commas.")
```

### OUTPUT
<img width="819" height="151" alt="{AB0FE98A-21F1-4233-B322-DE1A41DBA188}" src="https://github.com/user-attachments/assets/8ee70732-c5dc-468d-923e-edba9fa2f924" />

### RESULT
Thus the program prompts the user for a comma-separated list of grades, splits them, and handles exceptions if they can't be converted to integers has been implemented and executed successfully.
