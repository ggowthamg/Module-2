# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM

1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
#Add your Code Here
def perfect_num(n):
    a = sum(i for i in range (1, n) if n%i == 0)
    return a == n
    
if __name__ == '__main__':
    n = int(input())
    if perfect_num(n):
        print('The number is a Perfect number!')
    else :
        print('The number is not a Perfect number!')

```
### OUTPUT
![image](https://github.com/user-attachments/assets/d040d355-75ae-414d-832e-3dcd29a8e3ed)

### RESULT
Thus the program PERFECT NUMBER have been executed and verified sucessfully
