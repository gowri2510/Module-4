# Exp.No:16  
## DICTIONARY - SIZE OF DICTIONARY

---

### AIM  
To write a Python program to print the size of a dictionary using `getsizeof()` from the `sys` module.

---

### ALGORITHM

1. Begin the program.  
2. Import the `sys` module to use the `getsizeof()` function.  
3. Define the dictionaries with key-value pairs (`dic1`, `dic2`, `dic3`).  
4. Use `sys.getsizeof()` to calculate the memory size of each dictionary.  
5. Print the size of each dictionary in bytes.  
6. Terminate the program.

---

### PROGRAM

```
#Reg.No-212223060072
#Name-Gowri.M
#Add Your Code Here
import sys
dic1 = {"A": 1, "B": 2, "C": 3}
dic2 = {"saveetha": "Raju", "sec": "Nikhil", "Geek3": "Deepanshu"}
dic3 = {1: "Lion", 2: "Tiger", 3: "Fox", 4: "Wolf"}

print("Size of dic1:", str(sys.getsizeof(dic1)) + " bytes")
print("Size of dic2:", str(sys.getsizeof(dic2)) + " bytes")
print("Size of dic3:", str(sys.getsizeof(dic3)) + " bytes")



```
### OUTPUT
<img width="560" height="209" alt="{AEAF8FC4-E212-423A-B412-309F6D1F04CC}" src="https://github.com/user-attachments/assets/4e647c84-aab6-449d-b098-a26d95ef6444" />

### RESULT
Thus the program to print the size of a dictionary using getsizeof() from the sys module has been implemented and executed successfully.
