# Exp.No:2e  
## SEB - INVERTED PYRAMID PATTERN DECENDING ORDER

---

### AIM  
To write a Python program that displays an inverted pyramid pattern of descending numbers, where each row starts with the row number and repeats it, based on user input for the number of rows.

### ALGORITHM

Start the program.
Input the number of rows n from the user using int(input()).
Use an outer loop i that starts from n and decreases to 1 (i.e., for i in range(n, 0, -1)).
Inside the outer loop, use an inner loop j that also runs from i down to 1 (i.e., for j in range(i, 0, -1)).
Print the value of i in each iteration of the inner loop, with end=" " to keep it on the same line.
After the inner loop completes for a row, use print() to move to the next line.
Repeat steps 4–6 until the pattern is complete.
End the program.

### PROGRAM

```
n = int(input())
for i in range(n,0,-1):
    for j in range(i,0,-1):
        print(i,end=" ")
    print()
```
### OUTPUT
![image](https://github.com/user-attachments/assets/81052922-8229-434e-a3f0-546b863e742f)

### RESULT
Thus the program INVERTED PYRAMID PATTERN DECENDING ORDER have been executed and verified sucessfully.
