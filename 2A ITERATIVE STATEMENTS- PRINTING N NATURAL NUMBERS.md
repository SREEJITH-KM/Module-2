# Exp. No: 2a  


###  Aim
Write a python program to compute whether a given number is an Armstrong Number

---

###  Algorithm
Start

Read an integer from the user.

Store the original number for later comparison.

Count the number of digits (n).

Initialize a sum to 0.

For each digit in the number:

Raise the digit to the power of n and add to the sum.

Compare the sum with the original number:

If equal, it's an Armstrong number.

Else, it's not.

End
---

### 🧾 Program

```python
#Reg.NO 212223070004
#Name dhushanth
#Write your Code here
num=input()
sum=0
for i in num:
    sum+=int(i)**3
if sum==int(num):
    print("The given number",num,"is an Armstrong") 
else:
    print("The given number",num,"is not an Armstrong")

```
### OUTPUT
![image](https://github.com/user-attachments/assets/72bc7da2-943d-4ecf-adf0-e973e3950c8b)

```

```
### RESULT
thus the program is executeed successfully
```

```

