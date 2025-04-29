# Exp. No: 2a  
## ITERATIVE STATEMENTS – PRINTING N NATURAL NUMBERS

###  Aim
To create a Python program for printing `n` natural numbers using a `for` loop.

---

###  Algorithm

1. Begin the program.
2. Use `input()` to read the value of `n` (the upper limit) from the user.
3. Convert the input to an integer.
4. Display the message **"Natural Numbers are :"**.
5. Use a `for` loop to iterate from 1 to `n` (inclusive).
6. In each iteration, print the current value of `i`.
7. Terminate the program.

---

### 🧾 Program

```python
#Write your Code here
def natural(n):
    print('Natural Numbers are :')
    for i in range(1, n+1):
        print(i)
        
n = int(input(""))
natural(n)

```
### OUTPUT
![image](https://github.com/user-attachments/assets/bcc8f978-864c-4521-83a1-d1880c8d0d84)

### RESULT
Thus the program PRINTING N NATURAL NUMBERS have been executed and verified sucessfully

