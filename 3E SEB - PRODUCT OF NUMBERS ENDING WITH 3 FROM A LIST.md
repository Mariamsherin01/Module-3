# Exp.No:3e
## SEB - Product of Numbers Ending with 3 from a List

---

### AIM  

To write a Python program that finds and displays the product of all numbers from a list that end with the digit 3.
---

### ALGORITHM

1.Define a list of integers.

2.Initialize a variable product to 1 and a flag to check if any number ends with 3.

3.Loop through each number in the list.

4.If the number ends with 3 (number % 10 == 3), multiply it with product.

5.After the loop, check if any number ending with 3 was found.

6.If yes, print the product; otherwise, indicate no such number exists.

---

### PROGRAM

```
reg.no: 212222060143
name: Mariam Sherin
l=eval(input())
prod=1
x=len(l)
for i in range(0,x):
    if l[i]%10==3:
        prod*=l[i]
print("Product=",prod)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/2c7783a8-1e70-43b0-9a4b-b97a1cbc1af2)

### RESULT
Thus, The Python program that finds and displays the product of all numbers from a list that end with the digit 3 was implemented and executed successfully.
