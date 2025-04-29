# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  

To write a Python program that prints a right-angled triangle pattern of asterisks (*) based on the number of rows entered by the user.

### ALGORITHM

Start the program.
Input the number of rows n from the user.
Define a function pattern(n) to print the pattern.
Use an outer loop from i = 1 to i = n (inclusive) to iterate over each row.
Within the outer loop, use an inner loop from j = 0 to j < i to print i asterisks in the current row.
After printing each row of asterisks, move to the next line using print().
Call the function with the user input value n.
End the program.

---

### PROGRAM
```
#Add Your Code Here
def pattern (n):
    for i in range(1, n+1):
        for j in range(i):
            print('*', end=' ')
        print()
        
n = int(input(""))        
pattern(n)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/6b18eb68-b93f-40ea-8ab1-805b66a30640)

### RESULT
Thus the program LOOPING PATTERNS - PRINTING PATTERN have been executed and verified sucessfully
