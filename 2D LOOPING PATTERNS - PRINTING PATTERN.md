# Exp.No:2d
## LOOPING PATTERNS - PRINTING PATTERN

---

### AIM  
Write a Python Program to print the right handled triangle pyramid pattern of Stars

---

### ALGORITHM

1. Begin the program.  
2. Read the integer `n` from the user using `input()`. This will determine the number of rows in the pattern.  
3. Initialize a variable `i = 0`. This will help adjust the spacing before the stars.  
4. Loop through rows from `0` to `n - 1`:  
   - For each row, calculate the number of spaces to print using the formula: `((n - rows - 1) * 2) + i`.  
   - Print the calculated number of spaces using `print(" ", end="")`.  
   - Increment `i` by 1 after each row.  
   - Print stars using a nested loop: the number of stars in each row is `rows + 1`, printed using `print("*", end="  ")`.  
   - Print a newline after each row using `print("")` to move to the next line.  
5. Terminate the program.

---

### PROGRAM
```
#Reg.No:212223070004
#Name:dhushanth
#Add Your Code Here
rows=int(input())
k=2*rows-2
for i in range(0,rows):
    for j in range(0,k):
        print(end=" ")
    k=k-2
    for j in range(0,i+1):
        print("*",end=" ")
    print(" ")    

```

### OUTPUT
![image](https://github.com/user-attachments/assets/b57e08d7-4587-4efa-8499-75250a642fa4)


### RESULT
thus the program is executed successfully
